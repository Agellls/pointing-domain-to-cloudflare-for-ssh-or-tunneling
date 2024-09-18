# Pointing domain to cloudflare for ssh or tunneling

The first time is you have to create account <a href="https://dash.cloudflare.com/login">cloudflare</a>

## Pointing Domain

<li> Add your domain like this picture, then press continue

![OAuth Credential File](assets/Screenshot_1.png)

<li> After that please input the nameservers to your domain nameservers

![OAuth Credential File](assets/Screenshot_2.png)

![OAuth Credential File](assets/Screenshot_3.png)

<li> Delete all DNS management on there until empty

![OAuth Credential File](assets/Screenshot_4.png)

## Setting cloudflare

- SSL/TLS : FULL
- GRPC (Network) : ON
- WEBSOCKET (Network) : ON
- Always Use HTTPS (SSL/TLS > Edge Certificates) : OFF

![OAuth Credential File](assets/Screenshot_5.png)
![OAuth Credential File](assets/Screenshot_6.png)
![OAuth Credential File](assets/Screenshot_7.png)
![OAuth Credential File](assets/Screenshot_8.png)

Finally the setup done, now if you wanna use the pointing to vps the step like this

## Pointing IP VPS

<li> Now this how to pointing your ip VPS

![OAuth Credential File](assets/Screenshot_9.png)

- type = "A"
- Name (required) = yoursubname
- IPv4 address (required) = youripvps
- Proxy status = off (DNS only)
- TTL = Auto

![OAuth Credential File](assets/Screenshot_10.png)

then save, and here we go now your domain and your ip vps ready to use create shh, happy coding :D
