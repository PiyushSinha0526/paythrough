- Clone the repo

```jsx
git clone URL
```

- npm install
- Run postgres either locally or on the cloud (neon.tech)


- Copy over all .env.example files to .env
- Update .env files everywhere with the right db url
- Go to `packages/db`
    - npx prisma migrate dev
    - npx prisma db seed
- Go to `apps/user-app` , npm intsall, run `npm run dev`
- Try logging in using phone - 100001 , password - alex (See `seed.ts`)