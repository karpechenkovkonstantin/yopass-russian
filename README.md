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
docker build -t kkd/yopass-ru -f Dockerfile
```

---
## Русский 

Русский перевод для Yopass разработаного Johan Haals (jhaals/yopass)   
[Yopass - Делись секретами безопасно](https://github.com/jhaals/yopass)

### Установка

Скопируйте файл website/public/locales/ru.json в аналогичный каталог вашего Yopass.

Yopass автоматически обнаружит новый язык и подключит его если он выбран в качестве языка браузера. Предпочтительный язык браузера, определяется на основе информации в следующем порядке:

 - строка запроса (добавьте ?lng=LANGUAGE в URL)
 - cookie-файл (установите следующее значение cookie i18next=LANGUAGE)
 - локальное хранилище (установите ключ i18nextLng=LANGUAGE)
 - сессионное хранилище (установите ключ i18nextLng=LANGUAGE)
 - браузер (язык браузер)
 - html-тэг (значение html lang="LANGUAGE")

Список можно изменить в параметрах i18n в ./src/i18n.tsx. Подробности на https://github.com/i18next/i18next-browser-languageDetector.

### Контейнер

На основе этого репозитория вы можете создать свой docker-образ на русском языке взяв оригинальный образ Yopass-Image из docker.io.

```
git clone https://github.com/karpechenkovkonstantin/yopass-russian.git
cd yopass-russian
docker build -t kkd/yopass-ru -f Dockerfile
```
