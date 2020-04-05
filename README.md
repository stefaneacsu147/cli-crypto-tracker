# Coindex CLI

CLI made with nodeJS to check the activities of your coin(s)

Register an API key at https://nomics.com (you can use other one is not only for this one)

## Usage

```
npm install

npm link (may not work that well on Windows 10)
```

## Commands

```
# Help & Commands
coindex -h

# Version
coindex -V

# API Key Commands
coindex key set
coindex key show
coindex key remove

# Crypto check commands
coindex check price

# Check specific coins (default: BTC, ETH, XRP)
coindex check --coin=BTC, ETH

# Choose Currency (Default: EUR)
coindex check --currency=EUR
```

### Version

0.0.1

### License

MIT
