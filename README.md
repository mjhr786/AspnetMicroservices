# AspnetMicroservices
<body>
    <h2>AspnetMicroservices</h2>
    <p>Follow these steps to get your development environment set up: (Before Run Start the Docker Desktop)</p>
    <ol>
        <li>Clone the repository</li>
        <li>Once Docker for Windows is installed, go to the Settings > Advanced option, from the Docker icon in the
            system tray, to configure the minimum amount of memory and CPU like so:
            <ul>
                <li>Memory: 4 GB</li>
                <li>CPU: 2</li>
            </ul>
        </li>
        <li>At the root directory which include docker-compose.yml files, run below command:
            <br>
            <code>docker-compose -f docker-compose.yml -f docker-compose.override.yml up -d</code>
        </li>
        <li>Wait for docker compose all microservices. That's it! (some microservices need extra time to work so please
            wait if not worked in first shut)</li>
        <li>You can launch microservices as below urls:</li>
    </ol>
    <ul>
        <li>Catalog API -> http://localhost:8000/swagger/index.html</li>
        <li>Basket API -> http://localhost:8001/swagger/index.html</li>
        <li>Discount API -> http://localhost:8002/swagger/index.html</li>
        <li>Portainer -> http://localhost:9000/ -- admin/admin1234</li>
        <li>pgAdmin PostgreSQL -> http://localhost:5050/ -- admin@aspnetrun.com/admin1234</li>
    </ul>
</body>
</html>
