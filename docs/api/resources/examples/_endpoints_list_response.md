<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-12T10:11:26Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_32awEnLaA3oPGD7WfITQ0yLJ9HF",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32awEnLaA3oPGD7WfITQ0yLJ9HF"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32awFQizOfF4rh31hZQc535OMTw",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-09-12T10:11:26Z",
      "uri": "https://api.ngrok.com/endpoints/ep_32awFQizOfF4rh31hZQc535OMTw",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-12T10:11:24Z",
      "hostport": "0e1479d89a52.ngrok.paid:443",
      "id": "ep_32awFCtjV0ONkpwm0vp5AAwZEFc",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_32aw8f2tLMsDnXDJI7XVvGgNp3r",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://0e1479d89a52.ngrok.paid",
      "tunnel": {
        "id": "tn_32awFCtjV0ONkpwm0vp5AAwZEFc",
        "uri": "https://api.ngrok.com/tunnels/tn_32awFCtjV0ONkpwm0vp5AAwZEFc"
      },
      "tunnel_session": {
        "id": "ts_32awFCuDvzL3Dk376QwrFC2Wsmh",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32awFCuDvzL3Dk376QwrFC2Wsmh"
      },
      "type": "ephemeral",
      "updated_at": "2025-09-12T10:11:24Z",
      "upstream_url": "http://localhost:80",
      "url": "https://0e1479d89a52.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-09-12T10:11:21Z",
      "domain": {
        "id": "rd_32awEnLaA3oPGD7WfITQ0yLJ9HF",
        "uri": "https://api.ngrok.com/reserved_domains/rd_32awEnLaA3oPGD7WfITQ0yLJ9HF"
      },
      "edge": {
        "id": "edgtls_32awEk0avucnaUS0rzuWRj5ajfz",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_32awEk0avucnaUS0rzuWRj5ajfz"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_32awEoh7B2HJKjKPRqot5kDw2K0",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-09-12T10:11:21Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
