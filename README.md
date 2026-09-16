# Vision Store

Original dark/neon digital-services storefront starter.

## Run
1. Install Node.js 18.17+.
2. In this folder run: npm install
3. Copy `.env.example` to `.env.local` and add Supabase keys.
4. Run: npm run dev
5. Open http://localhost:3000

## Pages
- `/` landing page
- `/login` login UI
- `/register` registration UI
- `/dashboard` dashboard UI

The Supabase schema includes profiles, services, orders and manual payment requests. Real auth, database actions, admin approval and QR payment flow still need to be connected before accepting real users/payments.
