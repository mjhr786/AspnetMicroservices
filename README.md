# AspnetMicroservices
AspnetMicroservices

Follow these steps to get your development environment set up: (Before Run Start the Docker Desktop)

Clone the repository
Once Docker for Windows is installed, go to the Settings > Advanced option, from the Docker icon in the system tray, to configure the minimum amount of memory and CPU like so:
Memory: 4 GB
CPU: 2
At the root directory which include docker-compose.yml files, run below command:
docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d
Wait for docker compose all microservices. That’s it! (some microservices need extra time to work so please wait if not worked in first shut)

You can launch microservices as below urls:

Catalog API -> http://localhost:8000/swagger/index.html

Basket API -> http://localhost:8001/swagger/index.html

Discount API -> http://localhost:8002/swagger/index.html

Portainer -> http://localhost:9000/ -- admin/admin1234

pgAdmin PostgreSQL -> http://localhost:5050/ -- admin@aspnetrun.com/admin1234
