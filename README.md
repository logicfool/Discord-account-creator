# Discord-Account-Generator

Proof of concept of how Discord accounts can be created without the need to type/ click buttons on a browser.

### NEW VERSION

- Added captcha bypass, (made chromedriver undetected) (Does not work yet! Tried to )

## About

A script that automates creating discord accounts. It shows how accounts can be created automatically without the user typing unless there is a captcha. This is used for educational purposes only

## Preview

![Picture](https://i.ibb.co/jWK1dpP/Captura.png)

## Usage

1. You can customize usernames by editing the usernames in discord_usernames.txt.
2. Run the file and use normal mode if you are a beginner/inexperienced with proxies and theading.

### Get Python

If you dont have python installed, download python 3.7.6
and make sure you click on the 'ADD TO PATH' option during
the installation.

### Run via Python

1. install the required modules

```
pip install -r requirements.txt
```

2. To run the script..

```
python discordgenerator.py
```

### Run via Exe Version

1. Extract the .rar file
2. Run the exe file
3. Do not take out the program out of the folder

#### Proxy support

If you want to use proxies, simply paste the proxies in config/proxies.txt.  If you want to stop using proxies, just remove all the proxies from the .txt file. The script automatically checks for proxies on startup. HTTP as well as SOCKS4/5 proxies are supported also supports proxy authentication

Note:

```
- Input Proxies in specific format below
       -if proxy has username pass then proxytype://proxyusername:proxypass@proxyhost:proxyport
       -else proxytype://proxyhost:proxyport
       - Herer proxytype is HTTP/S or Socks4/5
```

#### Threading mode

- Uses multiple chrome windows
- Only run this when you have proxies or else one of you Chrome windows will get rate limited.
- Do put more than 6 threads unless you think your PC can handle it. I recommend using 2-3 threads.

#### No Threading

- This only uses one chrome window.

#### TROUBLESHOOT

ONLY IF IT IS NOT WORKING

1. Create a Ticket and let me know the problem

Where can i found my generated accounts?

It is located in the output folder. Open up login.txt to see the accounts
that has been generated.
