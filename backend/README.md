# Backend Setup Instructions

Follow these steps to set up and run the backend:

1. **Install dependencies**
   ```bash
   npm i
   ```

2. **Generate Prisma client**
   ```bash
   npx prisma generate
   ```

3. **Push database schema**
   ```bash
   npx prisma db push
   ```

4. **Seed the admin user**
   ```bash
   npm run seed
   ```

5. **Start the server**
   ```bash
   npm start
   ```
