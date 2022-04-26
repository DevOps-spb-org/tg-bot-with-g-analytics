# tg-bot-with-g-analytics

To capture the event we need to send the following data

```
{
    'client_id': uniq_user_id,
    'events': [{
        'name': event_name,
    }],
}
```

to this host

https://www.google-analytics.com/mp/collect?measurement_id={MEASUREMENT_ID}&api_secret={API_SECRET}

MEASUREMENT_ID - data stream identifier (G-code)

API_SECRET - The value of the secret key to be created in the Measurement Protocol API tab