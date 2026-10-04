# DevOps, CI/CD & Monitoring

## Contents
- DevOps, Git/GitHub and CI/CD notes
- Sample GitHub Actions CI pipeline
- Dockerfile
- Sample Node.js application
- Deployment and monitoring overview

## Flow
GitHub -> Build -> Test -> Docker -> Deploy -> Monitor

## Run the sample application
```bash
npm install
npm test
npm start
```

The application runs on port 3000.

## Docker
```bash
docker build -t devops-demo .
docker run -p 3000:3000 devops-demo
```

## Git workflow
```bash
git add .
git commit -m "Add CI/CD demo"
git push origin main
```
