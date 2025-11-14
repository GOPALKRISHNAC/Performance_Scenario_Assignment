**Purpose:** 
Evaluates performance, stability, and scalability of HTTP-based APIs using Apache JMeter.

🐳 Containerized Setup: Uses Docker Compose to orchestrate all dependencies for consistent, reproducible test execution.

🌐 Test Target: Utilizes the open-source HTTPBin service to simulate various HTTP request/response behaviors under load.

📊 Performance Metrics: Measures latency, throughput, and error rates while validating response correctness.

🔒 Isolation: Runs HTTPBin server, JMeter client, and reporting tools in Docker containers—no local installation needed.

🔁 Platform Independence: Ensures minimal environmental drift and easy CI/CD integration (e.g., Jenkins, GitHub Actions).

📝 Test Plans: Defined in .jmx format and parameterized for different environments (local, staging, cloud).

📁 Results Format: Captured in JTL, CSV, and HTML dashboards for insights into trends and metrics.

📈 Test Types:
Load Test
Stress Test
Spike Test
Endurance Test

🧩 Modular Design: 
Supports adding new scripts, endpoints, and configurations.

💾 Persistent Storage: 
Stores results, logs, and dashboards using Docker volumes.

📡 Monitoring Integration: 
Compatible with tools like Prometheus and Grafana for real-time visibility.

