# yopass - Russian language File


## English
Russian language File for yopass by Johan Haals (jhaals/yopass)   
[Yopass - Share Secrets Securely](https://github.com/jhaals/yopass)

### Installation

Copy the website/public/locales/ru.json file to the corresponding directory in your Yopass installation.

Yopass will automatically detect the new language and activate it if your Browser presents that language to Yopass. The user interface tries to determine the browser's preferred language by using the following information (in the given order):

 - querystring (append ?lng=LANGUAGE to URL)
 - cookie (set cookie i18next=LANGUAGE)
 - localStorage (set key i18nextLng=LANGUAGE)
 - sessionStorage (set key i18nextLng=LANGUAGE)
 - navigator (browser language)
 - htmlTag (html lang="LANGUAGE")

You can change this list in the i18n options in ./src/i18n.tsx. Please have a look at https://github.com/i18next/i18next-browser-languageDetector for the details.

### Container

Check this repository out and build your own container with the russian language file included to the original Yopass-Image from docker.io.

```
git clone https://github.com/karpechenkovkonstantin/yopass-russian.git
cd yopass-russian
docker build -t kkd/yopassde -f Dockerfile
```

---
## Русский 

Deutsche Sprachdatei für Yopass von Johan Haals (jhaals/yopass)   
[Yopass - Share Secrets Securely](https://github.com/jhaals/yopass)

### Установка

Kopiere die Datei website/public/locales/de.json in das entsprechende Verzeichnis der yopass-Installation.

Die Sprachdatei wird automatisch erkannt und genutzt, wenn der Browser die Sprache an yopass übermittelt.

### Контейнер

Einfach dieses Repo klonen und einen eigenen Container bauen, der die deutsche Sprachdatei in das Original-Yopass-Image von docker.io integriert.

```
git clone https://github.com/Anturix/yopass-german.git
cd yopass-german
docker build -t anturix/yopassde -f Dockerfile
```
