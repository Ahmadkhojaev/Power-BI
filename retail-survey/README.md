# Retail Mobil Dastur — Adaptiv Discovery So'rovnomasi

Retail sohasidagi mijoz bilan PM uchrashuvida foydalanish uchun interaktiv so'rovnoma.
Mijozning nima qildirmoqchiligini (maqsad, foydalanuvchilar, funksiyalar, integratsiyalar)
aniqlash uchun mo'ljallangan.

## Ishga tushirish

`index.html` faylini brauzerda oching (qo'shimcha hech narsa o'rnatish shart emas).

- GitHub'da: faylni oching → **Raw** → **Save as** → kompyuteringizda ochib ishlating.

## Asosiy imkoniyatlar

- **Adaptiv (shartli) savollar** — soha tanlanganda faqat o'sha sohaga oid savollar ochiladi
  (oziq-ovqat, kiyim-kechak, elektronika, dorixona, mebel, qurilish).
- **Ikki darajali tarmoqlanish** — masalan: oziq-ovqat → "tez buziladigan" → sovuq zanjir savoli.
- **Avtomatik tavsiya bloki** — javoblarga qarab tavsiya etilgan modullar ro'yxati
  (masalan: "Ombor moduli", "Loyalty", "1C integratsiyasi").
- **Progress bar** — faqat tegishli (ko'rinadigan) savollarni hisoblaydi.
- **Avtomatik saqlash** — javoblar brauzerda (localStorage) saqlanadi.
- **Eksport** — javoblar va tavsiyalarni Markdown (.md) yoki JSON ko'rinishida yuklab olish,
  hamda PDF / chop etish.

## Tuzilma

| Bo'lim | Tavsif |
|--------|--------|
| Kompaniya va biznes konteksti | Soha, filiallar, hodimlar, savdo kanallari |
| Sohaga oid maxsus talablar | Tanlangan sohaga qarab ochiladi |
| Loyiha maqsadi va muammolar | Maqsad, og'riqli nuqtalar, KPI |
| Foydalanuvchilar | B2C / B2E / B2B |
| Funksionallik (mijoz / hodim) | Tanlovga qarab ochiladi |
| Integratsiyalar | 1C, POS, to'lov tizimlari |
| Texnik talablar | Platforma, til, oflayn |
| Dizayn va brending | Ko'rinish |
| Byudjet, muddat, jamoa | Rejalashtirish |
