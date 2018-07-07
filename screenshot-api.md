# [ScreenShot API](https://apishub.com/abdulqadir/screenshot-api)

Get Screenshot of any webpage from the given URL as input

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| URL | string | required | Any valid URL which is publicaly accessible over the Internet. |
| Viewport | string | required | The viewing area of the browser which is making the screenshot request. |
| Fullpage | boolean | Optional | By default screenshots are only of the visible 'above the fold' area of the viewport. If Fullpage is specified, the resulting screenshot will include the entire page, scrolled down to the bottom. |
| Javascript | boolean | Optional |  By default, Javascript is enabled. To disable Javascript while capturing the screenshot, set this to false. This can be useful to prevent pop up banners from covering portions of the page you wish to capture, however some sites will not render properly without Javascript. |
| Webdriver | string | required | Specify the web driver (web browser) to use for the capture. Options are firefox (default) chrome phantomjs  |

### Response Params
Parameter | Type | Explanation |
|---|---|---|
| status | string | Status of API, ready or error |
| imageUrl | string | URL of the captured screenshot |

### Example Requests

```json
{
  "url": "https://apishub.com/abdulqadir/screenshot-api",
  "viewport": "1280x1024",
  "fullpage": false,
  "javascript": true,
  "webdriver": "firefox",
  "waitSeconds": 0,
  "fresh": false
}
```

### Example Response

```json
{
  "status": "ready",
  "imageUrl": "https://screenshotapi.s3.amazonaws.com/captures/6e5835db1602b82a0ad0d441d2d647e1.png"
}
```
### Demo
[Try here](https://apishub.com/abdulqadir/screenshot-api#try-now)
