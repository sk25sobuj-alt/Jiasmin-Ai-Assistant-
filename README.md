# Jiasmin Ai Assistant — Android App (GitHub diye APK banano)

Neon theme er AI voice + text chat assistant app. Nijer API key diye chalao.

## Ki ki ache
- 💬 Neon dark theme chat (pink/blue neon bubble, timestamp, ✓✓ tick)
- 🎙️ Mic button — mukhe bole message pathano
- 🔊 Voice reply — Gemini cloud voice (Kore, Puck, Charon…) ba phone er default voice
- ⚙️ Settings e 3 ta API key: **Gemini**, **OpenRouter**, **SerpAPI**
- 🧠 Personality picker (GirlFriend, Boss, Teacher, Savage Girl, Custom…)
- 🌐 Language picker — ~30 ta bhasha (default **Bengali**): reply, voice output, ar mic input — tintitei select kora bhasha kaj kore
- 🔍 Web Search toggle — SerpAPI diye fresh info ene AI ke dibe
- 🔐 Permissions section — mic, camera, location, notification, overlay, screen capture
- 🔛 API On/Off toggle — Gemini, OpenRouter, SerpAPI alada kore on/off kora jay
- 😺 Avatar picker — AI er avatar emoji choose koro (🤖 👩 🧑‍🚀 🐱 🦊 🐼 👾 💜), chat e sathe sathe bodle jay

## API key kothay pabe

1. **Gemini API key (FREE)** — [aistudio.google.com](https://aistudio.google.com) → Google account diye login → "Get API key" → "Create API key" → copy kore app er Settings → Gemini API Key te boshao → Save.
2. **OpenRouter API key** — [openrouter.ai/keys](https://openrouter.ai/keys) → account khulo → "Create API Key". Free model o ache (naam er seshe `:free` thaka model, jemon `deepseek/deepseek-chat-v3-0324:free`). Key + model name Settings e boshao.
3. **SerpAPI key** — [serpapi.com](https://serpapi.com) → sign up → free trial plan e key pabe. Web Search toggle er jonno lagbe.

## Provider select
Settings → **AI Provider** theke `Gemini (free)` ba `OpenRouter` select koro. Jar key boshaicho, shetai select koro.

## API On/Off
Settings → **API On/Off** theke Gemini, OpenRouter, SerpAPI — tintikei alada alada on/off kora jay. Bondho thaka ba key chara provider select kore message pathale toast dekhabe, request jabe na.

## Avatar
Settings → **Avatar** te tap kore AI er avatar emoji bodlao (🤖 👩 🧑‍🚀 🐱 🦊 🐼 👾 💜 — default 🤖). Chat header ar shob AI message e sathe sathe change hobe.

## Web Search
Settings → **Web Search (SerpAPI)** ON korle protibar message pathanor age web search kore top 5 result AI ke pathabe — fresh/news info pabe. SerpAPI key chara eta kaj korbe na; search fail korle normal reply ashbe.

## Personality
Settings → **Personality** te tap kore AI er style bodlao: GirlFriend, Boss, Teacher, Soft Romantic Listener, Hyper Energetic, Caring Neon AI, Savage Girl, Mystical, Unknown, Manipulative, MT Assistant, ba **Custom** (nijer description likho).

## Voice
Settings → **Voice** te tap kore voice bodlao:
- Gemini cloud voice (Kore, Achernar, Aoede, Puck, Charon, Fenrir… — default **Kore**): sundor natural voice, kintu **Gemini API key lagbe**.
- **Phone Default (Device TTS)**: phone er nijer voice engine use korbe, kono key lagena.
- Gemini voice fail korle auto phone er voice e chole jabe.

## Language
Settings → **Language** theke bhasha select koro (default **Bengali**) — shobcheye upore ekta **🌐 All Languages (Auto)** button ache: eta select korle AI user jei bhashay kotha bolbe shei bhashayi uttor dibe (shob bhasha bujhte parbe). Niche baki ~30 ta bhasha: Hinglish, English, Hindi, Bengali, Telugu, Rajasthani, Marathi, Tamil, Urdu, Gujarati, Kannada, Malayalam, Odia, Punjabi, Arabic, French, German, Spanish, Portuguese, Russian, Chinese (Simplified), Japanese, Korean, Turkish, Vietnamese, Thai, Indonesian, Italian, Dutch, Persian.

Select kora bhasha tin jaygay kaj kore:
- **AI reply** — oi bhashay uttor dibe
- **Voice output** — phone oi bhashar TTS support korle shei bhashay bolbe
- **Mic input** — mukhe oi bhashay bolle bujhte parbe

## Permissions
Settings er niche **Permissions** section e shob permission er status dekha jay (Granted / Tap to Allow):
- **GRANT ALL PERMISSIONS** — ekbare shob runtime permission chabe
- Default Assistant — phone er voice assistant settings khulbe (nije "Action Required" theke change korte hobe)
- Microphone, Camera, Precise Location, Post Notifications, Display Over Other Apps, Screen Capture — row te tap korlei permission chabe

## APK bananor steps (phone e Android Studio lagbe na)

### 1. GitHub e notun repo banao
- github.com e jao → **New repository**
- Naam dao: `zara-clone-app` (ba jekono naam), **Public** rakho → **Create repository**

### 2. Ei folder er shob file push koro
Terminal e ei folder er vitore giye:

```bash
git init
git add .
git commit -m "AI Assistant app"
git branch -M main
git remote add origin https://github.com/TOMAR-USERNAME/zara-clone-app.git
git push -u origin main
```
(TOMAR-USERNAME er jaygay tomar GitHub username boshao)

### 3. Actions tab e workflow run hobe
- Repo te **Actions** tab e jao
- `Build Debug APK` workflow nije nije run hobe (2-4 minute lagte pare)
- Sobuj tick ✅ asle build sesh

### 4. Artifacts theke APK download koro
- Oi run er vitore niche **Artifacts** section e `Jiasmin-Ai-Assistant-apk` paba
- Download koro → zip file kholo → vitore `Jiasmin-Ai-Assistant.apk`

### 5. Phone e install koro
- APK file ta phone e pathao (WhatsApp/Drive/USB diye)
- Phone e tap kore install koro (prothombar "unknown sources" allow korte hote pare)

### 6. API key boshao
- Upore bola jayga theke key niye app er Settings e boshao → Save
- Provider select koro → Chat e giye kotha bolo! 🎉

## Note
- API key chara chat kaj korbe na — age Settings e key boshao.
- Key gulo karor sathe share koro na, ar GitHub e push korar age key Settings e save kore rakha thakleo repo te key jay na (key shudhu phone er vitore save thake).
