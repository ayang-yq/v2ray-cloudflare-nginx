# v2ray-cloudflare-nginx

### request a domain in namecheap and issue a certificate

### setup Cloudflare as the Name server
https://www.namecheap.com/support/knowledgebase/article.aspx/9607/2210/how-to-set-up-dns-records-for-your-domain-in-cloudflare-account/ 

Note: you may choose "Full" instead of "Full (strict)" for SSL/TLS setting in Cloudflare if your certificate is not issued by a trusted CA. (Namecheap offers SSL certificates signed by Comodo Certificate Authority, no idea why it doesn't work with "Full (strict)" mode)

### Ref
https://ericclose.github.io/V2Ray-TLS-WebSocket-Nginx-with-Cloudflare.html 