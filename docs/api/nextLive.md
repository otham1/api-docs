---
sidebar_position: 3
---

# Get Next Live
This endpoint is solely responsible for getting the next live show.

### Endpoint URL
```
https://oocradio.com/api/1.1/wf/next_live
```

### Example request with curl

```
curl "https://oocradio.com/api/1.1/wf/next_live" \
  -X GET \
  -H "Accept: application/json" \
  -H "Content-Type: application/json"
}'
```

### Example response

```
HTTP/1.1 200 OK
Content-Type: application/json
{
    "status": "success",
    "response": {
        "Name": "HELIX",
        "Show_Name": "Tune in with HELIX!",
        "Date": 1673463600,
        "Artwork": "https://s3.amazonaws.com/appforest_uf/f1672245315868x740459149083113600/Mario.png",
        "Exists": true
    }
}
```