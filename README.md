# Regional-Language-Translator-using-openai-whisper
 A chatbot that allows users to provide audio files, either through recordings or uploads, and receive the corresponding translated English version.

The chatbot is built using the Flask app wherein the user is provided with options of either uploading live audio through recordings or uploading a preexisting audio file. The audio will be fed as input to the LLM. The LLM used in this project is openai whisper-1. The openai whisper model supports 98 languages in total of which the following languages have greater accuracy: 

Afrikaans, Arabic, Armenian, Azerbaijani, Belarusian, Bosnian, Bulgarian, Catalan, Chinese, Croatian, Czech, Danish, Dutch, English, Estonian, Finnish, French, Galician, German, Greek, Hebrew, Hindi, Hungarian, Icelandic, Indonesian, Italian, Japanese, Kannada, Kazakh, Korean, Latvian, Lithuanian, Macedonian, Malay, Marathi, Maori, Nepali, Norwegian, Persian, Polish, Portuguese, Romanian, Russian, Serbian, Slovak, Slovenian, Spanish, Swahili, Swedish, Tagalog, Tamil, Thai, Turkish, Ukrainian, Urdu, Vietnamese, and Welsh.

Other languages have moderate accuracy compared to these. I have tried this app for Malayalam, Telugu, Kannada, and Tamil. All these were accurately translated except for some anomalies in Telugu, Kannada, and Malayalam.

Apart from translation, we can also provide the transcription if needed so that the user can get the equivalent language script. (like An Audio to text converter)
