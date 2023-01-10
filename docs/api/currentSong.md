---
sidebar_position: 2
---

# Get Current Song
This endpoint is solely responsible for getting the current song playing.

### Endpoint URL
```
https://oocradio.com/api/1.1/wf/get_song
```

### Example request with curl

```
curl "https://oocradio.com/api/1.1/wf/get_song" \
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
        "Artist": "DJ Khaled, Drake, Lil Baby",
        "Title": "STAYING ALIVE (feat. Drake & Lil Baby)",
        "Cover": "https://i.scdn.co/image/ab67616d0000b273b690b30a50c94c6da49ba948"
    }
}
```