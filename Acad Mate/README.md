# AcadMate: Your Academic Sidekick

This contains everything you need to run your app locally and deploy it to the web.

## Run Locally

**Prerequisites:** Node.js

1.  Create a file named `.env.local` in the root of the project.
2.  Add your Gemini API key to the file like this:
    `GEMINI_API_KEY=your_api_key_here`
3.  Install dependencies:
    `npm install`
4.  Run the app:
    `npm run dev`

---

## Progressive Web App (PWA)

This application is a Progressive Web App, which means it can be "installed" on most modern desktop and mobile browsers.

- **Offline Functionality:** The app will load and be usable even without an internet connection.
- **Native Experience:** When installed, the app runs in its own window, has an app icon on your home screen or desktop, and feels like a native application.
- **How to Install:** In your browser's address bar (like Chrome or Edge), look for an "Install" icon (usually looks like a computer with a down arrow). Click it to add AcadMate to your device.

---

## Deploying to Vercel

You can deploy this application to Vercel for free with one click.

1.  **Push to GitHub:** Create a new repository on GitHub and push the project code to it.
2.  **Import to Vercel:**
    - Sign up or log in to [Vercel](https://vercel.com).
    - From your dashboard, click "Add New..." -> "Project".
    - Select your GitHub repository.
    - Vercel will automatically detect that you're using Vite and configure the build settings.
3.  **Add Environment Variable:**
    - In the Vercel project settings, navigate to the "Environment Variables" section.
    - Add a new variable with the key `GEMINI_API_KEY`.
    - Paste your Gemini API Key into the value field.
    - **Important:** Ensure the variable is available for all environments (Production, Preview, Development).
4.  **Deploy:** Click the "Deploy" button. Vercel will build and host your application.
