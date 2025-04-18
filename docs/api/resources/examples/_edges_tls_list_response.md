<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-04-18T10:06:48Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_2vtiXHQQ8xDvY3E7dKCg2LzGgaU",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vtiXHQQ8xDvY3E7dKCg2LzGgaU"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_2vtiW2DnmoY7XDjCCbs3JRMOCZd",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_2vtiW2DnmoY7XDjCCbs3JRMOCZd"
        },
        "enabled": true
      },
      "created_at": "2025-04-18T10:06:38Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_2vtiW1XvcfyUd9g5oCgRkc586PE",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_2vtiW1XvcfyUd9g5oCgRkc586PE"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
