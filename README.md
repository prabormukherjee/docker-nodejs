# docker-nodejs

Here I build a nodejs app and deploy it using docker. Here is all details to use this repo.

### Instruction
+ open terminal or cmd and cd over the project folder
+ run `sudo dockerd`
+ run `docker-compose up`
+ visit `localhost:3000`

Hopefully your app has started now.

### Upload into docker cloud
+ create an acconut in case you don't have already at *[https://hub.docker.com](https://hub.docker.com)* => you'll have an `{username}`
+ create a repository => you'll have a `{reponame}`
+ open terminal and run these commands
+ `docker login`
+ `docker build -t {username}/{reponame}:{version} ./app`
+ `docker push {username}/{reponame}`

**Change the `{username}` and `{reponame}` to your username and repository name. For `{version}` use `1.0`**

Now visit to the site, hopefully it has uploaded.
