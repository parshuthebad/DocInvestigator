# API Reference

### POST `/api/v1/verify`
Submits a document hash or identifier for status verification.

#### Request:
```json
{
  "asset_id": "urn:asset:9f86d081884c7d659a2feaa0c55ad015a3bf4f1b2b0b822cd15d6c15b0f00a08",
  "signature": "0xabc123..."
}
```

#### Response:
```json
{
  "status": "VERIFIED",
  "timestamp": 1727788800,
  "merkle_root": "0x1234...",
  "verified": true
}
```
