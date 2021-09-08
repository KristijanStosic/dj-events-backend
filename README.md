DJ Events (Strapi Backend)

> Strapi backend for the DJ Events website.

The Next.js frontend can be found [here](https://github.com/KristijanStosic/dj-events-frontend)

# Usage

### Using Cloudinary

Create a .env file and add your Cloudinary info for images

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

Database used is MongoDB so you have to create project on MongoDB Atlas.
Replace in config/database.js values with the one you put in .env


### Run the Server

```bash
npm run develop
# or
yarn develop
```

Open [http://localhost:1337/admin](http://localhost:1337/admin) to access the CMS

