# Lavalink.js

<a href="https://heroku.com/deploy?template=https://github.com/holasoyender/Lavalink.js">
    <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>

Repositorio para iniciar Lavalink en **PM2**, **Heroku**, etc...

## Iniciar con PM2

**1** Clonar el repositorio de GitHub - ```git clone https://github.com/holasoyender/Lavalink.js.git```

**2** Entrar en la carpeta e instalar dependencias - ```cd Lavalink.js && npm install```

**3** Configurar lavalink en el archivo `application.yml` (Sustituir 0.0.0.0 por localhost)

**4** Iniciar PM2 como Lavalink - ```pm2 start bootstrap.js --name Lavalink --no-autorestart```

# Dependencias

## Instalar Java JDK 17 en Ubuntu

**1** Descargar Java JDK 17 - ```sudo add-apt-repository -y ppa:openjdk-r/ppa```

**2** Descargar Java JDK 17 - ```sudo apt install -y openjdk-17-jdk```

**3** Verificar la instalación - ```java --version``` (Debería de devolver `openjdk version "17" ...`)

## Instalar Node.js y npm

**1** Instalar NPM - ```sudo apt install npm```

**2** Descargar NodeJS - ```cd ~ && curl -sL https://deb.nodesource.com/setup_16.x -o nodesource_setup.sh```

**3** Ejecutar el instalador - ```sudo bash nodesource_setup.sh```

**4** Instalar NodeJS - ```sudo apt install nodejs```

## Instalar PM2 

**1** Instalar PM2 desde NPM - ```npm i -g pm2```
