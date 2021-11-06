# Lavalink.js

Repositorio para iniciar Lavalink en **PM2**, **Heroku**, etc...

## Ubuntu / PM2

**1** Clonar el repositorio de GitHub - ```git clone https://github.com/holasoyender/Lavalink.js.git```

**2** Entrar en la carpeta e instalar dependencias - ```cd Lavalink.js && npm install```

**3** Iniciar PM2 como Lavalink - ```pm2 start bootstrap.js --name Lavalink --no-autorestart```

## Instalar Java JDK 17 en Ubuntu

**1** Descargar Java JDK 17 - ```sudo add-apt-repository -y ppa:openjdk-r/ppa```

**2** Descargar Java JDK 17 - ```sudo apt install -y openjdk-17-jdk```

**3** Verificar la instalación - ```java --version``` (Debería de devolver `openjdk version "17" ...`)
