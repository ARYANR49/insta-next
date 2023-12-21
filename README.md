
<h1 align="center">
  InstaNext
</h1>

## 🛠 Installation & Set Up

Please refer to the blogs for the full installation process with explanation, but here's the full installation for the final codes

1. Install the dependencies

   ```bash
   yarn
   ```

2. Copy `.env.example` into a new `.env` file, and add an environment variable, `DATABASE_URL` which links to a PostgreSQL database

3. Initialize your database

   ```bash
   yarn migrate
   yarn seed # depends if you wish to prefill the database with values or not
   ```

4. Run the development server

   ```bash
   yarn dev
   ```

