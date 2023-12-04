# Text-to-image
An text to image converting tool in which user can enter text from prompt and the tool will generate an image using dall e model to work. (which is a trained neural network to genetare detailed imgages from text). You can find more out about dall e model [here](https://openai.com/research/dall-e)
# Instructions To run 
  1. Clone the repo.
  2. Install the dependencies.
       ####  In Client 
       ```
          Npm create vite@latest ./ 
          npm install -D tailwindcss
          npx tailwindcss init
       ```  
       #### In Server 
       ```
           npm install cloudinary
           npm install express
           npm install mongoose
           npm install nodemon
           npm install openai
       ```
           Then in the environment(.env) file paste your mongodb database api key and openai api key and cloudinary api keys.
       
3. Finally, npm run dev to start the client/server app.
        
# Video Tutorial


# Technologies
 - Dalle-E-Model
 - MERN Stack
 - Cloudinary
 - Vite(Fornt End tool)
