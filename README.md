# tv-api
API for Terebi no Tomo Channel

There are two parts to the API, one which handles incoming POST requests from the channel, and the other for file generation.

Handling the POST requests is currently under development.

## File Generation API
The part of the API that is used for file generation is meant to be a companion to [this api.](https://github.com/iptv-org/api)
We host a list of channels that we will use from their API as many of their channels listed do not air in the countries they are listed in.

Example:
```json
{
  "countries": [
    {
      "name": "Andorra",
      "channels": [
        {
         "name": "Andorra TV",
         "slug": "AndorraTV.ad",
         "channel_id": 1,
        }
      ],
    }
  ],
} 
```
