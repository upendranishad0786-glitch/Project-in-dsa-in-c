EduDictionary — Supabase-connected starter

Already filled in:
- Supabase Project URL
- Supabase Publishable Key (public key)

Important setup still required:
1. Open Supabase Dashboard and select EduDictionary.
2. Go to SQL Editor > New query.
3. Paste all contents of schema.sql and press Run.
4. Go to Authentication > URL Configuration. Set Site URL to your eventual published website URL. While testing locally this can be left at its default.
5. Open index.html in a browser to test. Register may require email confirmation depending on Supabase Auth settings.

Security:
- The sb_publishable_ key is designed for use in public browser code.
- NEVER put a Secret key or service_role key in index.html.
- Use Row Level Security (RLS) and policies for any data tables.

This is a starter website, not yet publicly hosted. The word search uses a public dictionary API.
