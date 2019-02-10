# plex-streaming-gateway

This docker compose file brings up a telly gateway which let you configure Plex DVR with streams published by tv channels.  

It currenlty contains channels from RTBF, FranceTV, Euronews, TV5 monde and Arte.  FranceTV channels are geo-locked so if you are outside France, you need to use a proxy.

You can add additional channels by adding streamlink containers.  Note that the telly image needs to be adapted (https://github.com/dafal/docker-telly/blob/master/playlist.m3u) in this case.