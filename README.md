# Hypertube
3rd and last Web project for 42 school, Hypertube is a streaming site (made in React / Nodejs):

This project was done with [Phillipine Sentilhes](https://github.com/pommedepain), [Benjamin Tollie](https://github.com/BenjaminTle) et [Camille Julien](https://github.com/cajulien42)

Camille was in charge of the scrapping process Philippine was in charge on the API and the custom player,Benjamin was in charge of the streaming part. I was in charge of the UI/UX (Wireframe, prototype and code in React). 

## SUMMARY
- What is Hypertube ?
- Usage
- Gallery


## What is Hypertube ?
3rd and last project of the Web Branch of 42. Hypertube is a streaming website based on the bittorrent protocole. After the user has authenticated, he is able to choose from our 14 000 film reference && 3000 shows.

### Features
- Automatic scrapping of external API (CRON) every day with a custom database switch system
- Live streaming watch the torrent as it is still downloading.
- On the fly transcoding for the files with no supported extensions (ffmpeg)
- Fully customized player controls.
- Non-blocking download management.
- Experimental UX.
- Readable and clear UI.

## Usage
Just go the the api folder and run `npm i` You can now just `run npm run dev` and you're ready to go.

Note that you need to have ffmpeg installed to make the website work with many extensions. Be sure you have it installed locally.

+ you will need MongoDb install on your computer (you can install it [here](https://docs.mongodb.com/manual/administration/install-community/) )

__NB:__ This project has only a pedagogic goal, it is not meant for production as this would cause a lot of copyright problems

## Gallery
