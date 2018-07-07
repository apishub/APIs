# [Detect Language API](https://apishub.com/abdulqadir/detect-language)

Detects text language

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| q | string | required | Any language text |

### Response Params
Parameter | Type | Explanation |
|---|---|---|
| language | string | ISO Language Code |
| isReliable | boolean | text contains words in different languages then isReliable: true would identify that first detected language is significantly more probable than the second one. When only one language is detected isReliable: false would mean that confidence is very low. |
| confidence | double | Confidence value depends on how much text you pass and how well it is identified. The more text you pass, the higher confidence value will be. It is not a range, it can be higher than 100. |


### Example Response

```json
{
   "data":{
      "detections":[
         {
            "language":"en",
            "isReliable":true,
            "confidence":11.94
         }
      ]
   }
}
```
### Demo
[Try here](https://apishub.com/abdulqadir/detect-language#try-now)
