# DevOps, CI/CD & Monitoring – Study Notes

## 1. DevOps
DevOps combines Development and Operations to automate and improve software delivery.

Key principles:
- Collaboration
- Automation
- Continuous integration
- Continuous delivery/deployment
- Monitoring
- Fast feedback
- Infrastructure as Code

## 2. Git and GitHub
Git tracks source-code changes. GitHub hosts Git repositories and supports collaboration.

Common commands:
git clone <url>
git status
git add .
git commit -m "message"
git push origin main
git pull origin main

## 3. CI/CD
Continuous Integration automatically builds and tests code after changes are pushed.

Continuous Delivery prepares tested software for release.

Continuous Deployment automatically releases successfully tested changes to production.

## 4. Pipeline
GitHub -> Build -> Test -> Docker -> Deploy -> Monitor

## 5. Docker
Docker packages an application and its dependencies into a container.

Typical commands:
docker build -t myapp .
docker run -p 3000:3000 myapp

## 6. Monitoring
Monitoring checks application health and performance.

Logs:
Record application events and errors.

Metrics:
CPU, memory, request count, response time and error rate.

Alerts:
Notify the team when a threshold or failure condition is reached.

## 7. Environment Management
Typical environments:
Development -> Testing -> Staging -> Production

Secrets such as API keys and database passwords should be stored as environment variables or CI/CD secrets, not committed to GitHub.

## Exam Flow
Developer -> GitHub -> Build -> Automated Test -> Docker -> Deploy -> Logs/Metrics -> Feedback
