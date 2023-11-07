# HOW TO DOCKERIZE A STATIC REACT APP
Below are the steps to dockerize this static react app

### Create the react app
```
npx create-react-app <name of app>
```
### Installing dependencies
```
npm install
```
### change into the src path
```
cd src
```
### create docker file on terminal on the path src
```
touch Dockerfile
```
### create a nodejs docker file 
```
check official node image dockerhub
```
### Build the image 
```
docker build -t <name of image> .
```
### Run the image
```
docker run -d -p 8000:8000 <name of image>
```
### Check if the app is running on the browser with localhost
```
http://localhost:8000
```





