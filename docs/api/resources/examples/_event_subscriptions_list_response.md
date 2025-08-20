<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-08-20T10:07:50Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_31XxyDzMrHKGPMplCWAwXj2q0GB",
          "uri": "https://api.ngrok.com/event_destinations/ed_31XxyDzMrHKGPMplCWAwXj2q0GB"
        }
      ],
      "id": "esb_31XxyAcrgJZjJRuJZhl39U9MrUo",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_31XxyAcrgJZjJRuJZhl39U9MrUo/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_31XxyAcrgJZjJRuJZhl39U9MrUo"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
