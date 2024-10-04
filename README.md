- 👋 Hi, I’m @hoanganhkiet27
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
hoanganhkiet27/hoanganhkiet27 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# ~ By Kiet2024
# ～ Egern transfer to Shadowrocket & Surge & LanceX
revenuecat = type=http-response, pattern=^https:\/\/api\.revenuecat\.com\/.+\/(receipts$|subscribers\/[^/]+$), script-path=https://raw.githubusercontent.com/vuong2023/shad/main/js/Locket_Ohoang7.js, requires-body=true, max-size=-1, timeout=60

deleteHeader = type=http-request, pattern=^https:\/\/api\.revenuecat\.com\/.+\/(receipts|subscribers), script-path=https://raw.githubusercontent.com/vuong2023/shad/main/js/deleteHeader.js, timeout=60

[MITM]
hostname = %APPEND% api.revenuecat.com
