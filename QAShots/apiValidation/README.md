# 🌟 Exploratory / Functional rest API Validation

Hello QA friends! 👋  
Today I want to share some thoughts on **exploratory / functional rest API validation**.  
This is a checklist I often follow — simple, practical, and super useful in my daily work:

---

## 🚀 Starting from the basics

- 📝 **Headers**: Always check `content-type` and `accept`. Most APIs use `application/json`, but make sure other types aren’t accepted.  
- 📦 **Request & Response body**: Validate the schema, confirm required/optional fields, and check if data types match the documentation.  
- ⚙️ **Business rules**: Exercise the business logic directly through the API to ensure it behaves as expected.  
- ⏱️ **Performance**: Even if it’s not a formal performance test, latency observations can give you valuable hints.  
- 🔑 **Main HTTP methods**: The API should return the right status codes (`200 OK`, `201 Created`, etc.), consistent with your scenario.  
- ❌ **Error codes**: Don’t forget the “unhappy paths”! Good error handling means clear codes + easy-to-understand messages.  
- 🧭 **Heuristics + context**: Test with the software context in mind, but lean on heuristics to uncover critical points.  
- 🔒 **Data security**: Sensitive data must be tokenized, sanitized, and never exposed in responses, logs, or monitoring tools.  
- 👤 **Authentication + Authorization**: Two key questions: is the token from an authenticated user, and is that user authorized to perform the operation?  

---

## 🎁 Bonus checks

- 📑 **Contract testing**: Ensure schema, required fields, status codes, and data types match the implementation.  
- 🔄 **Idempotency**: If the same request is sent twice, does the system prevent duplicate operations?  
- 📌 **Versioning**: For APIs with `v1`, `v2`… make sure integrations remain compatible.  
- 📊 **Pagination**: Validate `offset` and `limit`. If missing and resource lists are huge, suggest adding pagination.  

---

✨ That’s my go-to roadmap for rest API validation and I hope you enjoy this content! 🚀
