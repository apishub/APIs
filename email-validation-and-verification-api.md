# [Email Validation and Verification API](https://apishub.com/manisha_kumari/email-validation-and-verification-api)

Validate and verify email address

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| email | string | required | Any string need to validate or verify |

### Response Params
Parameter | Type | Explanation |
|---|---|---|
| email | string | Contains the exact email address requested |
| did_you_mean | string | Contains a did-you-mean suggestion in case a potential typo has been detected. |
| format_valid | boolean | Returns true or false depending on whether or not the general syntax of the requested email address is valid. |
| mx_found | boolean | Returns true or false depending on whether or not MX-Records for the requested domain could be found. |
| smtp_check | boolean | Returns true or false depending on whether or not the SMTP check of the requested email address succeeded. |
| catch_all | boolean | Returns true or false depending on whether or not the requested email address is found to be part of a catch-all mailbox. |
| role | boolean | Returns true or false depending on whether or not the requested email address is a role email address. (e.g. 'support@company.com', 'postmaster@company.com') |
| disposable | boolean | Returns true or false depending on whether or not the requested email address is a disposable email address. (e.g. 'user123@mailinator.com') |
| free | boolean | Returns true or false depending on whether or not the requested email address is a free email address. (e.g. "user123@gmail.com", "user123@yahoo.com") |
| score | double | Returns a numeric score between 0 and 1 reflecting the quality and deliverability of the requested email address. |


### Example Response

```json
{
   "email": "support@apishub.com",   
   "did_you_mean": "",
   "format_valid": true,
   "mx_found": true,
   "smtp_check": true,
   "catch_all": false,
   "role": true,
   "disposable": false,
   "free": false,
   "score": 0.8
}
```
### Demo
[Try here](https://apishub.com/manisha_kumari/email-validation-and-verification-api#try-now)
