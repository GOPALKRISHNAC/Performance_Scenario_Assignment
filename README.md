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

Objective: 
Enables automated, repeatable, and scalable performance testing of APIs.

🔍 Validation Scope: Focuses on end-to-end checks for responsiveness, reliability, and system behavior under load.

👥 User Simulation: Emulates concurrent users, varied payloads, and diverse HTTP methods (GET, POST, PUT, DELETE).

📈 Performance Insights: Identifies latency hotspots, bottlenecks, and throughput limits early in development.

🚀 DevOps Alignment: Follows automation-first principles for continuous performance testing.

🛠️ Simple Deployment: Uses docker-compose up for setup and docker-compose down for teardown.

📊 Reporting: Generates HTML reports and graphical dashboards for easy result interpretation.

🧠 Data-Driven Decisions: Supports tuning, optimization, and deployment readiness validation.

🗂️ Historical Benchmarking: Builds a repository of test results to detect regressions and track improvements.
