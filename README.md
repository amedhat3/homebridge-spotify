# homebridge-spotify
## Example config.json
```
{
    "bridge": {
        "name": "Homebridge",
        "username": "CC:22:3D:E3:CE:32",
        "port": 51826,
        "pin": "031-45-154"
    },
    
    "description": "This is an example configuration file with one fake accessory and one fake platform. You can use this as a template for creating your own configuration file containing devices you actually own.",

    "accessories": [
        {
          "accessory": "Spotify",
          "name": "Spotify",
          "playlist": "spotify:user:abc123:playlist:xyz",
          "playlist_position": 6,
          "deviceId": "12345",
          "tokenUrl": "https://accounts.spotify.com/api/token",
          "volumeUrl": "https://api.spotify.com/v1/me/player/volume?volume_percent=25",
          "shuffleUrl": "https://api.spotify.com/v1/me/player/shuffle?state=true",
          "playUrl": "https://api.spotify.com/v1/me/player/play",
          "base64clientToken": "<base64(clientid:clientsecret)>",
          "refreshToken": "xyz789"
        }
    ],

    "platforms": [

    ]
}
```
