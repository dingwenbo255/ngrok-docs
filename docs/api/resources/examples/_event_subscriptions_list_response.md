<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Response
```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-04-18T10:06:44Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_2vtiWkKf2qz9jdjgZrqhnqD7mis",
          "uri": "https://api.ngrok.com/event_destinations/ed_2vtiWkKf2qz9jdjgZrqhnqD7mis"
        }
      ],
      "id": "esb_2vtiWkexOqw5ej1oZaP2DI18R3P",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_2vtiWkexOqw5ej1oZaP2DI18R3P/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_2vtiWkexOqw5ej1oZaP2DI18R3P"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
