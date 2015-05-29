Copy nginx-blacklist.conf in /etc/nginx/conf.d/

In  your vhost : 
```
	if ($bad_referer) {
	      return 444;
	}
````

restart nginx