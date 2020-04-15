# ip-country
A Cloudflare worker to fetch client's ip and country

The worker is hosted at https://ip-country.zeroone.workers.dev

Reponse:

curl https://ip-country.zeroone.workers.dev

{
  "ip": "*.*.*.61", //Masked ip
  "country": "IN"
}
