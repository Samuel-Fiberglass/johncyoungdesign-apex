# johncyoungdesign.com bare-domain redirect

The site lives at https://www.johncyoungdesign.com on Cloudflare Pages.
The bare domain's DNS is at Namecheap, whose URL redirect cannot answer https.
GitHub Pages serves this stub on the bare domain with a free certificate and
sends every path on to the same path on www.

DNS at Namecheap for host `@`: A records 185.199.108.153, 185.199.109.153,
185.199.110.153, 185.199.111.153. The `www` CNAME is not part of this.
