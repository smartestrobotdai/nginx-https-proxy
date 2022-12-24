# nginx-https-proxy
use nginx as https reverse proxy with docker-compose 

# Setup
1. Make sure docker & docker-compose are installed.
2. git clone git@github.com:smartestrobotdai/nginx-https-proxy.git
3. cd nginx-https-proxy
4. docker-compose -f docker-compose.yml up

# Test
curl --insecure https://localhost

You should see below HTML code:
<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
<style>
html { color-scheme: light dark; }
body { width: 35em; margin: 0 auto;
font-family: Tahoma, Verdana, Arial, sans-serif; }
</style>
</head>
<body>
<h1>Welcome to nginx!</h1>
<p>If you see this page, the nginx web server is successfully installed and
working. Further configuration is required.</p>

<p>For online documentation and support please refer to
<a href="http://nginx.org/">nginx.org</a>.<br/>
Commercial support is available at
<a href="http://nginx.com/">nginx.com</a>.</p>

<p><em>Thank you for using nginx.</em></p>
</body>
</html>
