# Backend - Item Manager Lab Test

## Setup
1. Open a terminal inside the backend folder.
2. Run:
   ```bash
   npm install
   ```
3. Create a `.env` file using `.env.example` as a guide.
4. Add your MongoDB Atlas connection string to `MONGO_URI`.
5. Start the server:
   ```bash
   npm run dev
   ```

## API Endpoints
- `GET /api/items`
- `GET /api/items/:id`
- `POST /api/items`
- `PUT /api/items/:id`
- `DELETE /api/items/:id`

## Item Fields
- `name`
- `category`
- `price`
- `weightSize`
- `description`
- `imageUrl`
