# tts-experimental
text to speech with cogintive service and integrate with AI (Chat GPT)

```bash
curl --location --request POST "https://southeastasia.tts.speech.microsoft.com/cognitiveservices/v1" \
--header "Ocp-Apim-Subscription-Key: 1ed5c237ae0144939db4a147a9axxxxx" \
--header 'Content-Type: application/ssml+xml' \
--header 'X-Microsoft-OutputFormat: audio-16khz-128kbitrate-mono-mp3' \
--header 'User-Agent: curl' \
--data-raw '<speak version='\''1.0'\'' xml:lang='\''en-US'\''>
    <voice xml:lang='\''en-US'\'' xml:gender='\''Female'\'' name='\''en-US-AnaNeural'\''>
        my voice is my passport verify me
    </voice>
</speak>' > output.mp3
```
