<h2><b>Python  programmer</b></h2>  
![Лебедев Сергей](https://sun9-32.userapi.com/impf/c857428/v857428993/b3844/BxoweOf1SMA.jpg?size=2560x1751&quality=96&sign=76937bcdecd802cc7b9dda2b8cef6988&type=album){ width=300px }  
 


I created this website on Python library for generate static sites - **mkdocs**.  
Documentation: [mkdocs.org](https://www.mkdocs.org){target=_blank}.  
  
<hr>  
# <h1 align="center">**About me**</h1>  
Hello! My name is Lebedev Sergey, i'm 36 years old.  
My original hobby, Python, has become my whole life.  
**Go to programming**  
Most of my life i worked in the largest it-projects in Russia (avito.ru, prom.ua, greeder.lv), but not as programmer. i was manager.  
Fiveyears ago i started integrating CRM (and ERP) systems [Bitrix24](https://www.bitrix24.ru){target=_blank} for companies.  
As part of this activity, i started writing code for integrating Bitrix24 and other systems (sites, ip-tel, google-tables).  
And parsers. Many different parsers. Requests and bs4 for simple sites. Selenium and bs4 for sites where js is needed and which have protection against parsing.  
**Programming full time**  
In the past year, i've been writing code for a company that uploads products to popular message boards.   
**My strengths**  
I have extensive experience in communicating with customers, describing business processes and automating them in crm or using code.  
I love beautiful code. But i understand and accept when you need to do it quickly.  
**languages**  
![languages](https://sun9-43.userapi.com/impg/3TDcHgOzuwJ0eQsnG42s31RGTDf2eJxB06sVlg/afx3BixZFcw.jpg?size=800x400&quality=95&sign=ca9469bc47932d4175bcb5611deffcad&type=album){ width=600px }  
**Russian** - native language  
**English** - good technical Eng (reading books and notes on programming without a dictionary), but no speaking practice  
**Ivrit** - a few days ago I started to study it  

<hr>
# <h1 align="center">**Examps of my projects**</h1>  
<hr width="50%">  
## 1. Program for load adds to [avito.ru](https://avito.ru){target=_blank}, [tiu.ru](https://tiu.ru){target=_blank}, [jazi.ru](https://jazi.ru){target=_blank}  
(Avito is bigest Russian marketplace focused on small resellers)  
The program can:  
1-1. Get xml of any subspecies from clients  
**Technology stack**: xml.etree.ElementTree,bs4,codecs,urllib.request  
1-2. Automatically upload data to Google Spreadsheets with data changes on the fly (recognition of categories, editing the name, description, cost and other parameters)  
**Technology stack**: google.oauth2, googleapiclient  
After realize module i understand, that google api have limit of querry. And later we make several api accaunts and switch between it.  
1-3. Create xml tables of your own format from Google for each site  
**Technology stack**: pandas, gspread, gspread_dataframe  
1-4. Generate and overlay text on the photo from product parameters on the fly  
**Technology stack**: cv2, numpy, PIL  
1-5. Change the aspect ratio in the photo on the fly  
**Technology stack**: PIL  
1-6. Overlay other pictures on the main photo on the fly  
**Technology stack**: PIL  
1-7. Auto change background of image  
**Technology stack**: PIL, cv2  
1-8. Load and read ftp. Different ftp for dif clients  
**Technology stack**: ftplib, io  
1-9. Change size of photo and make collages from photo (еo bypass blocking)  
**Technology stack**: PIL  

**Summary**  
This project was originally made for a small automation of one client.  
But it constantly grew and became the software thanks to which the company  
works with hundreds of customers.  
Architecture is constantly changing. And there was no time to bring it into perfect order.  
Most of the rework tasks were very urgent.  
And there was no time to streamline the code. New developments have always been a priority.  
However, I managed to keep the code readable and maintainable for other developers,  
despite the fact that this was my first such a large and continuous project without allocating time for optimization.  
<hr width="50%">  
## 2. Analysis of the issuance of [avito.ru](https://avito.ru){target=_blank}  
[GitHub code](https://github.com/ezjikfrom/avito_analysis){target=_blank}  
I can show this code because i made it for myself  
This analize Avito by querry and write result in google sheet.  
It help make more effective adds in avito.  
**Technology stack**: openpyxl, requests, bs4, pandas, gspread, gspread_dataframe, fake_useragent  
<hr width="50%">  
## 3. Parsers  
Many various parsers. Example you can see in №2 (Analysis avito).  
**Technology stack**: openpyxl, requests, bs4, pandas, gspread, gspread_dataframe,  
fake_useragent, selenium chrome and moziilla (if we need js and imitate ordinary user)  
<hr width="50%">  
## 4. Telegram bot which allows you to respond to customers from message [avito.ru](https://avito.ru){target=_blank}  
In this project i use simple server flask and sqlite.  
Unfortunately, in my work, databases were very rarely needed,  
because Google Sheets was an ideal repository with the ability  
to edit data by users. This made it possible not to develop a  
separate interface for working with data.  
  
In this block i had big problems with avito api -  
avito make it recently and it not always work (this made testing very difficult).  
I met many mistakes, what not described in the documentation avito api.  
**Technology stack**: requests, json, flask, sqlite3, telethon (telegram client)  
Early, 2-3 years ago i make about several 10 bots for telegram with keyboards and useful functionality  
<hr width="50%">  
## 5. API integration in [Bitrix24](https://www.bitrix24.ru){target=_blank} and [Amocrm](https://www.amocrm.ru/){target=_blank}  
5-1. And load data to google sheets, to make  
deeply customizable individual reports for business  
5-2. Take all data to migrate in other crm/erp (usually from amo to b24)  
5-3. Integrate with customs sites  
5-4. Integrate with external api telephony (only info about calls, not calls)  
5-5. Complex automations inside crm that are not available in standard functionality  
**Technology stack**: pandas, gspread, gspread_dataframe, requests, json  
  
<hr>
# <h1 align="center">**What am I looking for**</h1>  
<hr width="50%"> 
- Work as a developer and career growth in an Israeli company  
- The opportunity to develop as a developer and improve my level  
- Opportunity to work remotely in the next month and move on a work visa to Israel in 2-3 months   
<hr>
# <h1 align="center">**Contacts**</h1>  
<hr width="50%"> 
**Whatsapp, telegram**: +7-999-536-64-84  
**E-mail**: lebedev6484@gmail.com  

It's best to write to Whatsapp