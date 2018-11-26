# Yara CryptoHunter

Yara rule to match any listed cryptocurrency exchange's api.

## Installation & Usage

Download to your project directory, run with yara

```sh
~ $ yara -s CryptoExchangeApi.yar test.txt
CryptoExchangeApi test.txt
0x17ed:$a: api.binance.com
0x5c7d:$a: api.binance.com
0xf8c:$a3: anybits.com/api
0xfac:$a3: anybits.com/api
0xfdf:$a3: anybits.com/api
0x179f:$aa7: api.fcoin.com
0x1792:$aac: api.gdax.com
0x2315:$aaj: api.itbit.com
```
