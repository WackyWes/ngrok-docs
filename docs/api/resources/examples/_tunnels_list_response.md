<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tunnels": [
    {
      "endpoint": {
        "id": "ep_32awDvPI7HzTtR7bdIYc13HDbyg",
        "uri": "https://api.ngrok.com/endpoints/ep_32awDvPI7HzTtR7bdIYc13HDbyg"
      },
      "forwards_to": "http://localhost:80",
      "id": "tn_32awDvPI7HzTtR7bdIYc13HDbyg",
      "proto": "https",
      "public_url": "https://943a2ce57bc7.ngrok.paid",
      "region": "us",
      "started_at": "2025-09-12T10:11:14Z",
      "tunnel_session": {
        "id": "ts_32awDoP7SXTZKESUZsQScXq3pS6",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32awDoP7SXTZKESUZsQScXq3pS6"
      }
    },
    {
      "forwards_to": "http://localhost:80",
      "id": "tn_32awDI8s7aTppOmkI7Z7GnF17cd",
      "labels": {
        "baz": "qux",
        "foo": "bar"
      },
      "region": "us",
      "started_at": "2025-09-12T10:11:09Z",
      "tunnel_session": {
        "id": "ts_32awDIjRMZFeZ64vkhwJGB0q9Ro",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_32awDIjRMZFeZ64vkhwJGB0q9Ro"
      }
    }
  ],
  "uri": "https://api.ngrok.com/tunnels"
}
```
