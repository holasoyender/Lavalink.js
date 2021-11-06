# Lavalink.js

Repositorio para iniciar Lavalink en **PM2**, **Heroku**, etc...

## Ubuntu / PM2

**1** Clonar el repositorio de GitHub - ```git clone https://github.com/holasoyender/Lavalink.js.git```

**2** Entrar en la carpeta e instalar dependencias - ```cd Lavalink.js && npm install```

**3** Iniciar PM2 como Lavalink - ```pm2 start bootstrap.js --name Lavalink --no-autorestart```

## Instalar Java JDK 17 en Ubuntu

**1** Descargar Java JDK 17 - ```wget https://download.java.net/java/GA/jdk17/0d483333a00540d886896bac774ff48b/35/GPL/openjdk-17_linux-x64_bin.tar.gz```

**2** Extraer el archivo - ```sudo tar xvf openjdk-17_linux-x64_bin.tar.gz```

**3** Mover la carpeta descomprimida a la carpeta **opt** - ```sudo mv jdk-17 /opt/```

**4** Establecer las variables del entorno (de una en una) -
```export JAVA_HOME=/opt/jdk-17```
```export PATH=$PATH:$JAVA_HOME/bin```
```source ~/.bashrc```

**5** Verificar la instalación - ```java --version``` (Debería de devolver `openjdk version "17" ...`)
