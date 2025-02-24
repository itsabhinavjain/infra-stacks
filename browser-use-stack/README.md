- The actual library - https://github.com/browser-use/browser-use
	- Hosted version is also available as an API 
	- Ther is a library that you can use

- The application - https://github.com/browser-use/web-ui
	- Docker 
	- Local installation etc 
	

What I would love :- 
1) Ability to use a current browser so that it s
2) Already there - Save the state between sessions 
3) Ability to take control and give back control
4) Ability to cancel in case it is doing something weird 


## Docker
````
git clone https://github.com/browser-use/web-ui.git
cd web-ui

docker compose up -d --build
OR 
CHROME_PERSISTENT_SESSION=true docker compose up -d --build
```