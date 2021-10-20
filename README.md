DJ Events (Strapi Backend)

> Strapi backend for the DJ Events website.

The Next.js frontend can be found [here](https://github.com/KristijanStosic/dj-events-frontend)

# Usage

### Using Cloudinary

Create a .env file and add your Cloudinary and MongoDB info.
After creating project on MongoDB Atlas, fill in the values in .env file.
After that run npm install.

```
CLOUDINARY_NAME = "xxxx"
CLOUDINARY_KEY = "xxxx"
CLOUDINARY_SECRET = "xxxx"

DATABASE_HOST = 'xxxx'
DATABASE_SRV = 'xxxx'
DATABASE_PORT = 'xxxx'
DATABASE_NAME = 'xxxx'
DATABASE_USERNAME = 'xxxx'
DATABASE_PASSWORD = 'xxxx'
```



### Run the Server

```bash
npm run develop
# or
yarn develop
```

Open [http://localhost:1337/admin](http://localhost:1337/admin) to access the CMS

