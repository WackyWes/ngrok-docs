<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-09-12T10:11:32Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_32awGB8QO4piEXgumT1MUKBYUMa",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32awGB8QO4piEXgumT1MUKBYUMa"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_32awEoT6tU4WK44ND3grE3gAH36",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_32awEoT6tU4WK44ND3grE3gAH36"
        },
        "enabled": true
      },
      "created_at": "2025-09-12T10:11:21Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_32awEk0avucnaUS0rzuWRj5ajfz",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_32awEk0avucnaUS0rzuWRj5ajfz"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
