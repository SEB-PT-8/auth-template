# Steps to clone template

1. Perform the following commands in the command line
```bash
git clone https://github.com/SEB-PT-8/auth-template.git
cd auth-template
rm -rf .git
```

2. Create a .env file with the following 2 values of your database connection:
```
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.jbfjdbbdkkj.mongodb.net/libraryDB?retryWrites=true&w=majority&appName=Cluster0
SESSION_SECRET=lcnkdnkldncklndlkcdndkl
```


3. run:
```bash
npm i
```

4. Change the folder name from auth-template to your project name



