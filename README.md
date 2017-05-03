# Medic Kiosk
[Workshop Link](http://steamcommunity.com/sharedfiles/filedetails/?id=771173724)
### Installation
1. Download ZIP from [releases](https://github.com/Leeous/medic-kiosk/releases)
2. Extract to `[server directory]/garrysmod/addons`
3. Run the server
4. The _Medic Kiosk_ entity is automatically added to the **TEAM_MEDIC** job

Remember - this version is the **latest** and might have bugs! Scary!
If you're looking for a version you can use on your server, check the [releases](https://github.com/Leeous/medic-kiosk/releases) page.
Do not use this version for your server if it is public.

## Server console variables

Remember to define these in your server console and not your _server.cfg_.
Like this:
![](http://i.imgur.com/Ad9mFLc.gif)

| Variable | Value | Description |
| --- | --- | --- |
| medickiosk_limit | `number value` | How many Medic Kiosks one player can have at a time. |
| medickiosk_disableautoadd | `true` or `false` | Whether or not the Medic Kiosk should be <br/> automatically added to the job **TEAM_MEDIC**. <br/>_Useful for people want to add the Medic Kiosk to custom jobs_.|
| medickiosk_price | `number value` | How much it cost the medic to buy the Medic Kiosk. |
| medickiosk_maxprice | `number value` | The maximum price the medic can charge for people to use their Kiosk. |
