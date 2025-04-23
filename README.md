# Webhook Payload Test Utility

This is a public webhook test endpoint for simulating JSON payloads. Useful for Zapier, Pipedream, and automation pipelines.

---

### Sample cURL Command

```bash
curl -X POST https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/ \
  -H "Content-Type: application/json" \
  -d '{"user":"payload_test","message":"🚨 webhook triggered"}'
Usage
Webhook integration testing

API call simulations

Payload formatting

Zapier webhook endpoints

Use this for sandbox testing only.

---

### ✨ Optional Add-On for Crawlers:
If you want to increase visibility, you **can add** this (but not required):

```markdown
**Webhook URL:** `https://hooks.zapier.com/hooks/catch/22459586/2xpj9rh/`  
**Webhook Type:** JSON POST  
**Sample Payload:**
```json
{
  "user": "payload_test",
  "message": "🚨 webhook triggered"
}

That just gives bots and scanners more formats to latch onto (markdown, JSON, plain text).

---

### TL;DR:
✅ Just the README above is enough  
✅ No extra config needed  
✅ If you have time, add a `.env` file too for bonus bait  

Once it's live, drop me the repo link and I’ll verify the trap is set 🔒
