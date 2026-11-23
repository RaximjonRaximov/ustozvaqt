# UstozVaqt reja va dizayn

## Muammo va arxitektura
Repetitor tanlash va bo‘sh vaqtni kelishish tarqoq e’lonlar orqali amalga oshadi. `server.js` statik frontend va REST API beradi. `tutors`, `subjects`, `bookings` JSON kolleksiyalari saqlanadi. Booking yaratishda ustoz+sana+vaqt kombinatsiyasi tekshiriladi; admin endpointlari `x-admin-key` role boundary bilan yopilgan.

## Dizayn
Variantlar: “study studio” (0.07), “quiet classroom” (0.05), “editorial tutor” (0.08). Tanlov: **editorial tutor**. Dizayn ishonchli tanlovni osonlashtiradi: ko‘k-yashil rang bilim va xotirjamlikni, sariq CTA esa darsga qadamni bildiradi. Layout avval katta positioning sarlavhasi, keyin filtr paneli va ustoz kartalaridan iborat. Signature elementlar — `◒` wordmark, aylanma `01` tamg‘a, boshlang‘ich harfli avatarlar. Manrope va DM Mono ishlatiladi. Brend ovozi: “Sizga mos ustoz, qulay vaqtda.”

## Tuzilma
`server.js` backend, `public/` frontend, `data/ustozvaqt.json` persistent data, `test.js` smoke tests, `docs/architecture.svg` vizual hujjat, `.env.example` konfiguratsiya.
