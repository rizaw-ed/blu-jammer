🔧 Bluetooth Jammer using ESP32 and Dual NRF24L01 +PA+LNA

⚠️ For Educational and Testing Purposes Only
🧾 Bill of Materials:

    1x ESP32 Development Board

    2x NRF24L01 +PA+LNA Wireless Modules with Antenna

    2x 10uF 16V Electrolytic Capacitors

    Jumper Wires

    Breadboard or Solderable PCB

    USB Cable (for programming)

📘 Project Description:

This project demonstrates how to create a basic Bluetooth jammer using an ESP32 and two NRF24L01 +PA+LNA modules. The main purpose is to explore how 2.4GHz signal interference works and to gain hands-on experience with RF module communication and signal flooding techniques.

This jammer works by sending a large number of packets across the 2.4 GHz band, overlapping with frequencies used by Bluetooth devices, effectively reducing their ability to communicate.

⚠️ Important: This project is for educational and lab use only. Using this jammer outside of a controlled environment may be illegal and is not encouraged.
⚙️ Wiring and Connections:

Connect the two NRF24L01 modules to the ESP32 as follows:
| NRF1 Pin | ESP32 Pin |
| ------------ | --------- |
| CE           | D4        |
| CSN          | D15       |
| SCK          | D14       |
| MOSI         | D13       |
| MISO         | D12       |

| NRF2 Pin | ESP32 Pin |
| ------------ | --------- |
| CE           | D22       |
| CSN          | D21       |
| SCK          | D18       |
| MOSI         | D23       |
| MISO         | D19       |

⚠️ Note: Add a 10µF capacitor between VCC and GND on each NRF24L01 module to improve stability

====================================================

🔧 پروژه جمر بلوتوث با ESP32 و دو ماژول NRF24L01 +PA+LNA

⚠️ فقط برای اهداف آموزشی و تست در محیط آزمایشگاهی
🧾 لیست قطعات مورد نیاز:

    ۱ عدد برد توسعه ESP32

    ۲ عدد ماژول بی‌سیم NRF24L01 +PA+LNA دارای آنتن

    ۲ عدد خازن الکترولیتی ۱۰ میکروفاراد ۱۶ ولت

    سیم‌های اتصال (جامپر)

    بردبرد یا PCB سوراخ‌دار برای لحیم‌کاری

    کابل USB برای برنامه‌ریزی برد

📘 توضیح پروژه:

این پروژه نحوه ساخت یک پارازیت‌انداز (جمر) ساده بلوتوث با استفاده از یک برد ESP32 و دو ماژول NRF24L01 +PA+LNA را نمایش می‌دهد. هدف اصلی، یادگیری نحوه ایجاد تداخل در باند ۲.۴ گیگاهرتز و آشنایی عملی با ماژول‌های RF و روش‌های ارسال پکت‌های مزاحم در این فرکانس است.

این جمر با ارسال تعداد زیادی پکت در کانال‌های مختلف باند ۲.۴ گیگاهرتز باعث می‌شود دستگاه‌های بلوتوث در برقراری ارتباط دچار مشکل شوند یا اصلاً نتوانند متصل شوند.

⚠️ توجه مهم: این پروژه فقط برای آموزش و استفاده در محیط آزمایشگاهی کنترل‌شده طراحی شده است. استفاده از آن در محیط‌های عمومی ممکن است غیرقانونی باشد و به هیچ عنوان توصیه نمی‌شود.
⚙️ اتصالات و سیم‌کشی:

اتصالات دو ماژول NRF24L01 به برد ESP32 به شکل زیر انجام می‌گیرد:
| NRF1 Pin | ESP32 Pin |
| ------------ | --------- |
| CE           | D4        |
| CSN          | D15       |
| SCK          | D14       |
| MOSI         | D13       |
| MISO         | D12       |

| NRF2 Pin | ESP32 Pin |
| ------------ | --------- |
| CE           | D22       |
| CSN          | D21       |
| SCK          | D18       |
| MOSI         | D23       |
| MISO         | D19       |

⚠️ نکته: برای پایداری ولتاژ ماژول‌ها، یک خازن ۱۰ میکروفاراد بین پایه‌های VCC و GND هر ماژول NRF24L01 قرار دهید.
⚠️ نکته: برای پایداری ولتاژ ماژول‌ها، یک خازن ۱۰ میکروفاراد بین پایه‌های VCC و GND هر ماژول NRF24L01 قرار دهید.
