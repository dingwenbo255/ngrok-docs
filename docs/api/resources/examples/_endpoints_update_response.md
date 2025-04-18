<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "bindings": [
    "public"
  ],
  "created_at": "2025-04-18T10:06:43Z",
  "description": "Sample Cloud Endpoint",
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
}
