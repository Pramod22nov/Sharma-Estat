Applications and Packages Needed to run the project:

Nodejs:
nodemon: A utility that monitors for changes in your Node.js application and automatically restarts the server.
dotenv: For loading environment variables from a .env file into process.env.

All necessary node Packages : Using "npm i" command

react: The core React library.
react-dom: Used for rendering React components in the DOM.
react-router-dom: For handling routing in React applications.
axios: For making HTTP requests from React applications.
redux and react-redux: For state management in React applications.
ES7 React/Redux/GraphQL/React-Native snippets - VS code extension.


Express:
body-parser: Required for parsing request bodies, which is often needed for handling form data or API payloads.
cors: Necessary if your application needs to handle Cross-Origin Resource Sharing (CORS) to allow requests from different origins.
helmet: Useful for securing your Express.js apps by setting various HTTP headers.


Tailwind CSS
		npm create vite@latest my-project -- --template react
		cd my-project
		npm install -D tailwindcss postcss autoprefixer
		npx tailwindcss init -p


tailwind.config.js file code:
		"/** @type {import('tailwindcss').Config} */
		export default {
  		content: [
   			 "./index.html",
    			"./src//*.{js,ts,jsx,tsx}",
  		],
  		theme: {
    		extend: {},
  		},
  		plugins: [],
		}"

index.css file code:

		"@tailwind base;
		@tailwind components;
		@tailwind utilities;"



MongoDb Setup Online.
mongoose: An object modeling tool for MongoDB, providing a schema-based solution to model application data.
MongoDb database link
