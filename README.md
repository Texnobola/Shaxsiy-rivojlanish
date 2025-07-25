# Shaxsiy-rivojlanish
Biz 
## 👨‍💻💻🧪 `Frontend dasturchilari` 🧪💻👩‍💻  
o'z skriptlarimizni maxsus sahifa yoki fayllarga yuklaymiz. Bunday holatlarda qanday brauzer ishlatish ham muhim ! ⛔ 	𝑱𝒂𝒗𝒂𝑺𝒄𝒓𝒊𝒑𝒕 kodlari ikki xil muhitda qo'llaniladi:
| Muhit nomi | Ma'lumot |
| --- | --- |
| Brauzer | Ochiq manbali hamda frontend foydalanuvchilarini uchun qulay va interaktiv muhit yaratib beruvchi platforma |
| Node.js | Asosan Backend dasturchilari uchun foydali. Bu dasturning maqsadi asosan ma'lumotlar bazasi rolini o'ynash |

Endi diqqatni bugungi kodga qarataman.🔏 𝑱𝒂𝒗𝒂𝑺𝒄𝒓𝒊𝒑𝒕 faylida

```javascript
alert("Salom dunyo");
```

Bu skript bizga mana bunday natija olib keladi ⬇⬇⬇




![Natija](https://i.ibb.co/dskTZHPF/image.png)


Bu kod 𝑯𝑻𝑴𝑳da

```html
<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>

  <script>
    alert( 'Hello, world!' );
  </script>

  <p>...After the script.</p>

</body>

</html>
```
>[!TIP]
>Skript tegini har xil turdagi attributlari 2000-yildan buyon unutilganlari ko'p.
>Misol keltirishimiz mumkin bo'lganlar:
>```html
><script type=text/javascript></script
><script language=></script>
><script><!--...//..></script>
><script type="text/javascript"><!--
>   ...
>//--></script>
>```

>[!NOTE]
>Hozir tepada ko'rgan kodlaringizni joriy holatda muomaladan chiqqan


#Fayllar manzili skript tegiga ushbu holatda kiritiladi: 
```html
<script src="/path/to/script.js"></script>
```

Hamda URL manzilini kiritish mumkin:
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.11/lodash.js"></script>
```

Yana shu bilan birgalikda bir nechta JavaScript fayllarini HTML fayliga ulash uchun ushbu holatda kirgizish kerak:
```html
<script src="/js/script1.js"></script>
<script src="/js/script2.js"></script>
```

>[!CAUTION]
>Oddiy skriptlarni HTMLdagi ```html <script> </script> ``` tegiga kirgizish maqulloq ! ⚠
>Ajratib yozilgan fayllarni ustunlik tomoni ularni yuklash va joylashtirish brauzerga osonroq. ✅
>HTML fayllari brauzer xotirasiga saqlanadi. Ammo JavaScript fayllari vaqtinchalik buyruqlarni amalga oshirish uchun qo'llaniladi.Bu oshiqcha traffikni sarflamaydi va saytni tezroq ishlashiga xissa qo'shadi.👌

>[!WARNING]
>Bir dona ```html <script> ``` tegiga ham **src** va ichiga kiritilgan buyruq amalga oshirilmaydi !!!
>```html
><script src="file.js">
>alert(1); // bu buyruq ishga tushmaydi, chunki src allaqachon kiritilgan
></script>
>```
>Buning o'rniga ***ikkita*** teg kiritish kerak !
>```html
><script src="file.js"></script>
><script>
>  alert(1);
></script>
>```

#Xulosa
- Biz ```html <script> ``` tegini JavaScriptni sahifaga ulash uchun ishlatamiz.
* Hozirda `type` va `language` attributi ishlatilmaydi.
+ Skript tegini ishlatib biron bir faylni manzilini kiritish orqali uni ulash mumkin, masalan `<script src="path/to/script.js"></script>` yoki `<script src="project.js"`

