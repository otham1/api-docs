---
sidebar_position: 4
---

# Get Live Data
This endpoint is responsible for pulling live data from our website. It will pull the current song, similiar to the current song endpoint, and it will also pull the current DJ.

### Endpoint URL
```
https://oocradio.com/api/1.1/wf/get_live_data
```

### Example request with curl

```
curl "https://oocradio.com/api/1.1/wf/get_live_data" \
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
        "Artist": "Metro Boomin, Future, Chris Brown",
        "Title": "Superhero (Heroes & Villains) [with Future & Chris Brown]",
        "Cover": "https://i.scdn.co/image/ab67616d0000b27313e54d6687e65678d60466c2",
        "OnAir_Name": "AutoDJ",
        "OnAir_Artwork": "https://i.imgur.com/Q3yLgpG.png",
        "Spotify_URL": "https://open.spotify.com/track/0vjeOZ3Ft5jvAi9SBFJm1j"
    }
}
```