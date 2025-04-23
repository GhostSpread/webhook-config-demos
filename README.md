# webhook-config-demos
# Webhook Payload Simulator for Zapier & Automation Testing

Use this endpoint for simulating inbound webhook calls:

**POST Endpoint:**
`https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/`

---

### Sample cURL

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"user":"payload_test","message":"🚨 webhook triggered"}'
