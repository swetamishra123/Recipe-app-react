
# Recipe App using React.js

This is a simple food recipe app built using React.js. It fetches food recipes from the Edamam API and displays them in a user-friendly interface.

## Pre-requisite

- React hooks
- React components
- JavaScript ES6
- API
- CSS

## Approach

The app utilizes React hooks such as `useEffect` and `useState` to fetch data from the Edamam API and manage the state of the application. The basic approach involves:

1. **Fetching Food Recipe API Key**: To get started, you need to sign up on Edamam and obtain your API credentials (Application ID and Application Key) from the Developer section.

2. **Creating React App**: Use `create-react-app` to bootstrap your project and set up the necessary environment.

3. **Installing Required Packages**: Install any required packages, although the core dependencies will be handled by `create-react-app`.

4. **Implementing Components**: Build components to display food recipes and manage API requests. Use React hooks to handle state and lifecycle.

## Getting Food Recipe API Key

1. Sign up on [Edamam](https://developer.edamam.com/).
2. Go to the APIs section in the navbar.
3. Click "Start Now" in the Developer section.
4. Navigate to the Dashboard > Application > Recipe Search API.
5. Copy your Application ID and Application Key provided by Edamam.

## Project Setup

### Step 1: Create React App

```bash
npx create-react-app foldername
```

### Step 2: Move to Project Folder

```bash
cd foldername
```

### Step 3: Update API Credentials

Inside `src/App.js`, replace `<YOUR_APP_ID>` and `<YOUR_APP_KEY>` with your Edamam API credentials.

## Project Structure

```
recipe-app/
│
├── node_modules/
├── public/
├── src/
│   ├── components/
│   ├── App.js
│   ├── index.js
│   └── ...
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/recipe-app.git
```

2. Install dependencies:

```bash
npm install
```

3. Run the app:

```bash
npm start
```

## Contributing

Contributions are welcome! Fork the repository, create a branch, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

