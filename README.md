
This example is about showing social media login and login via email.

Currently both login by email and login via social media such as Google works.

Previously there was an issue with loginn via Google.

Switch to node v20.12.2

If you have nvm you can do:

```
nvm install v20.12.2
```

If you already have it and want to switch to it using nvm:

```
nvm use v20.12.2
```

Next run:

```
npm install
npm run dev
```

If you open the app in the browser you will see a Connect button.  If you click that it will open a dialog where you can choose to login via google.

Once logged in you will see the ethereum address which was generated or recreated for you.

