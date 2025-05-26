# 🗺️ Mapbox Basic Implementation with React

## A simple example implementing a Mapbox map in a React component, powered by Vite and Docker.

### 🚀 Usage

1. Clone the repository

```
git clone https://github.com/szidzse/mapbox-basic-implementation.git
cd mapbox-basic-implementation
```

2. Set up environment variables

Create a .env file in the root of the project, and add your Mapbox access token (🔑 You can get your access token by signing up at https://www.mapbox.com):

```
VITE_MAPBOX_ACCESS_TOKEN=<YOUR_MAPBOX_ACCESS_TOKEN>
```

3. Build the Docker image

```
docker build -t my-map-app .
```

4. Run the Docker container

```
docker run -p 5173:5173 my-map-app
```

5. Open the app

```
🌐 Go to http://localhost:5173 in your browser.
```

6. 🖼️ Preview

Here’s what the app looks like in action:

