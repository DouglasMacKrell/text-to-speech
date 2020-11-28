# Doug's Text-To-Speech App

### Live @ [dougs-text-to-speech.netlify.app](https://dougs-text-to-speech.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/dc46b693-3db8-4bff-8783-7d3369efa6d3/deploy-status)](https://app.netlify.com/sites/dougs-text-to-speech/deploys)

**Doug's Text-To-Speech App** is a static website that will allow users to write any text into a growing text field, and convert that text to speech via JavaScript and built-in browser tools. 

Built with HTML and JavaScript.

[![Douglas MacKrell](https://www.douglasmackrell.com/Doug-Portfolio-Social.png)](https://dougmackrell.com)

## Features

Users are able to:

* Type text into a textArea
* Adjust the speed of the reader
  * This can be adjusted while the reader is speaking
* Pause the reader, and resume from exactly where the reader was paused
* Stop and reset the reader 

## Future Features

* Fix a bug in the text area that locks edits after the reader has run, but before a full reset is called by the user via the Stop button
* Allow the user to change the computer voice used without having to jump into their browser settings
* Additional styling

## Technical Milestones

* Learning how to create a new SpeechSynthesisUtterance and controlling that through speechSynthesis 

## Technologies Used

* **HTML** For displaying the static webpage
* **JavaScript** For handling the text-to-speech functionality

## Local Setup

You must install [Node.js](https://nodejs.org) in your computer.

You can check for this dependency by entering `node -v` in your terminal. If your shell/terminal doesn't complain and you see version numbers you are good to go.

1. Clone this repo into a folder of your choice:
```
       git clone https://github.com/DouglasMacKrell/text-to-speech
```

2. To launch the site, open the folder you selected in Step 1 and right click on:
```
       index.html
```

3. Finally, select "Open With", and select the browser of your choice.

4. A new browser tab should have been opened and the App should be running. If that is not the case check the terminals output for errors, if you are unable to troubleshoot the problem, I would be happy to address issues so open [one](/issues)

---

### Please check out my other work at [DouglasMacKrell.com](https://douglasmackrell.com)

---

[![DougTV Social Media](https://dougtv.herokuapp.com/DougTV-Social.png)](https://dougtv.herokuapp.com)

** **

<details>
    <summary>
        Before you leave, please take note:
    </summary>

You're the best! Thank you for visiting!

Please give this project a star and be sure to check out my [YouTube Channel](https://youtube.com/BigMacKrell)!

</details>
