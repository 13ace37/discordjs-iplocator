# discordjs-iplocator
Geolocate IP / Resolve Domain

# Commands
- Geolocate IP - `.locate [IP]`
- Resolve Domain - `.resolve [DOMAIN]`

# Output

- Resolve Domain

```JSON 
[
    {
        "address": "172.217.168.46",
        "ttl": 0,
        "type": "A"
    },
    {
        "address": "2a00:1450:400a:801::200e",
        "ttl": 1,
        "type": "AAAA"
    },
    {
        "exchange": "alt2.aspmx.l.google.com",
        "priority": 30,
        "type": "MX"
    },
    {
        "exchange": "alt4.aspmx.l.google.com",
        "priority": 50,
        "type": "MX"
    },
    {
        "exchange": "aspmx.l.google.com",
        "priority": 10,
        "type": "MX"
    },
    {
        "exchange": "alt3.aspmx.l.google.com",
        "priority": 40,
        "type": "MX"
    },
    {
        "exchange": "alt1.aspmx.l.google.com",
        "priority": 20,
        "type": "MX"
    },
    {
        "value": "ns4.google.com",
        "type": "NS"
    },
    {
        "value": "ns1.google.com",
        "type": "NS"
    },
    {
        "value": "ns2.google.com",
        "type": "NS"
    },
    {
        "value": "ns3.google.com",
        "type": "NS"
    }
]
```

- Geolocate IP

``` JSON
{
    "status": "success",
    "as": "AS15169",
    "city": "",
    "country": "United States",
    "countryCode": "US",
    "isp": "Google LLC",
    "lat": 37.751,
    "lon": -97.822,
    "org": "Google LLC",
    "query": "172.217.168.46",
    "region": "",
    "regionName": "",
    "timezone": "",
    "zip": ""
}
```


`http://www.google.com/maps/place/37.751,-97.822`

# Installing
- `git clone 13ace37/discordjs-iplocator`
- `npm i`
- enter ur bot-token in the `config.json`
- `node iplocator.js`
