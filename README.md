<h1 align="center">
  <br>
  <a href="https://perfecthomelab.allfabox.fr/"><img src="https://github.com/allfab/docker-homeassistant-assist-stack/assets/1840185/a83bea0c-37be-4520-af3a-33a71da2deb2" alt="Perfect Homelab" width="200px"></a>
  <br>
  Home Assistant - Local Assist Pipeline
  <br>
  Docker Compose Stack
  <br>
</h1>

<h4 align="center">Home Assistant Local Assist Pipeline with <a href="https://docs.docker.com/compose/">Docker Compose</a>.</h4>

<p align="center">
  <a href="https://perfecthomelab.allfabox.fr/" target="_blank"><img src="https://img.shields.io/badge/Perfect_Homelab-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white" /></a>
  <a href="https://www.home-assistant.io/" target="_blank"><img src="https://img.shields.io/badge/homeassistant-038fc7?style=for-the-badge&logo=homeassistant&logoColor=white" /></a>
  <a href="https://esphome.io/" target="_blank"><img src="https://img.shields.io/badge/esphome-489e9e?style=for-the-badge&logo=esphome&logoColor=white" /></a>
</p>

<p align="center">
  <a href="#key-features">Principales caractéristiques</a> •
  <a href="#how-to-use">Comment utiliser ce dépôt</a> •
  <!-- <a href="#download">Téléchargement</a> • -->
  <a href="#credits">Crédits</a> •
  <a href="#related">En lien</a> •
  <a href="#license">License</a>
</p>

<!-- ![screenshot](https://raw.githubusercontent.com/amitmerchant1990/electron-markdownify/master/app/img/markdownify.gif) -->

## Principales caractéristiques

Dans Home Assistant, les pipelines `Assist` sont composés de divers composants qui forment ensemble un `assistant vocal`.

Pour chaque composant, vous pouvez choisir parmi différentes options. Il existe une option de reconnaissance vocale (speech-to-text) et de transcription (text-to-speech) qui fonctionne entièrement au niveau local. Aucune donnée n'est envoyée à des serveurs externes pour traitement.

Le composant de reconnaissance vocale est `Whisper`. C'est un modèle d'IA open source qui prend en charge différents langages. Nous utiliserons une version appelée `faster-whisper` de chez linuserver.io. Sur un Raspberry Pi 4, il faut environ 8 secondes pour traiter les commandes vocales entrantes. Sur un NUC Intel, cela se fait en moins d'une seconde.

Pour la transcription, nous utiliserons un outil tel que `Piper`. Toujours dans la flotte de conteneurs Docker de Linuxserver.io. `Piper` est un système un transcripteur local qui est optimisé pour le Raspberry Pi 4. Il prend en charge de nombreuses langues. Sur un Raspberry Pi, en utilisant des modèles de qualité moyenne, il peut générer 1,6 seconde de voix en une seconde.


## Comment utiliser ce dépôt

Pour cloner et exécuter cette application, vous aurez besoin de [`Git`](https://git-scm.com) installé sur votre ordinateur.

Depuis votre ligne de commande :
```bash
# Cloner le dépôt
$ git clone https://github.com/allfab/docker-homeassistant-assist-stack.git

# Se rendre dans le répertoire
$ cd docker-homeassistant-assist-stack

# Exécuter la pile docker compose
$ docker compose up -d
```


## Crédits

- [Setup Local Voice Assistant In Home Assistant Using USB Microphone - Docker Containers Setup Guide](https://smarthomecircle.com/setup-voice-assistant-with-home-assistant-using-docker-usb-microphone)
- [How to Create Custom Wake Word For Your Voice Assistant In Home Assistant](https://smarthomecircle.com/custom-wake-word-for-voice-assistant-with-home-assistant)
- [Installing a local Assist pipeline](https://www.home-assistant.io/voice_control/voice_remote_local_assistant/)

## En lien

[Docker Compose](https://docs.docker.com/compose/) - Docker Compose est un outil permettant de définir et d'exécuter des applications multi-conteneurs.

<!-- ## Soutien

<a href="https://www.buymeacoffee.com/5Zn8Xh3l9" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/purple_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a> -->

## Vous pourriez aimer...

- [Setup Local Voice Assistant In Home Assistant Using USB Microphone - Docker Containers Setup Guide](https://smarthomecircle.com/setup-voice-assistant-with-home-assistant-using-docker-usb-microphone)
- [How to Create Custom Wake Word For Your Voice Assistant In Home Assistant](https://smarthomecircle.com/custom-wake-word-for-voice-assistant-with-home-assistant)
- [Installing a local Assist pipeline](https://www.home-assistant.io/voice_control/voice_remote_local_assistant/)

## License

Licence à définir

---

> [perfecthomelab.allfabox.fr](perfecthomelab.allfabox.fr) &nbsp;&middot;&nbsp;
> GitHub [@allfab](https://github.com/allfab) &nbsp;&middot;&nbsp;
> Twitter [@allfab](https://twitter.com/allfab) &nbsp;&middot;&nbsp;
> Mastodon [@allfab@mapstodon.space](https://mapstodon.space/@allfab)

