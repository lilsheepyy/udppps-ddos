# udppps

Golang script to send small udp packets(15 bytes) for a high rate. It depends on the server you are running it and how you run it.
Usage: ./udppps.go -ip <ip> -port <port> -pps <pps> -duration <duration> [-threads <threads>]

I made this for roblox servers but also works for r6 unranked and homes didn´t tested in other targets.

If you get permission denied error, just do this: chmod +x udppps
