# **Hello AI**
A single page application (SPA) by [Luna Lam](https://github.com/lunaxlam)

## **Overview**
*Hello AI* utilizes [OpenAI](https://openai.com/api/)'s powerful GPT-3 AI model to process a plain text prompt and return a human-like text response. User queries are automatically saved in [db-json](https://www.npmjs.com/package/db-json).

## **Tech Stack**
Frontend: CSS 3, HTML5, JavaScript, ReactJS <br />
Backend: db-json, JSON Server<br />
APIs: [OpenAI](https://openai.com/api/)

*This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).*

## **Installation**
To run *Hello AI*:

Install [Node.js](https://nodejs.org/en/). 

Clone or fork the [repo](https://github.com/lunaxlam/luna-lam-fun-with-ai-app.git):
```
https://github.com/lunaxlam/luna-lam-fun-with-ai-app.git
```

In the project directory, save your OpenAI API key in a file called .env in the following format:
```
REACT_APP_OPENAI_SECRET=YOUR_OPENAI_API_KEY_HERE
```

Run the application:
```
npm start
```

In your browser, navigate to [http://localhost:3000](http://localhost:3000):
```
http://localhost:3000
```
You can now run *Hello AI*. Enjoy!
