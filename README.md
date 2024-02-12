- 👋 Hi, I’m @Bhctlh
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Bhctlh/Bhctlh is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->hi
from nltk.chat.util import Chat, reflections
pairs = [
    [
        r"merhaba|selam|hey",
        ["Merhaba! Nasıl yardımcı olabilirim?", "Merhaba, size nasıl yardımcı olabilirim?"]
    ],
    [
        r"ben (.*) ismim",
        ["Merhaba %1, nasıl yardımcı olabilirim?",]
    ],
    [
        r"nasılsın|naber",
        ["İyi, teşekkürler! Siz nasılsınız?", "Ben bir chatbot'um, teşekkürler!",]
    ],
    [
        r"(güle güle|hoşça kal)",
        ["Güle güle! Tekrar görüşmek üzere!", "Hoşça kal!",]
    ],
]
def chatbot():
    print("Bot: Merhaba! Ben bir chatbot'um. Çıkmak için 'güle güle' veya 'hoşça kal' yazabilirsiniz.")
    chat = Chat(pairs, reflections)
    chat.converse()
    if __Bhctlh__ == "__main__":
    chatbot()
    nasılsın
    merhaba
    
