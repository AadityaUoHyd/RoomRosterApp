# RoomRoster App
Meeting room booking application built with Next.js, Appwrite, and Tailwind CSS.

## Usage

### Install Dependencies
```bash
npm install
```

### Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000] (http://localhost:3000) with your browser in dev mode.

### Appwrite Setup & Environment Variables

you will need to create a new project and database in Appwrite.

Log into your https://cloud.appwrite.io/console (Appwrite console) and setup your project. Either use `.env.local` or provide those details to environment variables at production server with adding your own values for the Appwrite API key, project ID and database ID environment variables.

### For example your env.local should look alike =>
- APPWRITE_API_KEY=<Your_APPWRITE_API_KEY>
- NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
- NEXT_PUBLIC_APPWRITE_PROJECT=room-roster
- NEXT_PUBLIC_APPWRITE_DATABASE=room-roster
- NEXT_PUBLIC_APPWRITE_COLLECTION_ROOMS=rooms
- NEXT_PUBLIC_APPWRITE_COLLECTION_BOOKINGS=bookings
- NEXT_PUBLIC_APPWRITE_ROOMS_STORAGE_BUCKET=rooms
- NEXT_PUBLIC_URL=http://localhost:3000


## Find this App at production server vercel, post deployment:
https://room-roster-app.vercel.app/
