बच्चा Screen Time — Android starter project

फीचर:
- YouTube ऐप foreground में लगातार 20 मिनट रहने पर स्क्रीन चेतावनी और हिंदी TTS आवाज़।
- टाइमर YouTube से बाहर आने पर reset होता है।
- केवल चेतावनी देता है; ऐप/फोन को लॉक नहीं करता।

महत्वपूर्ण सीमाएँ:
- Android Usage Access से YouTube ऐप का समय पता चलता है, Shorts और सामान्य YouTube वीडियो में फर्क नहीं किया जा सकता।
- महिला आवाज़ फोन के Text-to-Speech इंजन और उपलब्ध Hindi voice पर निर्भर है। यदि महिला Hindi voice उपलब्ध न हो, तो सिस्टम की default Hindi voice चलेगी।
- Android बैटरी/बैकग्राउंड प्रतिबंधों के कारण कुछ फोन में सेवा रुक सकती है। इस प्रोजेक्ट को वास्तविक फोन पर टेस्ट करना जरूरी है।
- ऐप चालू रखने के लिए Main screen में Usage Access और Display over other apps अनुमति दें, फिर निगरानी शुरू करें।
- यह source project है, तैयार APK नहीं। APK बनाने के लिए Android Studio में खोलें और Build > Build APK(s) चुनें।
