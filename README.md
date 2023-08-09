# WSL2
Attention si des problèmes de connexion, il faut changer le host dans le fichier `glupfile.js`
- `const host = yargs.argv.host || '0.0.0.0'`

# Installation
- docker-compose up -d
- docker exec -it node bash
- npm install
- npm start (default port 8000)
  - npm start -- --port=80