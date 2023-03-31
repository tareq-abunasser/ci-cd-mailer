# CI/CD send email with apk exists in google drive folder

## add .env file
```
PORT=3000
MAIL_HOST=smtp.gmail.com
MAIL_PORT=465
MAIL_USER=YOUR EMAIL
MAIL_PASS=GENERATED APP PASSWORD FROM GOOGLE’S MY ACCOUNT SECTION.
```

## Build Command
```npm install && npm run build```

## install packages
```npm i dotenv express ejs nodemailer```

## Start Command
```node index.js```
