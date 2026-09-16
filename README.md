# Docker Node.js Sample

Eine einfache Node.js-Anwendung, die mit Docker betrieben wird.

## Installation

### 1. Repository klonen

```bash
git clone https://github.com/Amir-1210/docker-nodejs-sample-amir.git
cd docker-nodejs-sample-amir
```

### 2. Abhängigkeiten installieren

```bash
npm install
```

### 3. Sicherstellen, dass Docker Desktop installiert ist

Installiere Docker Desktop und stelle sicher, dass es läuft.

Gib diesen Command im Terminal von VS Code ein:

```bash
docker --version
```

### 4. Anwendung mit Docker starten

Stelle sicher, dass Docker Desktop läuft.

Gib diesen Command im Terminal ein:

```bash
docker compose up --build
```

Die Anwendung ist danach unter http://localhost:3000 erreichbar.
