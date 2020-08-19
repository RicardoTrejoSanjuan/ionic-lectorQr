# ionic-lectorQr

En este repositorio se encuentra el código para las aplicaciones móviles de Andriod y IOS, las cuales se generan con el mismo código escrito en Angular 7.

MapBox
QRs


# Contenido
1. [Requerimientos](#Requerimientos)
2. [Instalación](#Instalación)
3. [Ejecución](#Ejecución)
4. [Construir aplicación](#construir-aplicación)
5. [Imagenes de la aplicación](#Imagenes-de-la-aplicación)


## Requerimientos:

- NodeJs 10+
- NPM 6+

## Instalación:ç

Construir de forma local

```bash
ionic cordova add platform android

ionic cordova run android
```


``` bash
npm install -g ionic
npm install
```
---

## Ejecución

### Ejecutar en Dev Server (Web Browser)

``` bash
ionic serve --lab
```

---

### Extensiones recomendadas para VSCode

- Angular Language Service
- Angular Snippets
- Ionic 4 Snippets
- Angular2 Switcher


---

## Construir aplicación

### Android APK Dev

Actualizar versión de la aplicación.

```bash
npm start
```

### Android APK Prod

Dependencias:

- Android Studio
- Gradle
- Cordova (npm i -g cordova)
- JDK 1.8
- keytool
- jarsigner
- zipalign

### Variables de entorno requeridas:

**ANDROID_HOME** y **JAVA_HOME**

Ej. 

(Ubuntu)
```bash
export ANDROID_HOME=/home/user/Android/Sdk/ 
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/ 
```

(OSX)
```bash
export ANDROID_HOME=/Users/ricardo/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/tools:$ANDROID_HOME/platform-tools
```

## Imagenes de la aplicación

![Alt](/img/home.png | width=100 "Inicio")
![Alt](/img/historial.png "Historial")
![Alt](/img/share.png "Compartir")
![Alt](/img/map.png "Mapa 3D")
![Alt](/img/qr.png "Lector QR")
![Alt](/img/qr3.png "Lector QR")



## Documentación
* [ionic debug](https://ionicframework.com/docs/appflow/quickstart/deploy)
* [ionic](https://ionicframework.com/docs/intro)
* [Angular](https://angular.io/docs)
* [TypeScript](https://www.typescriptlang.org/docs/home.html)
* [MapBox](https://www.mapbox.com/)
* [QR](https://www.qrcode.es/es/home/)

