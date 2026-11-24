# CHLP tool: staging copy

This repository holds a staging copy of the CHLP tool. It tests accounts, test logins and data validation before any real entry is stored. It holds invented data only.

- Every entry, organization and contact in it is invented, and the database refuses anything else.
- Only the test logins that the Climate Health Ledger Project created have access.
- It is not the CHLP tool's public page. The public page is at https://richmond-chlp.github.io/chlp-tool-alpha/ and stores nothing.

The page carries supabase-js 2.118.0 (MIT License) inside the file. The key in the page is Supabase's publishable key, which is meant for browsers; the database's row-level security decides what each login can read or write.

Contact: richmond@climatehealthledger.org.
