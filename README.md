
# BTCUSD #

Simple Bitcoin to USD CLI converter.

## USAGE ##

```
btcusd [OPTIONS] [VALUE]

OPTIONS:
-h		--help		Displays this message
-u		--usd		Converts USD to BTC
-b		--btc		Converts BTC to USD
```

Convert 455 USD to BTC (Does not reflect actual output)

```bash
btcusd -u 455
#=> 0.984729 BTC
```

Convert 4.32 BTC to USD (Does not reflect actual output)

```bash
btcusd -b 4.32
#=> 2129.76 USD
```

