# FreeRTOS_Config
Config for stm32f103c8

پاسخ : راه حل پرش نکردن برنامه به task ها در freeRTOS

مشکل  نرفتن برنامه به توابع بود
دوستانی که ممکنه درگیر این مشکل بشین، دلیلش تنظیمات فایل FreeRTOSConfig.h است که  نمونه فایل کانفیگ را برای میکروکنترلر stm32f103c8 که به صورت عملی جواب می دهد را گذاشتم.
مسیر فایل در برنامه هم:
.\Core\Inc

نکته****  :    هر موقع که برنامه را توسط stm32cubemx تغییر دادید و آپدیت کردید فراموش نکنید که این فایل را حتما مجدد جایگزین کنید.
