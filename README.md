# AWS DevOps Challenge - Fullstacklab

Install command:
brew install node@14
Platform built on V8 to build network applications

https://nodejs.org/


### Local Setup

1. Clone the repo:

```
git clone https://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@github.com/fullstacklabs/devops-ci-challenge.git
```    

2. Node setup for CI pipeline with all 5 stages:
```
    npm install
    npm run lint
    npm run prettier
    CI=true npm run test
    npm run build
```

3. Local Testing: