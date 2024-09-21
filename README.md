# Waymap - Web Vulnerability Scanner
Version: 1.0.4
Author: Trix Cyrus
Copyright: © 2024 Trixsec Org

## What is Waymap?
Waymap is a fast and optimized web vulnerability scanner built for penetration testers. It helps in identifying vulnerabilities such as SQL Injection and Command Injection by testing against various payloads.

Demo Video
Check out this video to see Waymap in action:

![Waymap Demo](https://github.com/TrixSec/waymap/blob/main/demo/lv_0_20240921113323.mp4?raw=true)

![SQL Injection ](https://github.com/TrixSec/waymap/blob/main/demo/sqli-demo.png?raw=true)


![Command Injection](https://github.com/TrixSec/waymap/blob/main/demo/cmdi-demo.png?raw=true)


### v1.0.3 features
#### sql injection
#### command injection
#### web crawling

### v1.0.4 update

#### updated crawler to crawl url in target domain boundary and handle target url redirection 

#### added auto update for scanner (for that reclone the repo if you are using v1.0.4)

### v1.0.5 
#### Fixed minor bugs(reclone the repo if you're using v1.0.4)

## Next Update Very Soon: 1.1.3

#### LFI Module 
#### RCE Module 
#### Maybe Dork Scraper


## Installation and Usage

### Clone the repository:

``` git clone https://github.com/TrixSec/waymap.git ```

### Install the required dependencies:

```pip install .  ```
### Run Waymap:

 ``` python waymap.py --crawl 1 --scan sql/cmdi --target https://example.com ```

 #### CHECK HELP
``` python waymap.py -h ```

### Follow Us on Telegram

Stay updated with the latest tools and hacking resources. Join our Telegram Channel by clicking the Telegram logo below:

[![Telegram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/82/Telegram_logo.svg/240px-Telegram_logo.svg.png)](https://t.me/Trixsec)


### Happy Hacking
~ TrixSec
