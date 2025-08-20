<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-20T10:07:49Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31XxxOhepkPsqDA3GK1go1459tm",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31XxxOhepkPsqDA3GK1go1459tm"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31Xxy3Qr0YZZjLWCEa0E0rh76Bs",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-20T10:07:49Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31Xxy3Qr0YZZjLWCEa0E0rh76Bs",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-20T10:07:47Z",
      "hostport": "bdcbd6dd42ee.ngrok.paid:443",
      "id": "ep_31XxxpXhJNFzz0FYkSnaMcvI84c",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31XxrMJ0tiIh37b1RZMkoFNvuqr",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://bdcbd6dd42ee.ngrok.paid",
      "tunnel": {
        "id": "tn_31XxxpXhJNFzz0FYkSnaMcvI84c",
        "uri": "https://api.ngrok.com/tunnels/tn_31XxxpXhJNFzz0FYkSnaMcvI84c"
      },
      "tunnel_session": {
        "id": "ts_31XxxoXtg9eMcStzhRjJOm14zOm",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31XxxoXtg9eMcStzhRjJOm14zOm"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-20T10:07:47Z",
      "upstream_url": "http://localhost:80",
      "url": "https://bdcbd6dd42ee.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-20T10:07:44Z",
      "domain": {
        "id": "rd_31XxxOhepkPsqDA3GK1go1459tm",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31XxxOhepkPsqDA3GK1go1459tm"
      },
      "edge": {
        "id": "edgtls_31XxxTMJQIZ5lgp8QjABZd1tDG4",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31XxxTMJQIZ5lgp8QjABZd1tDG4"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31XxxUc12hh3iU6WTDrQrKgJcQ0",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-20T10:07:44Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
