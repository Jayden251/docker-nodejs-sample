# README DATEI

## Schritte zur Installation

### 1

Klonen Sie das Repository lokal auf Ihren Computer:  
git clone <https://github.com/DEIN_USERNAME/docker-nodejs-sample.git>  
Wechseln Sie danach in das Projektverzeichnis:  
cd docker-nodejs-sample

### 2. Installation der notwendigen Pakete

Installieren Sie die benötigten Node.js-Pakete mit folgendem Befehl:  
npm install

### 3. Docker-Konfiguration und -Installation

 (<https://docs.docker.com/get-docker/>).

### 4. Starten der Applikation in einem Docker-Container

Erstellen Sie das Docker-Image mit folgendem Befehl:  
docker build -t todo-app .

Starten Sie dann die Anwendung in einem Docker-Container:  
docker run -p 3000:3000 todo-app

Die Applikation sollte nun unter <http://localhost:3000> erreichbar sein.
