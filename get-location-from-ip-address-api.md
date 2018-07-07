# [Get Location from IP Address API](https://apishub.com/abdulqadir/get-location-from-ip-address)

Get information about city, country region etc from public IP

### Input Params
Parameter | Type | Requirement | Explanation |
|---|---|---|---|
| ip | string | required | Any valid Public IP, which is publicaly accessible over the Internet. |

### Response Params
Parameter | Type | Explanation |
|---|---|---|
| city | string | City of the IP |
| country | string | Country of the IP |
| countryCode | string | Country Code |
| isp | string | Internet service provider of the IP |
| lat | double | Latitude of the IP area |
| lon | double | Longitude of the IP area |
| org | string |  |
| query | string | IP Address |
| region | string |  |
| regionName | string | URL of the captured screenshot |
| status | string | Status of request |
| timezone | string | URL of the captured screenshot |
| zip | string | Zip of IP City |


### Example Response

```json
{
   "as":"AS9541 Cyber Internet Services (Pvt) Ltd.",
   "city":"Karachi",
   "country":"Pakistan",
   "countryCode":"PK",
   "isp":"Cyber Internet Services (pvt.)",
   "lat":24.9056,
   "lon":67.0822,
   "org":"Cyber Internet Services (Pvt)",
   "query":"203.101.180.17",
   "region":"SD",
   "regionName":"Sindh",
   "status":"success",
   "timezone":"Asia/Karachi",
   "zip":"12311"
}
```
### Demo
[Try here](https://apishub.com/abdulqadir/get-location-from-ip-address#try-now)
