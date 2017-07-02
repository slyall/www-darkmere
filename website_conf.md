Website Config
==============

rsync -van public/ usenet.net.nz:/var/www/www.darkmere.gen.nz/html/

# todo
* http -> https redirect
* Review any other pages on the old site
* Review photos on the old site

# Apache Config

/etc/apache2/sites-enabled/www.darkmere.gen.nz.conf 

```
	RewriteEngine on
	RewriteRule ^/2007/0129.html  /linux.conf.au_guide	[R=302,L]
	RewriteRule ^/2005/0108.html  /ihug_engineering		[R=302,L]
	RewriteRule ^/2003/0803.html  /bladestroller		[R=302,L]
	RewriteRule ^/2004/0404.html  /domestic_blindness.html	[R=302,L]
```


