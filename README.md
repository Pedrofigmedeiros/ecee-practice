# Elastic Certified Engineer Practice (ECEE)

Hands-on labs, realistic mock exams, datasets, and practice environments for the Elastic Certified Engineer (ECEE) certification.

## Overview

This repository contains practical Elasticsearch exercises designed to help developers improve their skills and prepare for the Elastic Certified Engineer exam.

The project includes:

- Mock exams
- Practice datasets
- Docker environment
- Elasticsearch setup files
- Query DSL exercises
- Aggregations
- Runtime Fields
- Ingest Pipelines
- Index Templates
- Snapshot Lifecycle Management
- Cross-Cluster Replication

## Repository Structure

```text
ecee-practice/
├── datasets/
├── docs/
├── mocks/
├── setup/
├── solutions/
├── scripts/
└── docker-compose.yml
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/<your-username>/ecee-practice.git
cd ecee-practice
```

Start Elasticsearch and Kibana:

```bash
docker compose up -d
```

Once the containers are running:

- Elasticsearch: http://localhost:9200
- Kibana: http://localhost:5601

## Mock Exams

Each mock exam contains:

- Environment setup
- Practice dataset
- Practical questions
- A separate solutions directory

## Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to open an Issue or submit a Pull Request.

## Disclaimer

This is an independent community project and is not affiliated with or endorsed by Elastic.
