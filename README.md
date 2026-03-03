```curl
GET https://tskarcgis.westeurope.cloudapp.azure.com/server/rest/services/LUK/LUK/MapServer/2/queryRelatedRecords?f=json&
    objectIds=1696&outFields=DAY&relationshipId=0&returnGeometry=false
User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:148.0) Gecko/20100101 Firefox/148.0
Accept: */*
Accept-Language: cs,en;q=0.9,en-US;q=0.8,sk;q=0.7
Accept-Encoding: gzip, deflate, br, zstd
Referer: https://tskarcgis.westeurope.cloudapp.azure.com/luk/
```

```json
{
  "fields": [
    {
      "name": "DAY",
      "type": "esriFieldTypeDate",
      "alias": "Den úklidu bloku",
      "length": 8
    }
  ],
  "relatedRecordGroups": [
    {
      "objectId": 1696,
      "relatedRecords": [
        {
          "attributes": {
            "DAY": 1745366400000
          }
        },
        {
          "attributes": {
            "DAY": 1758153600000
          }
        }
      ]
    }
  ]
}
```
