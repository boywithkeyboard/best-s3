## What's the best storage service?

| Name | (Promised) Durability | Storage | Egress | Rate Limit | Upload | Download |
| --- | --- | --- | --- | --- | --- | --- |
| [Storj](https://www.storj.io) | 11 nines | $0.004 / GB | $0.007 / GB | 100 req/s | / | / |
| [Cloudflare R2](https://developers.cloudflare.com/r2/) | 11 nines | $0.015 / GB | / | / | $4.50 / million | $0.36 / million |
| [Vultr](https://www.vultr.com/products/object-storage/) | ? | $0.005 / GB | $0.01[^1] / GB | 400 req/s/ip | / | / |
| [Contabo](https://contabo.com/en/object-storage/) | ? | $0.01196 / GB | / | 250 req/s | / | / |
| [Backblaze](https://www.backblaze.com/cloud-storage/pricing) | ? | $0.006 / GB | $0.01[^1][^2] / GB | ? | / | $0.4 / million |

[^1]: Egress is free within the [Bandwidth Alliance](https://www.cloudflare.com/bandwidth-alliance/).
[^2]: Egress is free up to a certain limit.
