# [Convert URL to PDF API](https://apishub.com/shahzaibHassan/convert-url-to-pdf-api)

Convert webpage to PDF file by passing any URL.

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| url | string | required | Any valid URL which is publicaly accessible over the Internet. |

### Response Params
Parameter | Type | Explanation |
|---|---|---|
| status | string | Status of API, or error |
| file_url | string | URL of the generated PDF |


### Example Response

```json
{
   "status":"success",
   "file_url":"https://s3.amazonaws.com/apiscafe.com/pdf/pdf_20344.pdf"
}
```
### Demo
[Try here](https://apishub.com/shahzaibHassan/convert-url-to-pdf-api#try-now)
