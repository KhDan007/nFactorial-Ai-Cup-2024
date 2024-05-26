# nFactorial-Ai-Cup-2024
Fork this repository and build nFactorial Ai Cup 2024 projects 

## < Khamzin Daniyal >

## < MealVision AI >

## < Your App's description, technical considerations, etc. >
My app allows users to take a picture of what they have eaten, or what they are planning to eat and get a very detailed description of the nutrients that this meal consists of. Each entry is saved in history and users can see each of them whenever they want. This leads to a better UI and UX and more user retention.

The application uses CV and NLP in order to transform the uploaded image into the nutriental analysis. This happens in few steps:
1) User uploads their image of food.
2) The image is sent to backend, where I use the ClarifAI API, in order to get a list of food keywords present in the image with their corresponding cofidenvce levels.
3) Then using llama-8b-8192 with Groq API I process the obtained keywords with confidence levels and get a response of the recipe and ingredients of a meal, in a form of JSON.
4) Then I send this JSON to the third API - Edamam API. I use this API for its nutritional analysis, it can analyze the nutrients of a meal based on its recipe. I send the recipe and get a large nutritional data in a form of JSON
5) Then I parse this JSON and show the user the most important part (not ready yet)

## Typeform to submit:
https://docs.google.com/forms/d/e/1FAIpQLSfjnACTWf5xYKInMllmhy5Bchc-DnOXw6vEXsHmXI4XFPwZXw/viewform?usp=sf_link

## DEADLINE: 26/05/2024 10:00
