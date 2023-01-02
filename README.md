H.care is a healthcare dashboard that caters to your healthcare needs https://healthcare-theta.vercel.app/

What does it provide?
A dashboard that displays your water consumption, steps, sleep records etc in a graphical way and display health news.
A dashboard that provides nutrient information and shows how much carbs, calories, protien, sugar, etc. you have consumed upon query.
A dashboard that displays your sleep data in graphical way and gives tips on sleeping well.
A dashboard that provides tips to improve your mental health according to your mood.
A dashboard that tracks your activity, displays calories burnt upon query and provides video links for various exercises.
It has a chatbot for your health and fitness concerns
Introduction
H.care is powered by NextJs and Firebase .
It uses TailwindCSS for styling
It uses Nutritionix API to display nutrition information and exercise information. What makes this api great is it takes natural language like 'I ate 2 eggs for breakfast today' and returns acurate nutritional information. Same goes for exercise information.
It uses nivo.rocks for graphical charts. A great collection of components built on top of React and D3JS .
It uses NextAuth for authentication.
Firebase provides database for storing data and provides functions to fetch data in realtime Docs .
It uses React-Icons for icons.
It uses TheNewsApi for news fetching . It is great for getting filtered news.
Getting Started
This project requires you to have a GOOGLE_CLIENT_ID and GOOGLE_CLIENT_SECRET which you will receive when you will create a new Firebase App here.
A whole step by step process is here.
It will also require NEXT_PUBLIC_NEWS_API_TOKEN which is a api key that you can get here

Running on local machine
Fork the repository and clone it in a local directory.
Open the terminal in the directory and run the following command:
npm i
Upon completion create a 'env.local' file in the same directory and write the following in it and save:
GOOGLE_CLIENT_ID=*YOUR ID*
GOOGLE_CLIENT_SECRET=*YOUR SECRET*
NEXT_PUBLIC_NEWS_API_TOKEN=*YOUR NEWS API TOKEN*
Run npm run dev in the terminal, this will start the local server.
Voila! You are ready. 😂
The app should be running at http://localhost:3000 by default.
