title: HTTP2 ready
date: 2015-10-20 21:50:04
tags:
- HTTP2
- Linux
---
This blog site is finally HTTP2 ready. Let's review the techniques used by this blog.
![Arch Apache Hexo](/aah.png)

##### Hosting
This website is hosted by a Amazon EC2 instance in west coast. The instance is reserved for a year so it only costs $75.

##### OS
This website is powered ArchLinux. Without the unnecessary pre-installed softwares, this OS only requires 90MB ~ 110MB memory.

##### Web server
The web server is Apache. The newest Apache ships with [mod_h2](https://icing.github.io/mod_h2/), the HTTP/2 support. I also tried h2c (HTTP/2 without TLS). Apparently mainstream browsers don't support it.

##### Blog software
I just shift to hexo from Wordpress. There are two reasons. Hexo generates static web pages from Markdown files. Compared to Wordpress, which uses PHP + MySQL, it seems to be more lightweight. The second reason is I love writing Markdown.

##### Certificate
I just bought this Comodo SSL certificate for $4.99 each year as SSL is a must for HTTP/2.
