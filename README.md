# Markdown Blog
to use this just add a .env file and write DB_CONNECT={get this connection link from your mongo db cluster}
This [markdown](https://www.computerhope.com/jargon/m/markdown.htm) blog is built with Node.js Express and MongoDB Atlas, and runs in a Docker container. Users can get blog posts from the MongoDB cluster, and post new articles, update and delete them.

## Main Page
<img width="1440" alt="Screen Shot 2021-02-16 at 4 50 34 PM" src="https://user-images.githubusercontent.com/41644259/108127931-ff35c600-7079-11eb-8099-0d868c852ffd.png">


## Blog Post
<img width="1440" alt="Screen Shot 2021-02-16 at 4 55 43 PM" src="https://user-images.githubusercontent.com/41644259/108128504-d7932d80-707a-11eb-88e2-0b71e10ca315.png">


## Deployment
```
git clone git@github.com:hannahkim7605/markdown-blog.git
cd markdown-blog
docker build -t markdown-blog .
docker run -p 5000:8080 -d markdown-blog
```
The blog is available at http:/localhost:5000.


Reference:
- How To Build a Markdown Blog Using Node.js, Express, And MongoDB by Web Dev Simplified (https://www.youtube.com/watch?v=1NrHkjlWVhM)
- https://www.npmjs.com/package/nodemon
- https://zellwk.com/blog/crud-express-mongodb/
- https://ejs.co/#docs
- https://stackoverflow.com/questions/23259168/what-are-express-json-and-express-urlencoded/51844327
- https://www.npmjs.com/package/dotenv
- https://github.com/jsdom/jsdom
- https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
- https://docs.docker.com/engine/reference/commandline/run/
