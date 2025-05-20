# 🛠️ Cuby Environment

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Cuby-Project/Cuby-environment.svg)](https://github.com/Cuby-Project/Cuby-environment/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Cuby-Project/Cuby-environment.svg)](https://github.com/Cuby-Project/Cuby-environment/network)
[![GitHub issues](https://img.shields.io/github/issues/Cuby-Project/Cuby-environment.svg)](https://github.com/Cuby-Project/Cuby-environment/issues)
[![GitHub last commit](https://img.shields.io/github/last-commit/Cuby-Project/Cuby-environment.svg)](https://github.com/Cuby-Project/Cuby-environment/commits/main)

</div>

## 📝 Description

Cuby Environment is the infrastructure and deployment configuration for the Cuby ecosystem. This repository contains Docker configurations, environment variables, and deployment scripts to set up and run all Cuby services in a production environment.

## 🔗 Related Projects

- [Cuby Client](https://github.com/Cuby-Project/Cuby-Client) - Main desktop application
- [Cuby Mobile App](https://github.com/Cuby-Project/Cuby-mobile-app) - Mobile version
- [Cuby Recognition API](https://github.com/Cuby-Project/Cuby-recognition-API) - Color detection API
- [Cuby Solve API](https://github.com/Cuby-Project/Cuby-solve-API) - Cube solving algorithm API
- [Cuby Capture API](https://github.com/Cuby-Project/Cuby-capture-API) - Cube state capture API
- [Cuby Capture Website](https://github.com/Cuby-Project/Cuby-capture-website) - Web interface

## ✨ Features

- 🐳 Docker containerization
- 📊 PostgreSQL database
- 📈 Grafana monitoring
- 🔄 OpenTelemetry integration
- 🔒 Environment variable management
- 🚀 Easy deployment

## 🚀 Getting Started

### 🔧 Prerequisites

- Docker and Docker Compose
- Git
- Basic knowledge of containerization

### 🛠️ Installation

1. Clone the repository:

```bash
git clone https://github.com/Cuby-Project/Cuby-environment.git
```

2. Configure environment variables:

```bash
cp .env.example .env
# Edit .env with your configuration
```

3. Start the services:

```bash
docker-compose up -d
```

## 📊 Services

### PostgreSQL

- Port: 5432
- Purpose: Main database for the Cuby ecosystem

### Grafana (LGTM)

- Port: 3000
- Purpose: Monitoring and visualization
- Additional ports:
  - 4317: OTLP gRPC receiver
  - 4318: OTLP HTTP receiver
  - 55681: OpenTelemetry Collector

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🔮 Roadmap

- Kubernetes support
- Enhanced monitoring
- Automated backups
- CI/CD integration
- Security improvements

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

*quentinformatique*

## 📞 Support

- [Report a bug](https://github.com/Cuby-Project/Cuby-environment/issues/new/choose)
- [Request a feature](https://github.com/Cuby-Project/Cuby-environment/issues/new/choose)
