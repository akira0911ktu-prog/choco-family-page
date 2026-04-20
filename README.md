# Family-only page

This repository hosts a single static HTML page for private family sharing.

The content is **encrypted at rest** (AES-GCM with PBKDF2 key derivation,
200,000 iterations). Only visitors who know the password, shared privately
with family members, can read the content.
