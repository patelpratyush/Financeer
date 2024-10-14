# Financeer

## Tech Stack

### Frontend

- React.js / Vite
- TypeScript
- Redux-toolkit
- MUI
- Recharts

### Backend

- Node.js
- Express.js
- Mongodb

## Demo

<https://financeer-dashboard.vercel.app/>

## Cloning the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/marcinsuski/finance-dashboard.git
```

### Running the Server

1. Navigate to the `server` directory:

```bash
cd server
```

2. Install the required dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

### Running the Client

1. Navigate to the `server` directory:

```bash
cd client
```

2. Install the required dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

## Project Structure

- `server/`: Contains the backend server code.
- `client/`: Contains the frontend client code.

## Environment Variables

Before running the server, you need to set up the required environment variables.

Create a `.env` file in the `server` directory with the following contents:

```bash
MONGODB_URL="mongodb+srv://<username>:<password>@7km6ofs.mongodb.net/?retryWrites=true&w=majority"
PORT=<port number, e.g. 8080>
```

- Replace `<username>` and `<password>` with your MongoDB Atlas credentials.
- Replace `<port number>` with desired port for your server.

Once the .env file is set up, you can proceed to run the server using the steps mentioned above.
