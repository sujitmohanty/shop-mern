> An eCommerce web application built with the MERN stack.

### Env Variables

Add a `.env` file to root and add the following

```
NODE_ENV = development
PORT = 8585
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
```

Change the JWT_SECRET and PAGINATION_LIMIT to what you want

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```

# Run frontend (:5173) & backend (:8585)
npm run dev

# Run backend only
npm run server
```
