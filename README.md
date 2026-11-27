# 🌿 FernLearn
**Free Learning. Real Skills. Equal Opportunities.**

A Campus Fern product. Student-built discovery directory for free learning and practical courses. Account required. External providers determine access and credentials; no certificate or employment guarantee.

This frontend uses Supabase Auth and PostgreSQL RLS, deployed through GitHub Pages and Actions. Runtime configuration is generated from SUPABASE_URL and SUPABASE_PUBLISHABLE_KEY. A publishable key is safe for the browser subject to properly configured RLS; never commit any privileged secret. The owner setup kit is kept separately.

Account name, email, UID, first verified access timestamp and saved course IDs are stored in Supabase. Founder-only registration access. Contact campusfern.support@gmail.com for support or deletion requests. Supabase handles passwords. No payment is required to use FernLearn.
