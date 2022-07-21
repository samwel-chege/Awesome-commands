# Awesome-commands
Sometimes it takes long to search for that one command to debug something or even install a dependency.. I will randomly write them down here
- Actually I am going to also add some important links to resources

### Set up tailwindcss in react app

```bash
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p 
```
The init command generates tailwind.config.js and postcss.config.js files

### psql : error: could not connect to server: No such file or directory 
- use the command below to start postgresql

```bash
sudo service postgresql start
```
### Adding tailwindcss to our django app
- check out [django + tailwind](https://django-tailwind.readthedocs.io/en/latest/installation.html)

 ## Geting a JWT_SECRET token
- Go to your terminal and run the following command
```bash
openssl rand -base64 32
```
- or you can alternatively use this link -  https://generate-secret.vercel.app/32
