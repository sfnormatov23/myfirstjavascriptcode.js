<Sirojiddin, ofarin\! Savollaringizdan ko'rinib turibdiki, siz allaqachon **"User Experience"** (foydalanuvchi uchun qulaylik) haqida o'ylay boshladingiz. Bu professional dasturchi va olimlar uchun juda muhim hislat.

Siz aytgan narsani amalga oshirishning **3 ta eng zo'r usuli** bor. Bular loyihangizni juda tartibli va "shirin" ko'rsatadi:

-----

### 1-usul: Rasmni "Silka" (Link) qilish

Siz aytganingizdek: rasm turadi, odam rasmni bossa, u sizning uzun kodingiz yozilgan faylga o'tib ketadi.

**README.md ichiga mana buni yozing:**
`[![Natija](LULc%202020t.jpg)](my_first_js_code.js)`

  * **Bu nima degani?** Birinchi qavsdagi `LULc%202020t.jpg` — bu ko'rinib turadigan rasm. Ikkinchi qavsdagi `my_first_js_code.js` — bu rasm bosilganda ochiladigan kod fayli.

### 2-usul: "Spoiler" (Yashirin blok) qilish

Agar kodni README ichida qoldirmoqchi bo'lsangiz, lekin u uzooooon joyni egallashini xohlamasangiz, uni **yashirib qo'yish** mumkin. Odam "Kodlarni ko'rish" degan yozuvni bossagina kod ochiladi.

**README.md ichiga mana buni yozing:**

````markdown
<details>
  <summary>💻 Bu yerni bosing (Kodlarni ko'rish uchun)</summary>

  ```javascript
  // Bu yerda sizning 200 qatorli kodingiz turadi
  console.log("Juda uzun kod...");
  // ...
````

\</details\>

```
*   **Natija:** README&#39;da faqat bitta qator yozuv turadi. Uni bossangiz, kod pastga qarab &quot;yoyiladi&quot;. Bu juda professional usul!

### 3-usul: Oddiy Link (Silka) berish

Rasmdan tashqari, matn ko'rinishida ham link bersangiz bo'ladi.

**README.md ichiga:**
`Bu tahlilni amalga oshirish uchun yozilgan kodni [bu yerda](my_first_js_code.js) ko'rishingiz mumkin.`

-----

### Qaysi birini tavsiya qilaman?

Agar siz **top olim** bo'lmoqchi bo'lsangiz, **1-usul va 2-usulni birga** ishlating.

1.  README'da chiroyli rasm tursin.
2.  Tagida "Kodlarni ko'rish" degan yashirin blok (2-usul) bo'lsin.

**Sirojiddin, sizga bitta muhim "sir"ni ochaman:**
Chet eldagi professorlar sizning hamma kodingizni boshidan oxirigacha o'qib chiqishga vaqti bo'lmaydi. Ular:

  * Xarita (Rasm)ga qaraydi.
  * Xulosangizga qaraydi.
  * Kod borligiga va u tartibli ekanligiga ishonch hosil qiladi.

Shuning uchun README'ni rasm va qisqa tushuntirishlar bilan boyitib, kodni "yashirin blok" yoki "alohida fayl" qilib qo'ysangiz — bu **100 ballik natija** bo'ladi.

Hozir o'sha yashirin blokni (2-usulni) README'da sinab ko'ring-chi? O'sha "💻 Bu yerni bosing" degan yozuv chiqdimi?
```>
  <summary>💻 Bu yerni bosing (Kodlarni ko'rish uchun)</summary>

