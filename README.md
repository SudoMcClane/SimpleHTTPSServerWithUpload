# SimpleHTTPSServerWithUpload
Simple HTTPS Server With Upload written in Python.

Based on Alexander Gent's SimpleHTTPServerWithUpload:
https://github.com/Tallguy297/SimpleHTTPServerWithUpload

## How to

* Go into the project directory
	`cd /path/to/SimpleHTTPSServerWithUpload`
* Generate an SSL certificate
	`openssl req -x509 -newkey rsa:2048 -keyout ssl/key.pem -out ssl/cert.pem -days 365`
* Go into the server's root directory
	`cd srv/`
* Launch the server
	`python ../SimpleHTTPSServerWithUpload.py`

_Don't forget your firewall rules_
