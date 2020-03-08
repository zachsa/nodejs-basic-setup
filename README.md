# Nodejs Basic Setup
I'm getting tired of setting up Babel, ESLint, Prettier, and associated NPM scripts every time I want to try out some Node.js code (using ESM the babel way!). This repository is just a nice starter

# Install
```npm install```

# Start development server
```npm start```

# Start production server
```npm start:prod```

# Automated deployment
1. Add a self-hosted action runner to your server
2. `.github/workflows/master-branch.yml` should run on commits to master
3. This repository is setup to deploy 2 containers - a PostGIS database and Node app via docker-compose