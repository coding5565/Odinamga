# Faqat Sen Uchun: qo'llanma

Sayt 4 ekrandan iborat: maxfiy kod → lolalar va 6 ta gap → 3 ta sovg'a (rasmlar, qo'shiq, maktub) → "Biz birga N kun".

## 1. Rasmlar
`rasmlar/` papkasiga 6 ta rasm qo'ying: `1.webp` ... `6.webp` (jpg ham bo'ladi, faqat `SOZLAMALAR` dagi nom bilan bir xil bo'lsin).
- 1 va 2-rasm qulf ekranidagi yuraklarda ham chiqadi, 1-rasm plastinka o'rtasida ham.
- Kvadratga yaqin rasmlar chiroyli chiqadi.
- Har birini 500 KB dan kichik qiling (telefonda tez ochiladi).
- Nomi aynan bir xil bo'lsin: `1.JPG` va `1.jpg` internetda har xil hisoblanadi.

## 2. Qo'shiq
Qo'shiqni `qoshiq.mp3` nomi bilan shu papkaga (index.html yoniga) qo'ying.
Kod to'g'ri kiritilganda qo'shiq o'zi boshlanadi.

## 3. Matnlar
`index.html` ni istalgan muharrirda oching. Skript boshidagi `SOZLAMALAR` qismida:
- `ism`: uning ismi
- `imzo`: maktub oxiridagi ismingiz
- `kod`: maxfiy kod (masalan, tanishgan kun va oy: 14.02 → `1402`)
- `maslahat`: 2 marta xato kiritsa chiqadigan ishora
- `tanishganSana`: `YYYY-OO-KK` ko'rinishida, "birga N kun" shundan hisoblanadi
- `rasmlar`: har bir rasm tagidagi yozuv
- `qoshiq`: qo'shiq nomi va ijrochisi
- `gaplar`: lolalar atrofidagi 6 ta gap
- `maktub`: maktub matni (`{ism}` o'rniga ism qo'yiladi)

## 4. Tekshirish
`index.html` ni ikki marta bosing, brauzerda ochiladi.

## 5. Internetga joylash
Eng osoni: https://app.netlify.com/drop sahifasiga `sevgi_sayt` papkasini sudrab tashlang, havola beradi.
GitHub Pages yoki o'z domeningiz ham bo'ladi. Havola tayyor bo'lgach, undan yurakli QR kod yasash mumkin.
