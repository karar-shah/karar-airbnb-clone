## Next-auth:

1. pnpm add next-auth
2. Add API route
   1. `pages/api/auth/[...nextauth].js`
3. [NEXTAUTH_SECRET & NEXTAUTH_URL](https://next-auth.js.org/configuration/options)
   1. `openssl rand -base64 32`
4. [Provider OAuth](https://next-auth.js.org/configuration/providers/oauth)
   1. Google
   2. etc ...
