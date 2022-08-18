# Ubuntu 22.04. Login Screen Customizer

Download the script with the following command:

````
curl -L -O https://raw.githubusercontent.com/cmar0ck/ubuntu-22-04-login-screen-customizer/main/ubuntu-22-04-set-background.sh
````

There are four options:
1. Background image
2. Background color
3. Background gradient horizontal (requires two valid hex colors)
4. Background gradient vertical (requires two valid hex colors)

Tip: You can pick colors from https://www.color-hex.com/

Example Commands:

1. `sudo ./ubuntu-22-04-set-background --image /home/user/backgrounds/image.jpg`
2. `sudo ./ubuntu-22-04-set-background --color #AABBCC`
3. `sudo ./ubuntu-22-04-set-background --gradient horizontal #AABBCC #DDEEFF`
4. `sudo ./ubuntu-22-04-set-background --gradient vertical #AABBCC #DDEEFF`
5. `sudo ./ubuntu-22-04-set-background --reset`
6. `./ubuntu-22-04-set-background --help`

RESCUE_MODE, Example Commands:

1. `sudo ./ubuntu-22-04-set-background --image /home/user/backgrounds/image.jpg rescue`
2. `sudo ./ubuntu-22-04-set-background --color #AABBCC rescue`
3. `sudo ./ubuntu-22-04-set-background --gradient horizontal #AABBCC #DDEEFF rescue`
4. `sudo ./ubuntu-22-04-set-background --gradient vertical #AABBCC #DDEEFF rescue`

Why RESCUE_MODE?
If another script created conflicts with your configuration add 'rescue' to the end of the command as mentiond above.

(Please note that for 'RESCUE_MODE' an active internet connection is required.)
