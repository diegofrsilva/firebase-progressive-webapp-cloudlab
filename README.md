# Node 6+ and npm required

# Install dependencies
```sh
npm install -g bower
npm install -g firebase-tools
```

# check firebase CLI
```sh
firebase -V
```

# login with your credentials
```sh
firebase login
```

# init firebase and enable hosting and database
```sh
firebase init
```

# Install components
```sh
cd public
bower install -p platinum-sw polymerlabs/note-app polymerlabs/note-app-elements firebase/polymerfire
```

# Change the code below to use your credentials (index.html)
	<firebase-app
	    name="notes"
	    api-key="YOUR_API_KEI"
	    auth-domain="YOUR_DOMAIN_KEY"
	    database-url="YOUR_DATABASE_URL">
	</firebase-app>
	
# start 
```sh
firebase serve --debug
```
