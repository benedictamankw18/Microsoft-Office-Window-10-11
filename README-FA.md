# فعال‌سازی سریع ویندوز ۱۰ و ۱۱: راه‌حلی ۴۰ ثانیه‌ای

[![Readme](https://img.shields.io/badge/README_IN-فارسی-blue?logo=readme)](README-FA.md)  
[![Readme](https://img.shields.io/badge/README_IN-ENGLISH-blue?logo=readme)](README.md)  

> این مخزن شامل روشی است که می‌تواند ویندوز ۱۰ و ۱۱ را در کمتر از ۴۰ ثانیه فعال کند. هر دو روش با نسخه‌هایHome، Home N، Home Single Language، Home Country Specific، Professional، Education و Enterprise ویندوز سازگار هستند.  
> 

## روش اول (پیشنهادی)  
**فعال‌سازی سریع ویندوز با استفاده از PowerShell** 

> [!TIP]
> روش‌های زیادی برای اجرای PowerShell در ویندوز ۱۰ و ۱۱ وجود دارد. [^1].  

یکی از سریع‌ترین روش‌ها برای باز کردن PowerShell در ویندوز، از طریق آیکون جستجو و منوی استارت است. مراحل زیر را دنبال کنید:

<br>

### مرحله ۱  
کافی است بر روی آیکون استارت یا کادر جستجو کلیک کنید و "PowerShell" را داخل کادر تایپ کنید.  
> راه آسان دیگر: [^2].   

<p align="right">
  <br><img src="https://github.com/user-attachments/assets/5a10538a-c8c2-4934-868b-fd8e910f1f9e" width="540px">
</p> 

---  
<br>

### مرحله ۲  
سپس، باید روی `Run as Administrator` کلیک کنید تا پاورشل با **مجوزهای مدیر** اجرا شود.  

<p align="right">
  <br><img src="https://github.com/user-attachments/assets/1f25dd2a-16db-4053-a45c-aac6f8a9e470" width="540px">
</p>  

---  
<br>

### مرحله ۳  
اکنون، پس از یک مکث کوتاه برای لود شدن پاورشل، لطفاً لاین زیر را `کپی` کنید:

```CSS
irm https://get.activated.win | iex
```

---  
<br>

### مرحله ۴  
حالا آن را (با راست کلیک) درون پاورشل جای‌گذاری کنید و به منظور تایید کلید اینتر را بزنید. در پنجره‌ی تازه باز شده، چندین گزینه موجود است که باید گزینه `1` را تایپ و اینتر زده و چند ثانیه صبر کنید تا پروسه فعالسازی کامل شود.  

<p align="right">
  <br><img src="https://github.com/user-attachments/assets/0c3689a1-1595-40b3-97e2-041dac423237" width="540px">
</p>  

---  
<br>

#### تبریک میگم،  
ویندوز شما فعال شد. اکنون می‌توانید با فشردن کلید اینتر پنجره CMD را ببندید و همچنین پاورشل را بسته و وضعیت فعال بودن ویندوز را از منوی تنظیمات بررسی کنید [^3].  

<br><br><br><br><br><br><br><br>

## روش دوم  
### فعال‌سازی سریع ویندوز با استفاده از CMD (خط فرمان)  

> [!NOTE]
> اتصال صحیح سیستم به **اینترنت** را بررسی کنید.
> 
> فعال کردن VPN **ضروری نیست.**  

<br>

## مرحله ۱  
کافی است بر روی آیکون استارت یا کادر جستجو کلیک کنید و "CMD" را داخل کادر تایپ کنید.  
و پس از مشاهده گزینه `Command Prompet` آن را با حالت **Run as administrator** اجرا کنید.  
> راه آسان دیگر: [^2].  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/88ac970a-f24b-4acc-82c0-f8e7c0b05249" width="480px">
</p>  

---  
<br>

### لیست کلیدهای لایسنس

|            **کلید**            |   **نسخه**  |
|:-----------------------------:|:--------------:|
| TX9XD-98N7V-6WMQ6-BX7FG-H8Q99 |      Home      |
| 3KHY7-WNT83-DGQKR-F7HPR-844BM |     Home N     |
| 7HNRX-D7KGG-3K4RQ-4WPJ4-YTDFH |  Home sl [^4]  |
| PVMJN-6DFY6–9CCP6–7BKTT-D3WVR |  Home cs [^5]  |
| W269N-WFGWX-YVC9B-4J6C9-T83GX |  Professional  |
| MH37W-N47XK-V7XM9-C7227-GCQG9 | Professional N |
| NW6C2-QMPVW-D7KKK-3GKT6-VCFB2 |   Education    |
| 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ |   Education N  |
| NPPR9-FWDCX-D2C8J-H872K-2YT43 |   Enterprise   |
| DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4 |  Enterprise N  |

![rainbow](https://github.com/NiREvil/vless/assets/126243832/1aca7f5d-6495-44b7-aced-072bae52f256)  

<br>

### مرحله ۲  
نصب کلید مشتری KMS  
از دستور زیر استفاده کنید:  

```CSS
slmgr /ipk yourlicensekey
```

---  
<br>

> [!NOTE] 
> لطفاً یکی از **کلیدهای لایسنس** را که با **نسخه ویندوز شما مطابقت دارد** از لیست انتخاب کرده و آن را با عبارت `yourlicencekey` در دستور فوق جایگزین کنید.  

> [!TIP] 
> چگونه نسخه ویندوز خود را بررسی کنم [^3]  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/1b6401e6-7e63-4351-8a92-fa355dfc30cf" width="480px">
</p>  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/90037069-7ea3-44a8-a9fa-e296f5e8d47b" width="340px">
</p>  

---  
<br>

### مرحله ۳  
تنظیم آدرس ماشین KMS  
از این دستور استفاده کنید:  
```CSS
slmgr /skms kms8.msguides.com
```

برای اتصال به سرور KMS من   

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/9d634454-1c59-47da-874e-bfe575288fe6" width="480px">
</p>  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/2d2e6cfb-4e85-483f-ae0a-c7157d22da36" width="340px">
</p>  

---  
<br>

### مرحله ۴  
ویندوز خود را فعال کنید.  
آخرین مرحله این است که ویندوز خود را با استفاده از دستور زیر فعال کنید:  

```CSS
slmgr /ato
```  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/5e495d42-6ce5-4884-9de2-96a56efb4343" width="480px">
</p>  

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/aecd9cfd-8c09-4433-b410-a62205a8d692" width="240px">
</p>  

---  
<br>

### مرحله ۵  
اکنون وضعیت فعال‌ بودن ویندوز را دوباره بررسی کنید [^6]

<p align="left">
  <br><img src="https://github.com/user-attachments/assets/9ca70137-8e2e-4504-a52d-22f41d959bd7" width="480px">
</p>

#### تمام ✅ 
اگر اعلانی مشابه تصویر فوق مشاهده کردید ویندوز شما با موفقیت فعال شده است.
در صورت دریافت هرگونه خطا ابتدا اتصال صحیح اینترنت را بررسی کرده سپس مراحل را تکرار کنید.

<br>

**کنجکاو باشید 🤍**  
 
[![Telegram](https://img.shields.io/badge/TELEGRAM-blue.svg?logo=telegram)](https://t.me/F_NiREvil)    [![Twitter](https://img.shields.io/badge/TWITTER-blue.svg?logo=x)](https://twitter.com/NiREvil_)  


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png"></picture>
   
<br>

[^1]: [10 روش برای اجرای پاورشل در ویندوز](https://www.google.com/amp/s/www.minitool.com/news/open-windows-11-powershell.html%3famp)  

[^2]: راه آسان دیگر برای اجرای پاورشل: **کلیک راست** روی منوی استارت برای باز کردن منوی سریع و انتخاب **Windows Terminal (admin)** در ویندوز ۱۱ یا **Windows PowerShell (admin)** در ویندوز ۱۰ از لیست منو.  

[^3]: برای بررسی نسخه ویندوز خود: **کلیک راست** روی منوی استارت و انتخاب گزینه **System**. نسخه ویندوز شما در بخش دوم صفحه قابل مشاهده است. تمامی دسورات را می‌توانید با عمل **Copy و paste** دنبال کنید. دستورات را کپی کرده و سپس داخل **CMD یا پاورشل** با عمل **کلیک راست** جای‌گذاری کنید.  
[^4]: نسخه Home Single Language.

[^5]: نسخه Home Country Specific.

[^6]: برای مشاهده وضعیت فعال‌/غیرفعال بودن ویندوز به این مسیر بروید:  
***Settings → Update & Security → activation menu***
