# Echoes of the Lost Tongue
![image](https://github.com/user-attachments/assets/4b9beb02-2c4a-4ede-a3dc-98e68a26214b)

> A language learning RPG providing the immersive environment best suited for learning new languages.

![GitHub last commit](https://img.shields.io/github/last-commit/Marcrafting/ELT-RPG)
![GitHub commit activity](https://img.shields.io/github/commit-activity/w/marcrafting/ELT-RPG)
![GitHub contributors](https://img.shields.io/github/contributors/marcrafting/ELT-RPG)

## [Download the Latest Model](https://github.com/MarCrafting/ELT-RPG/releases/)

## Instructions to get the game to its intentional functioning state:

1. Ensure you have downloaded Anki and have it opened. The `Anki Essentials` folder provides all you need to set up Anki. You can also download Anki directly from [Anki's download page](https://apps.ankiweb.net).

2. Import the provided Anki deck package into Anki by clicking the `Import File` button in Anki.

3. Install the Anki-Connect addon by doing the following:
    - Open the `Install Add-on` dialog by selecting `Tools` then click on `Add-ons` and finally `Get Add-ons...` in Anki
    - Input `2055492159` into the text box labeled "Code" and press `OK` to proceed
    - Restart Anki when prompted to complete the installation of Anki-Connect

4. Configure Anki-Connect
    - Go back to the add-ons, make sure `Anki-Connect` is selected, then click `Config`
    - Replace the code section with the code below:

    ```js
    {
        "apiKey": "MySecureApiKey",
        "apiLogPath": null,
        "ignoreOriginList": [],
        "webBindAddress": "127.0.0.1",
        "webBindPort": 8765,
        "webCorsOriginList": ["http://localhost/"]
    }

5. THAT'S IT!!
Go to the `ELT Game` folder and launch the `Echoes of the Lost Tongue.exe` executable, your game is ready!

> [!NOTE]
>## Shortcut Keys:
>
>E - interact
>
>Q or ESC - quit menu

> [!TIP]
>## FAQ:
>
>**Q:** Why isn't the lesson loading?  
>**A:** Make sure you have Anki running in the background BEFORE you launch the game.
>
>**Q:** My lesson is having other issues, why?  
>**A:** Check if you successfully imported the Anki Deck. You'll know it was successful if you can see the deck named `Japanese Phonetic Writing System - Free Refold Deck` populated as one of your decks in Anki.
>
>**Q:** There's some connection error I keep seeing, what do I do?  
>**A:** After updating the Anki-Connect add-on Config, don't forget to click `Apply` to save the changes. If issues persist, try uninstalling Anki-Connect (ONLY THE ADD-ON) and reinstall it. When you open the Config, only edit the `apiKey` field. Change the value to `"MySecureApiKey",`. The line should look like this:
>```js
>"apiKey": "MySecureApiKey",
