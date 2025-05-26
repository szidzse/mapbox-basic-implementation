#  A simple example implementing a MapBox map in a React component. 

### Usage

1. Clone the repository:

```
git clone https://github.com/szidzse/mapbox-basic-implementation.git
```

2. Create a '.env' file in the project folder, then create an environment variable called 'VITE_MAPBOX_ACCESS_TOKEN':

```
VITE_MAPBOX_ACCESS_TOKEN=
```

3. Go to https://www.mapbox.com/ and create an account. Get your Access Token, then set the value of 'VITE_MAPBOX_ACCESS_TOKEN' to:

It should look like this: 

```
VITE_MAPBOX_ACCESS_TOKEN=<YOUR_MAPBOX_ACCESS_TOKEN>
```

4. Build an image based on the Dockerfile:

```
docker build -t my-map-app .
```

5. Run the container: 

```
docker run -p 5173:5173 vite-app
```

6. Open your browser on http://localhost:5173: