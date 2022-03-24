## OSCARS.DEV
Live code of my personal portfolio website.  
This site has been made with NextJs and has been styled using Tailwind CSS.  
All content is dynamically loaded from Supabase.  

### [LIVE DEMO](https://oscars.dev/)  
  
## Development
Running the development server:
```bash
npm run dev
# or
yarn dev
```
  
## Docker
Deploying site with docker [based on NextJs example](https://github.com/vercel/next.js/tree/canary/examples/with-docker):

Install Docker on your machine.
Build your container: `docker build -t oscarsdev .`
Run your container: `docker run --name oscarsdev -p 3000:3000 oscarsdev`
