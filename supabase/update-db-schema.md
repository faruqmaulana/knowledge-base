## update database schema in supabase from local to remote database flow (turborepo, nextjs, supabase, prisma)

1. update prisma shcema
2. generate prisma model types
3. push prisma shcema
4. create migration with supabase cli
5. push migration db to remote database

```bash
npx prisma generate
npx prisma db push
pnpm --filter web supabase db diff -f <migration-name>
pnpm --filter web supabase db push
```
