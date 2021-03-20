# help
Help desk

const Asena = require('../events');
const {MessageType} = require('@adiwajshing/baileys');
const con = require('../config');


    if (con.WORKTYPE === 'private') {

        Asena.addCommand({pattern: 'help', fromMe: true, desc: ENZAR}, (async (message, match) => {

            await message.client.sendMessage(message.jid, ENSEN, MessageType.text);
            await new Promise(r => setTimeout(r, 4000));

            // Numbers
            var r_text = new Array ();
            r_text[0] = "╾──────────────╼
⎚⎚⎚ㅈ𓊈Help𓊉ㅈ⎚⎚⎚
╾──────────────╼

☞:sticker
💌Use - To covert picture, gif or video into sticker.

☞:imagesticker
💌Use - To convert sticker into image.

☞:removebg
💌Use - To remove the background of the image.

☞:insta
💌Use -To get user information from instagram.
Example - :insta <username>

☞:ocr 
💌Use -To read the text on the photo.

☞:trt 
💌Use -To translate the text into different languages.
Example - :trt en hi (from English to Hindi)

☞:tts 
💌Use -To convert text into sound.

☞:wiki 
💌Use -To search query on Wikipedia.

☞:ss 
💌Use -To get the screenshot of 
website 
Example - :ss <website link>

☞:animesay
💌Use -It writes the text inside the banner the anime girl holding.
Example - :animesay This world shall know pain.

☞:changesay
💌Use -To convert text to change my mind meme poster.
Example - :changesay Haku is a boy.

☞:trumpsay
💌Use -To convert text to Trump's tweet.
Example - :trumpsay hello

☞:alive 
💌Use -To check if bot is online or offline.

☞:img
💌Use -To get images from Google.
Example - :img Pain Naruto

☞:ttp 
💌Use -To convert text to plain image.
Example - :ttp Hello

☞:attp
💌Use -To convert text to colourful animated sticker.
Example - :attp Hello

☞:wallpaper
💌Use -To get random hd wallpaper.
Example - :wallpaper

☞:weather 
💌Use -To get the weather update.
Example - :weather solan

☞:speedtest 
💌Use -To know the bot internet speed.

☞:ping 
💌Use -To know the bot ping.

☞:roll 
💌Use -To roll dice.

☞:covid 
💌Use -To get covid stats.
Example - 
:covid in     [For India]
:covid jp     [For Japan]
:covid usa  [For USA]
:covid         [For Worldwide]

    𓊈Media Commands𓊉

☞:song 
💌Use - Upload the song you want.
Example - :song believer
                   :song <yt link>

☞:ytsearch 
💌Use - To get youtube video links.
Example - :ytsearch dynamite

☞:video 
💌Use - Upload the yt video you want.
Example - :video <yt link>

☞:mp4audio
💌Use -To convert video to audio.

☞:tts 
💌Use -To convert text to sound.
Example - :tts sekai ni itami o
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁";
          

            var i = Math.floor(6*Math.random())

            await message.client.sendMessage(message.jid, ENSON + `${r_text[i]}`, MessageType.text);

        }));
    }
    else if (con.WORKTYPE === 'public') {

        Asena.addCommand({pattern: 'help', fromMe: false, desc: ENZAR}, (async (message, match) => {

            await message.client.sendMessage(message.jid, ENSEN, MessageType.text);
            await new Promise(r => setTimeout(r, 4000));

            // Numbers
            var r_text = new Array ();
            r_text[0] ="╾──────────────╼
⎚⎚⎚ㅈ𓊈Help𓊉ㅈ⎚⎚⎚
╾──────────────╼

☞:sticker
💌Use - To covert picture, gif or video into sticker.

☞:imagesticker
💌Use - To convert sticker into image.

☞:removebg
💌Use - To remove the background of the image.

☞:insta
💌Use -To get user information from instagram.
Example - :insta <username>

☞:ocr 
💌Use -To read the text on the photo.

☞:trt 
💌Use -To translate the text into different languages.
Example - :trt en hi (from English to Hindi)

☞:tts 
💌Use -To convert text into sound.

☞:wiki 
💌Use -To search query on Wikipedia.

☞:ss 
💌Use -To get the screenshot of 
website 
Example - :ss <website link>

☞:animesay
💌Use -It writes the text inside the banner the anime girl holding.
Example - :animesay This world shall know pain.

☞:changesay
💌Use -To convert text to change my mind meme poster.
Example - :changesay Haku is a boy.

☞:trumpsay
💌Use -To convert text to Trump's tweet.
Example - :trumpsay hello

☞:alive 
💌Use -To check if bot is online or offline.

☞:img
💌Use -To get images from Google.
Example - :img Pain Naruto

☞:ttp 
💌Use -To convert text to plain image.
Example - :ttp Hello

☞:attp
💌Use -To convert text to colourful animated sticker.
Example - :attp Hello

☞:wallpaper
💌Use -To get random hd wallpaper.
Example - :wallpaper

☞:weather 
💌Use -To get the weather update.
Example - :weather solan

☞:speedtest 
💌Use -To know the bot internet speed.

☞:ping 
💌Use -To know the bot ping.

☞:roll 
💌Use -To roll dice.

☞:covid 
💌Use -To get covid stats.
Example - 
:covid in     [For India]
:covid jp     [For Japan]
:covid usa  [For USA]
:covid         [For Worldwide]

    𓊈Media Commands𓊉

☞:song 
💌Use - Upload the song you want.
Example - :song believer
                   :song <yt link>

☞:ytsearch 
💌Use - To get youtube video links.
Example - :ytsearch dynamite

☞:video 
💌Use - Upload the yt video you want.
Example - :video <yt link>

☞:mp4audio
💌Use -To convert video to audio.

☞:tts 
💌Use -To convert text to sound.
Example - :tts sekai ni itami o
▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁";

            var i = Math.floor(6*Math.random())

            await message.client.sendMessage(message.jid, ENSON + `${r_text[i]}`, MessageType.text);

        }));
    }
}
