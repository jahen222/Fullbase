## Fullbase README

This repository contains multiple initial projects organized within a TurboRepo (MonoRepo) structure. The projects can be installed using Yarn and built using `yarn build`. The projects are located in the `apps` directory and include:

- `app` (React Native)
- `app-business` (React Native)
- `backend` (Strapi)
- `frontend` (Next.js)

### Requirements

- **Node.js**: v18
- **Java**: v17

### Installation

1. Clone the repository:

```bash
git clone https://github.com/jahen222/fullbase.git
```

2. Navigate to the repository directory:

```bash
cd fullbase
```

3. Install dependencies using Yarn:

```bash
yarn install
```

### Database Configuration

The database connection details are located in `apps/backend/.env`. You need to create this file using the following template:

```
HOST=0.0.0.0
PORT=1337
APP_KEYS=
API_TOKEN_SALT=
ADMIN_JWT_SECRET=
TRANSFER_TOKEN_SALT=
JWT_SECRET=
DATABASE_CLIENT=
DATABASE_URL=
DATABASE_HOST=
DATABASE_PORT=
DATABASE_NAME=
DATABASE_USERNAME=
DATABASE_PASSWORD=
DATABASE_SSL=
```

Fill in the appropriate values for your database configuration. The supported databases are MySQL, Postgres, or SQLite. If you need access to a cloud database, please contact the administrator at henryjaimes.peli@gmail.com.

### Usage

You can run the front and the back together using `yarn dev`, or individually using the following commands:

- **Backend**:
  - `yarn backend:build`: Build the backend.
  - `yarn backend:dev`: Run the backend in development mode.
  - `yarn backend:start`: Start the backend server.

- **Frontend**:
  - `yarn frontend:build`: Build the frontend.
  - `yarn frontend:dev`: Run the frontend in development mode.
  - `yarn frontend:start`: Start the frontend server.

- **App**:
  - `yarn app:build`: Build the app.
  - `yarn app:android`: Run the app for Android.
  - `yarn app:web`: Run the app for web.
  - `yarn app:start`: Start the app.

- **App Business**:
  - `yarn app-business:build`: Build the app business.
  - `yarn app-business:android`: Run the app business for Android.
  - `yarn app-business:web`: Run the app business for web.
  - `yarn app-business:start`: Start the app business.

### License

This project is licensed under the [MIT License](LICENSE).

### Contact
For any questions or issues, please contact [Henry Jaimes](mailto:henryjaimes.peli@gmail.com).