# FurnitureForge

FurnitureForge is a custom furniture design and manufacturing platform that allows users to create bespoke furniture pieces through an interactive and intuitive web application. The platform provides real-time 3D visualization and customization options, ensuring that users can design their ideal furniture with precision.

## Tech Stack
### Front-End
- React/Next.js: For building an interactive and responsive user interface.
- Konva.js & Three.js: For 3D rendering, allowing users to visualize furniture designs in - real-time.
- HTML5/CSS3: For structuring and styling the web pages.

### Back-End
- Laravel: For handling complex logic and integration with design algorithms.
- Next.js: For server-side rendering and real-time updates.
- GraphQL: For efficient data querying and manipulation.

### Database
PostgreSQL for storing user data, orders, and product configurations.

### 3D Configuration and Rendering
Three.js: For 3D model rendering and manipulation.

### Hosting and Deployment
- AWS: For scalable cloud hosting, storage, and deployment.
- Docker & Kubernetes: For containerization and orchestration of services.

### CI/CD
GitHub Actions: For continuous integration and deployment pipelines.


# Installation
## 1. Clone the repository:
```
git clone https://github.com/yourusername/furnitureforge.git
cd furnitureforge
```

## 2. Set up the Front-End:
- Navigate to the frontend directory and install dependencies:
  ```
  cd frontend
  npm install
  ```
- Run the development server:
  ```
  npm run dev
  ```
## 3. Set up the Back-End:
  ```
  cd backend
  composer install
  ```
- Set up environment variables in the .env file.
- Run the application:
  ```
  php artisan serve
  ```
## 4. Set up Docker:
- Ensure Docker is installed and running.
- Build and start the containers:
  ```
  docker-compose up --build
  ```

# Usage
Access the front-end through the development server (e.g., http://localhost:3000).
