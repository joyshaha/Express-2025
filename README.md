# Express Backend — Quick Start

Small Express + MongoDB backend used in the project.

## Prerequisites
- Node.js (v16+ recommended)
- A MongoDB connection string in [.env](.env) (MONGODB_URI)
- JWT secret in [.env](.env) (JWT_SECRET)

## Key files
- Server entry: [server.js](server.js)
- DB connection: [`connectDB`](config/db.js) — [config/db.js](config/db.js)
- Auth middleware: [`auth`](middleware/auth.js) — [middleware/auth.js](middleware/auth.js)
- Routes:
  - [routes/auth.js](routes/auth.js)
  - [routes/users.js](routes/users.js)
  - [routes/post.js](routes/post.js)
  - [routes/videos.js](routes/videos.js)
  - [routes/podcast.js](routes/podcast.js)
  - [routes/transactions.js](routes/transactions.js)
  - [routes/home.js](routes/home.js)
- Models:
  - [models/User.js](models/User.js)
  - [models/Post.js](models/Post.js)
  - [models/Video.js](models/Video.js)
  - [models/Podcast.js](models/Podcast.js)
  - [models/Transaction.js](models/Transaction.js)
- Package config: [package.json](package.json)

## Install
```sh
npm install
```