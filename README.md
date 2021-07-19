## <h3 align="center">DropGala Database Configuration</h3>

### Database Diagram:

<p align="center"><img src="db-diagram.png" width="80%"/></p>

Website : https://dropgala.com

### pgadmin ssh:

check: https://medium.com/3-elm-erlang-elixir/faq-how-to-connect-pgadmin4-to-db-through-ssh-tunnel-with-public-key-authentication-b351750c20be

Nginx-keepalive: https://www.digitalocean.com/community/tutorials/how-to-set-up-highly-available-web-servers-with-keepalived-and-floating-ips-on-ubuntu-14-04

### environment variables

Setting an environment variable for a droplet is a little more complicated than for an app running on the app platform.

Follow these steps to set environment variables on a Linux droplet:

SSH into your droplet. If you’re not sure how to do that, see here
Once connected, run the following command to set your environment variable:

```bash
$ export YOUR_VARIABLE_KEY=<your-variable-value>
```