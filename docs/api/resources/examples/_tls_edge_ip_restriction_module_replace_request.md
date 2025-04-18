<!-- Code generated for API Clients. DO NOT EDIT. -->
#### Example Request
```bash
curl \
-X PUT \
-H "Authorization: Bearer {API_KEY}" \
-H "Content-Type: application/json" \
-H "Ngrok-Version: 2" \
-d '{"enabled":true,"ip_policy_ids":["ipp_2vtiXO5MUBdUeAR8H1U90tv261N","ipp_2vtiXQPVOf9TKAaXCAXhI1KmV7s"]}' \
https://api.ngrok.com/edges/tls/edgtls_2vtiXOmFYZK9yipW3ocnsrAS8xh/ip_restriction
