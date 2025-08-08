# Devops-pipeline-with-dashboard

A complete CI/CD pipeline with an interactive dashboard for monitoring builds, deployments, and pipeline status.

## 🎯 Features

- **Interactive Dashboard**: Real-time pipeline monitoring
- **GitHub Actions CI/CD**: Automated build, test, and deploy
- **Docker Integration**: Containerized application
- **Automated Testing**: Built-in test scripts
- **Easy Deployment**: One-command deployment

## 🏃‍♂️ Quick Start

### Prerequisites
- Docker installed
- Git installed

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/ibraheemcisse/devops-pipeline-with-dashboard.git
   cd devops-pipeline-with-dashboard
   ```

2. **Run the dashboard locally**
   ```bash
   cd my-app
   docker build -t devops-dashboard .
   docker run -p 8080:80 devops-dashboard
   ```

3. **Access the dashboard**
   Open http://localhost:8080 in your browser

### Using Docker Compose
```bash
docker-compose up -d
```

### Using Build Scripts
```bash
# Build the dashboard
./scripts/build.sh

# Run tests
./scripts/run-tests.sh

# Deploy
./scripts/deploy.sh
```

## 🧪 Testing

Run the test suite:
```bash
./scripts/run-tests.sh
```

## 🚀 Deployment

Deploy to production:
```bash
./scripts/deploy.sh
```

## 📁 Project Structure

- `.github/workflows/` - CI/CD pipeline configuration
- `my-app/` - Dashboard application and Docker setup
- `scripts/` - Automation scripts for testing and deployment
- `docs/` - Project documentation

## 🛠️ Built With

- **Frontend**: HTML5, CSS3, JavaScript
- **Containerization**: Docker, Nginx
- **CI/CD**: GitHub Actions
- **Automation**: Bash Scripts

## 📊 Dashboard Features

- Real-time pipeline status monitoring
- Build statistics and metrics
- Recent builds history
- Responsive design for all devices
- Interactive animations and effects

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Show Your Support

Give a ⭐️ if this project helped you!

---

Built with ❤️ by [ibraheemcisse](https://github.com/ibraheemcisse)
