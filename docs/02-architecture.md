# Architecture & Verification Workflow

1. **Ingestion & Hashing**: Computes SHA-256 / Blake3 digests for incoming media or documents.
2. **Metadata Canonicalization**: Normalizes headers, timestamps, and origin signatures.
3. **Ledger / Tree Anchoring**: Batches verification records into Merkle trees for low-cost validation.
4. **Resolution Endpoint**: Exposes public lookup endpoints for any verifier.
