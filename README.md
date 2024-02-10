# Build Image --target

\*\* production

docker build --target production -t aknote:production .

\*\* builder

docker build --target builder -t aknote:builder .

# Start and run multiple containers in background

docker-compose up -d

# Start and run multiple containers in background by specific --scale count and

docker-compose up --scale [service_name_here]=3 -d

# Start and run multiple containers in background by specific --scale count and re-build

docker-compose up --scale [service_name_here]=3 -d --build

# Run container with interactive

docker run -it -d --name aknote_c -p 3000:3000 [image_name_here]
# nextjs_load_balancing_with_docker_and_nginx
