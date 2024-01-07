For Install project
```
npm install 
```
Add File
```
.env
```
Fill this in .env File
```
DATABASE_URL = "postgresql://username:password@localhost:5432/pgs?schema=public"
JWT_SECRET = 
```

For update database and add all models 
```
npx prisma migrate dev
```

For run project 
```
npm run dev
```

