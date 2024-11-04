# RoomRoster App

Meeting room booking application built with Next.js, Appwrite, and Tailwind CSS.

## Usage

#### Install Dependencies

```bash
npm install
```

#### Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser.

#### Appwrite Setup & Environment Variables

you will need to create a new project and database in Appwrite.

Log into your https://cloud.appwrite.io/console (Appwrite console) and setup your project. Either use `.env.local` or provide those details to environment variables at production server with adding your own values for the Appwrite API key, project ID and database ID environment variables.

#### For example your env.local should look alike)

- APPWRITE_API_KEY=standard_c16d92b16a80bb9a98f3c5e9982c743d40b698710d28602341eb9af32b137989818bc6b744b4a9a25b6426535efa02f18f3dfee0403353968b8453b4e9b63307e39c15b5ea334f0def9c848583436a81cfdb497dc2d8b4d1cc22b8d4a1d- ebf058cc158339611db570a0fab090ecaa6348c1a6cb0052adea5c0b0d40eb15db001
- NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
- NEXT_PUBLIC_APPWRITE_PROJECT=room-roster
- NEXT_PUBLIC_APPWRITE_DATABASE=room-roster
- NEXT_PUBLIC_APPWRITE_COLLECTION_ROOMS=rooms
- NEXT_PUBLIC_APPWRITE_COLLECTION_BOOKINGS=bookings
- NEXT_PUBLIC_APPWRITE_ROOMS_STORAGE_BUCKET=rooms
- NEXT_PUBLIC_URL=http://localhost:3000
