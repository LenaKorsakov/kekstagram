# Kekstagram
A simple application in vanilla JavaScript that allows the user to upload their photos to the site, filter and sort photos in the feed, like and comment on other people's photos.

## Description
When you start the application, you will see previews of other users' photos. When you hover your mouse over each of the previews, information about the number of likes and comments is displayed.
![Main-screenshot](https://github.com/LenaKorsakov/kekstagram/blob/master/screens/main-screen.png)

You can apply three different filters to the photo in the feed: default, by popularity (by a number of comments) or to show any 10 photos.
![Filter-screenshot](https://github.com/LenaKorsakov/kekstagram/blob/master/screens/filter-screen.png)

You can open each photo full screen, read its description, and view other users' comments about it.
![Photo-screenshot](https://github.com/LenaKorsakov/kekstagram/blob/master/screens/photo-screen.png)

The most interesting thing about this app is that you can upload your own photo to the site.  Right in the app you can edit the photo: apply one of the available effects, intensify or weaken the effect with a handy slider, and change the scale of the photo.
You can also leave a description and hashtags under the photo. The forms have strict validation and verification of the entered data.
![Photo-screenshot](https://github.com/LenaKorsakov/kekstagram/blob/master/screens/loading-screen.png)

If the photo has been successfully sent to the server, a popup will appear with the message that it was successful. If an error occurs, a popup with an error message appears.
![Success-screenshot](https://github.com/LenaKorsakov/kekstagram/blob/master/screens/success-screen.png)

## Stack
- JavaScript(ES18)
- HTML
- CSS
- Nouislider
- Pristine validation

My very first attempt at building an app.

## Demo site
<a href="https://lenakorsakov.github.io/kekstagram/">Go to site</a>

## How to run app:

- Clone repository:
```bash
git clone git@github.com:LenaKorsakov/kekstagram.git
```

- Install dependencies repository:

```bash
npm install
```

- Run application:

```bash
npm start
```
