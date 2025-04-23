# Webhook Payload Test Utility

This is a public webhook test endpoint for simulating JSON payloads. Useful for Zapier, Pipedream, and automation pipelines.

---

### Sample cURL Command

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"user":"payload_test","message":"🚨 webhook triggered"}'
```

---

### Usage
- Webhook integration testing  
- API call simulations  
- Payload formatting  
- Zapier webhook endpoints

---

### Optional Add-On for Crawlers

**Webhook URL:**  
`https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/`

**Webhook Type:**  
JSON POST

**Sample Payload:**

```json
{
  "user": "payload_test",
  "message": "🚨 webhook triggered"
}
```

---

_Use this repo for sandbox testing only._
