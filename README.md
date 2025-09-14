# FliMY
This project is a full stack movie review platform called FliMY. The frontend is a modern web application built with React and TypeScript, styled using Tailwind CSS, and bundled with Vite. The backend is powered by Supabase, which provides a complete solution including a PostgreSQL database, user authentication, and instant APIs.

Here is the text reformatted for easier reading:

FliMY - Movie Review Platform Project Guide  
Project Overview  
This project is a React application powered by Vite. It uses TypeScript for development, Tailwind CSS for styling, and Supabase for database and authentication services.

Setup and Installation Instructions  
1. Prerequisites: Make sure you have Node.js, which includes npm, installed on your system.  
2. Clone the Repository: Run `git clone <your-repository-url>` and navigate to `vite-react-typescript-starter`.  
3. Install Dependencies: Run `npm install` in the project root to install required packages.  
4. Set Up Environment Variables: Create a `.env` file by copying the example file and adding your Supabase credentials.  
5. Run the Development Server: Start the local development server with `npm run dev`. The application should run on `http://localhost:5173`.

Database Setup Instructions  
1. Create a Supabase Project: Visit supabase.com and create a new project.  
2. Design Your Database Schema: Create tables for movies, reviews, and users. Supabase automatically handles user authentication.  
3. Get Project Credentials: Locate your Project URL and API Keys in the Supabase dashboard.

Environment Variables Required  
1. Create a `.env` file in the project root and add your Supabase credentials:

```
VITE_SUPABASE_URL=https://your-project-url.supabase.co  
VITE_SUPABASE_ANON_KEY=your-public-anon-key-here  
```

API Documentation  
The project uses the `@supabase/supabase-js` client library to interact with the Supabase API. Refer to the official Supabase documentation for detailed information on available endpoints and usage.

Additional Notes & Design Decisions  
- Core Technologies: Vite, React, TypeScript, Supabase, Tailwind CSS, React Router DOM, and ESLint.  
- Technical Considerations:  
    - Ensure responsive design and proper error handling.  
    - Use environment variables for sensitive keys and implement thorough input validation.  
    - Consider adding rate limiting for API endpoints.
