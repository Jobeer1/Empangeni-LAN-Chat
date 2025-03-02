# Empangeni-LAN-Chat

This program is a personal assistant that you can use on your computer. It can talk to you, understand your voice, and even describe pictures.

## How to Use

1.  **Download the Program:**
    * Go to the "Releases" section of this page. You'll find it on the right side of the screen.
    * Download the file named `Empangeni-chat.exe`.

2.  **Get API Keys:**
    * This program uses special keys to connect to the internet and do things like understand speech and describe pictures.
    * You'll need to get your own keys from these websites:
        * **Azure:** Go to [Azure Cognitive Services](https://azure.microsoft.com/en-us/products/cognitive-services/) and create an account. You'll need keys for "Speech" and "Computer Vision".
        * **Google:** Go to [Google AI Studio](https://makersuite.google.com/app/apikey) and create an API key.
    * Write these keys down. You'll need them in the next step.

3.  **Set Up the Program:**
    * When you first run `Empangeni-chat.exe`, it will look for a file named `config.ini` in the same folder.
    * If `config.ini` does not exist, it will create one for you.
    * Open the `config.ini` file using a text editor (like Notepad).
    * Type in the keys you got from Azure and Google into the `config.ini` file. Replace the placeholders with your actual keys.
    * Save the `config.ini` file.

4.  **Start Using the Program:**
    * Once you've entered the keys, the program will start.
    * You can talk to it using your microphone.
    * You can also give it pictures to describe.

## What It Can Do

* **Talk to You:** The program can speak to you using a computer voice.
* **Understand Your Voice:** It can understand what you say.
* **Describe Pictures:** If you give it a picture, it can tell you what's in it.
* **Answer Questions:** It can answer your questions using Google's Gemini AI.

## Important Notes

* **Internet Connection:** This program needs an internet connection to work.
* **API Keys:** Keep your API keys safe. Don't share them with anyone.
* **Help:** If you have any problems, you can ask for help by creating an "issue" on this page. You'll find the "Issues" tab at the top of the screen.

## Zulu Translation (Ukuhumusha KwesiZulu)

* **Ifayela le-EXE (Empangeni-chat.exe):** Leli fayela liyisicelo sokuthi usebenzise kumakhompyutha wakho.
* **Ifayela le-config.ini:** Leli fayela lidinga ukuthi libe sefoldeni efanayo ne-Empangeni-chat.exe. Udinga ukuvula leli fayela usebenzisa i-text editor bese ufaka ama-API keys akho.

## Afrikaans Translation (Afrikaanse Vertaling)

* **Vir Ontwikkelaars (Vir Ontwikkelaars):**
    * Om die kode te verander, moet jy die volgende doen:
        * Kry die API sleutels van Azure en Google.
        * Werk die `config.ini` lêer op met jou sleutels.
        * Installeer die benodigde pakkette deur `pip install -r requirements.txt` te gebruik.
        * Maak seker dat jy die `venv` gids nie na GitHub stoot nie.

## Thank You

Thank you for using Empangeni-LAN-Chat! We hope you find it helpful.
