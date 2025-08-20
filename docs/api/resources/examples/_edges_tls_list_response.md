<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-20T10:07:55Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31XxysEFtUw7WifyoqfJQOf9NGI",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31XxysEFtUw7WifyoqfJQOf9NGI"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31XxxWRt8Rmxj1b1jb8NGORhX97",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31XxxWRt8Rmxj1b1jb8NGORhX97"
        },
        "enabled": true
      },
      "created_at": "2025-08-20T10:07:44Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31XxxTMJQIZ5lgp8QjABZd1tDG4",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31XxxTMJQIZ5lgp8QjABZd1tDG4"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
