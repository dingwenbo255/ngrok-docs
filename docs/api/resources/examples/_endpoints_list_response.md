<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-18T10:06:43Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_2vtiVxCp9Iq6IswGQa5upK2ApPb",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vtiVxCp9Iq6IswGQa5upK2ApPb"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vtiWfvQFNoPGbGoapMOQbLsoK3",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-04-18T10:06:43Z",
      "uri": "https://api.ngrok.com/endpoints/ep_2vtiWfvQFNoPGbGoapMOQbLsoK3",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-18T10:06:41Z",
      "hostport": "6a7bd5d230b9.ngrok.paid:443",
      "id": "ep_2vtiWM4LLmKXRBMQDHlBeCBpF5i",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_2vtiTs5QjA2WrvDdkGLQXuBY1JI",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://6a7bd5d230b9.ngrok.paid",
      "tunnel": {
        "id": "tn_2vtiWM4LLmKXRBMQDHlBeCBpF5i",
        "uri": "https://api.ngrok.com/tunnels/tn_2vtiWM4LLmKXRBMQDHlBeCBpF5i"
      },
      "tunnel_session": {
        "id": "ts_2vtiWMH53uPb6rfzLcyfzaCd59k",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_2vtiWMH53uPb6rfzLcyfzaCd59k"
      },
      "type": "ephemeral",
      "updated_at": "2025-04-18T10:06:41Z",
      "upstream_url": "http://localhost:80",
      "url": "https://6a7bd5d230b9.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-04-18T10:06:39Z",
      "domain": {
        "id": "rd_2vtiVxCp9Iq6IswGQa5upK2ApPb",
        "uri": "https://api.ngrok.com/reserved_domains/rd_2vtiVxCp9Iq6IswGQa5upK2ApPb"
      },
      "edge": {
        "id": "edgtls_2vtiW1XvcfyUd9g5oCgRkc586PE",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_2vtiW1XvcfyUd9g5oCgRkc586PE"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_2vtiVxDi38qODBeKeNeXpNMwUUt",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-04-18T10:06:39Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
