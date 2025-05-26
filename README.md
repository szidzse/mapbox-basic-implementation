# 🗺️ Mapbox Basic Implementation with React, Vite and Docker

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white&style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)

## A simple example implementing a Mapbox map in a React component, powered by Vite and Docker.

---

### 🚀 Usage

#### 1. Clone the repository

```
git clone https://github.com/szidzse/mapbox-basic-implementation.git
cd mapbox-basic-implementation
```

#### 2. Set up environment variables

- Create a .env file in the root of the project, and add your Mapbox access token (🔑 You can get your access token by signing up at https://www.mapbox.com):

```
VITE_MAPBOX_ACCESS_TOKEN=<YOUR_MAPBOX_ACCESS_TOKEN>
```

#### 3. Build the Docker image

```
docker build -t my-map-app .
```

#### 4. Run the Docker container

```
docker run -p 5173:5173 my-map-app
```

#### 5. Open the app

```
🌐 Go to http://localhost:5173 in your browser.
```

#### 6. 🖼️ Preview

- Here’s what the app looks like in action:

![Screenshot From 2025-05-26 20-44-16](https://github.com/user-attachments/assets/c1a3f4f1-ddc6-4d26-8f59-3a8bd7b574d6)

![Screenshot From 2025-05-26 20-44-03](https://github.com/user-attachments/assets/285759cf-69f1-4593-a166-65757a80ed86)

