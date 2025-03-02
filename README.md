# Empangeni-LAN-Chat

Empowering communication in Empangeni. This LAN chat application uses AI to break down language barriers, providing real-time translation, voice support, and OCR for inclusive community interaction.

## Zulu Introduction

Sawubona! Siyakwamukela ku-Empangeni-LAN-Chat. Lolu hlelo lokusebenza lwakhiwe ukusiza abantu base-Empangeni ukuba baxhumane kalula, noma ngabe bakhuluma izilimi ezahlukene. Sebenzisa ubuchwepheshe be-AI ukuhumusha imilayezo, ukukhuluma ngezwi, nokukhipha umbhalo ezithombeni. Yonke imininingwane yakho ihlala kumakhompyutha akho kuphela, ivikelekile ngokuphelele.

(Translation: Hello! Welcome to Empangeni-LAN-Chat. This application is designed to help the people of Empangeni communicate easily, even if they speak different languages. It uses AI technology to translate messages, speak in voice, and extract text from images. All your information stays on your local computers only, completely secure.)

## Getting Started

To run this application, you'll need free API keys from Gemini and Azure Cognitive Services. Here's how to get them:

### Gemini API Key

1.  Go to the [Google AI Studio](https://makersuite.google.com/app/apikey) website.
2.  Log in with your Google account.
3.  Create a new API key.
4.  Copy the API key.

### Azure Cognitive Services API Key

1.  Go to the [Azure portal](https://portal.azure.com/).
2.  Create a free Azure account if you don't have one.
3.  Create a "Speech" resource and a "Computer Vision" resource.
4.  Navigate to the "Keys and Endpoint" section of each resource.
5.  Copy the subscription key and region.

Once you have the API keys, add them to the `config.ini` file in the root directory of the project.

## Running the Application

1.  Clone this repository to your local machine: `git clone <repository_url>`
2.  Navigate to the project directory: `cd Empangeni-LAN-Chat`
3.  Install the required Python packages: `pip install -r requirements.txt`
4.  Run the Flask backend: `python app.py`
5.  Open the `index.html` file in the `frontend` directory in your web browser.
6.  Ensure all devices are connected to the same LAN Wi-Fi network.

## Functionality

* **Real-time LAN Chat:** Send and receive messages instantly within your local network.
* **Gemini-Powered Translation:** Translate messages into multiple languages with cultural nuance.
* **Azure Text-to-Speech:** Listen to messages in Afrikaans, English, and Zulu.
* **Optical Character Recognition (OCR):** Extract text from images and handwritten notes.
* **Voice Customization:** Adjust pitch and rate for voice synthesis.
* **Conversation Analysis:** Analyze conversation history for insights.
* **Local Data Security:** All data and context remain on users' local machines, ensuring complete privacy and control.

## Information Security

Your privacy is our top priority. This application is designed to keep your data secure. All information and context remain on your local machines and are never sent to external servers, except for the API calls to Gemini and Azure. This gives you complete control over your data.

## Technologies Used

* Gemini 2.0 Flash
* Azure Cognitive Services (Speech Synthesis, Computer Vision)
* Flask (Backend)
* HTML, CSS, JavaScript (Frontend)
* jQuery

## Acknowledgements

This project would not have been possible without the powerful AI technologies provided by:

* **Gemini:** For its exceptional natural language processing, cultural nuance understanding, and real-time translation capabilities.
* **Microsoft Azure Cognitive Services:** For its robust Text-to-Speech (TTS) services in multiple languages and accurate Optical Character Recognition (OCR).

We extend our deepest gratitude to these giants for their contributions, enabling us to bridge communication barriers and foster human connections in Empangeni. We are thankful that these technologies are now accessible to our local people, making communication easier and more effective.
