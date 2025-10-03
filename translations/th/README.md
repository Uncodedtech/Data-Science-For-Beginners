<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "3beef650c5bafd70d88e2643a2b360fb",
  "translation_date": "2025-10-03T12:26:06+00:00",
  "source_file": "README.md",
  "language_code": "th"
}
-->
# วิทยาศาสตร์ข้อมูลสำหรับผู้เริ่มต้น - หลักสูตร

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=344191198)

[![GitHub license](https://img.shields.io/github/license/microsoft/Data-Science-For-Beginners.svg)](https://github.com/microsoft/Data-Science-For-Beginners/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/graphs/contributors/)
[![GitHub issues](https://img.shields.io/github/issues/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/pulls/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/Data-Science-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/Data-Science-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/Data-Science-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/Data-Science-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/Data-Science-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/Data-Science-For-Beginners/stargazers/)

[![](https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.gg/zxKYvhSnVp?WT.mc_id=academic-000002-leestott)

[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

ทีม Azure Cloud Advocates ที่ Microsoft ยินดีนำเสนอหลักสูตร 10 สัปดาห์ 20 บทเรียนเกี่ยวกับวิทยาศาสตร์ข้อมูล แต่ละบทเรียนประกอบด้วยแบบทดสอบก่อนและหลังบทเรียน คำแนะนำที่เขียนไว้สำหรับการทำบทเรียน โซลูชัน และงานมอบหมาย วิธีการเรียนรู้แบบเน้นโครงการช่วยให้คุณเรียนรู้ผ่านการลงมือทำ ซึ่งเป็นวิธีที่พิสูจน์แล้วว่าทำให้ทักษะใหม่ๆ ติดตัวได้ดี

**ขอขอบคุณผู้เขียนของเรา:** [Jasmine Greenaway](https://www.twitter.com/paladique), [Dmitry Soshnikov](http://soshnikov.com), [Nitya Narasimhan](https://twitter.com/nitya), [Jalen McGee](https://twitter.com/JalenMcG), [Jen Looper](https://twitter.com/jenlooper), [Maud Levy](https://twitter.com/maudstweets), [Tiffany Souterre](https://twitter.com/TiffanySouterre), [Christopher Harrison](https://www.twitter.com/geektrainer).

**🙏 ขอบคุณพิเศษ 🙏 สำหรับ [Microsoft Student Ambassador](https://studentambassadors.microsoft.com/) ผู้เขียน ผู้ตรวจสอบ และผู้มีส่วนร่วมในเนื้อหา,** โดยเฉพาะ Aaryan Arora, [Aditya Garg](https://github.com/AdityaGarg00), [Alondra Sanchez](https://www.linkedin.com/in/alondra-sanchez-molina/), [Ankita Singh](https://www.linkedin.com/in/ankitasingh007), [Anupam Mishra](https://www.linkedin.com/in/anupam--mishra/), [Arpita Das](https://www.linkedin.com/in/arpitadas01/), ChhailBihari Dubey, [Dibri Nsofor](https://www.linkedin.com/in/dibrinsofor), [Dishita Bhasin](https://www.linkedin.com/in/dishita-bhasin-7065281bb), [Majd Safi](https://www.linkedin.com/in/majd-s/), [Max Blum](https://www.linkedin.com/in/max-blum-6036a1186/), [Miguel Correa](https://www.linkedin.com/in/miguelmque/), [Mohamma Iftekher (Iftu) Ebne Jalal](https://twitter.com/iftu119), [Nawrin Tabassum](https://www.linkedin.com/in/nawrin-tabassum), [Raymond Wangsa Putra](https://www.linkedin.com/in/raymond-wp/), [Rohit Yadav](https://www.linkedin.com/in/rty2423), Samridhi Sharma, [Sanya Sinha](https://www.linkedin.com/mwlite/in/sanya-sinha-13aab1200),
[Sheena Narula](https://www.linkedin.com/in/sheena-narua-n/), [Tauqeer Ahmad](https://www.linkedin.com/in/tauqeerahmad5201/), Yogendrasingh Pawar , [Vidushi Gupta](https://www.linkedin.com/in/vidushi-gupta07/), [Jasleen Sondhi](https://www.linkedin.com/in/jasleen-sondhi/)

|![ภาพสเก็ตช์โดย @sketchthedocs https://sketchthedocs.dev](../../translated_images/00-Title.8af36cd35da1ac555b678627fbdc6e320c75f0100876ea41d30ea205d3b08d22.th.png)|
|:---:|
| วิทยาศาสตร์ข้อมูลสำหรับผู้เริ่มต้น - _ภาพสเก็ตช์โดย [@nitya](https://twitter.com/nitya)_ |

### 🌐 การสนับสนุนหลายภาษา

#### รองรับผ่าน GitHub Action (อัตโนมัติและอัปเดตเสมอ)

[French](../fr/README.md) | [Spanish](../es/README.md) | [German](../de/README.md) | [Russian](../ru/README.md) | [Arabic](../ar/README.md) | [Persian (Farsi)](../fa/README.md) | [Urdu](../ur/README.md) | [Chinese (Simplified)](../zh/README.md) | [Chinese (Traditional, Macau)](../mo/README.md) | [Chinese (Traditional, Hong Kong)](../hk/README.md) | [Chinese (Traditional, Taiwan)](../tw/README.md) | [Japanese](../ja/README.md) | [Korean](../ko/README.md) | [Hindi](../hi/README.md) | [Bengali](../bn/README.md) | [Marathi](../mr/README.md) | [Nepali](../ne/README.md) | [Punjabi (Gurmukhi)](../pa/README.md) | [Portuguese (Portugal)](../pt/README.md) | [Portuguese (Brazil)](../br/README.md) | [Italian](../it/README.md) | [Polish](../pl/README.md) | [Turkish](../tr/README.md) | [Greek](../el/README.md) | [Thai](./README.md) | [Swedish](../sv/README.md) | [Danish](../da/README.md) | [Norwegian](../no/README.md) | [Finnish](../fi/README.md) | [Dutch](../nl/README.md) | [Hebrew](../he/README.md) | [Vietnamese](../vi/README.md) | [Indonesian](../id/README.md) | [Malay](../ms/README.md) | [Tagalog (Filipino)](../tl/README.md) | [Swahili](../sw/README.md) | [Hungarian](../hu/README.md) | [Czech](../cs/README.md) | [Slovak](../sk/README.md) | [Romanian](../ro/README.md) | [Bulgarian](../bg/README.md) | [Serbian (Cyrillic)](../sr/README.md) | [Croatian](../hr/README.md) | [Slovenian](../sl/README.md) | [Ukrainian](../uk/README.md) | [Burmese (Myanmar)](../my/README.md)

**หากคุณต้องการให้มีการสนับสนุนภาษาเพิ่มเติม รายการภาษาที่รองรับอยู่ [ที่นี่](https://github.com/Azure/co-op-translator/blob/main/getting_started/supported-languages.md)**

#### เข้าร่วมชุมชนของเรา 
[![Azure AI Discord](https://dcbadge.limes.pink/api/server/kzRShWzttr)](https://aka.ms/ds4beginners/discord)

เรามีซีรีส์การเรียนรู้กับ AI ที่กำลังดำเนินอยู่ เรียนรู้เพิ่มเติมและเข้าร่วมกับเราได้ที่ [Learn with AI Series](https://aka.ms/learnwithai/discord) ตั้งแต่วันที่ 18 - 30 กันยายน 2025 คุณจะได้รับเคล็ดลับและเทคนิคในการใช้ GitHub Copilot สำหรับวิทยาศาสตร์ข้อมูล

![Learn with AI series](../../translated_images/1.2b28cdc6205e26fef6a21817fe5d83ae8b50fbd0a33e9fed0df05845da5b30b6.th.jpg)

# คุณเป็นนักเรียนหรือไม่?

เริ่มต้นด้วยทรัพยากรต่อไปนี้:

- [หน้าศูนย์นักเรียน](https://docs.microsoft.com/en-gb/learn/student-hub?WT.mc_id=academic-77958-bethanycheum) ในหน้านี้ คุณจะพบทรัพยากรสำหรับผู้เริ่มต้น ชุดเครื่องมือสำหรับนักเรียน และแม้กระทั่งวิธีการรับบัตรกำนัลการรับรองฟรี นี่คือหน้าที่คุณควรบุ๊กมาร์กและตรวจสอบเป็นระยะๆ เนื่องจากเรามีการเปลี่ยนแปลงเนื้อหาอย่างน้อยเดือนละครั้ง
- [Microsoft Learn Student Ambassadors](https://studentambassadors.microsoft.com?WT.mc_id=academic-77958-bethanycheum) เข้าร่วมชุมชนระดับโลกของนักเรียนแอมบาสเดอร์ นี่อาจเป็นทางเข้าสู่ Microsoft ของคุณ

# เริ่มต้นใช้งาน

> **ผู้เริ่มต้นอย่างสมบูรณ์**: ใหม่กับวิทยาศาสตร์ข้อมูล? เริ่มต้นด้วย [ตัวอย่างที่เหมาะสำหรับผู้เริ่มต้น](examples/README.md)! ตัวอย่างที่เรียบง่ายและมีคำอธิบายชัดเจนเหล่านี้จะช่วยให้คุณเข้าใจพื้นฐานก่อนที่จะดำดิ่งสู่หลักสูตรเต็มรูปแบบ

> **ครู**: เราได้ [รวมคำแนะนำบางส่วน](for-teachers.md) เกี่ยวกับวิธีการใช้หลักสูตรนี้ เราอยากได้ความคิดเห็นของคุณ [ในฟอรัมการสนทนาของเรา](https://github.com/microsoft/Data-Science-For-Beginners/discussions)!

> **[นักเรียน](https://aka.ms/student-page)**: หากต้องการใช้หลักสูตรนี้ด้วยตัวเอง ให้ fork repo ทั้งหมดและทำแบบฝึกหัดด้วยตัวเอง โดยเริ่มต้นด้วยแบบทดสอบก่อนการบรรยาย จากนั้นอ่านการบรรยายและทำกิจกรรมที่เหลือ พยายามสร้างโครงการโดยการทำความเข้าใจบทเรียนแทนที่จะคัดลอกรหัสโซลูชัน อย่างไรก็ตาม รหัสนั้นมีอยู่ในโฟลเดอร์ /solutions ในแต่ละบทเรียนที่เน้นโครงการ อีกแนวคิดหนึ่งคือการสร้างกลุ่มการศึกษาและเรียนรู้เนื้อหาด้วยกัน สำหรับการศึกษาต่อ เราแนะนำ [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/qprpajyoy3x0g7?WT.mc_id=academic-77958-bethanycheum)

## พบกับทีมงาน

[![วิดีโอโปรโมต](../../ds-for-beginners.gif)](https://youtu.be/8mzavjQSMM4 "วิดีโอโปรโมต")

**Gif โดย** [Mohit Jaisal](https://www.linkedin.com/in/mohitjaisal)

> 🎥 คลิกที่ภาพด้านบนเพื่อดูวิดีโอเกี่ยวกับโครงการและผู้ที่สร้างมันขึ้นมา!

## วิธีการสอน

เราเลือกใช้หลักการสอนสองข้อในการสร้างหลักสูตรนี้: การเน้นโครงการและการรวมแบบทดสอบบ่อยๆ เมื่อจบซีรีส์นี้ นักเรียนจะได้เรียนรู้หลักการพื้นฐานของวิทยาศาสตร์ข้อมูล รวมถึงแนวคิดด้านจริยธรรม การเตรียมข้อมูล วิธีการทำงานกับข้อมูล การสร้างภาพข้อมูล การวิเคราะห์ข้อมูล กรณีการใช้งานจริงของวิทยาศาสตร์ข้อมูล และอื่นๆ

นอกจากนี้ แบบทดสอบที่มีความเสี่ยงต่ำก่อนชั้นเรียนจะช่วยตั้งเจตนาของนักเรียนในการเรียนรู้หัวข้อ ในขณะที่แบบทดสอบที่สองหลังชั้นเรียนช่วยเพิ่มการจดจำ หลักสูตรนี้ออกแบบมาให้ยืดหยุ่นและสนุกสนาน และสามารถเรียนได้ทั้งแบบเต็มหรือบางส่วน โครงการเริ่มต้นจากขนาดเล็กและมีความซับซ้อนมากขึ้นเมื่อจบวงจร 10 สัปดาห์

> ดู [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md), [Translation](TRANSLATIONS.md) แนวทาง เรายินดีรับความคิดเห็นที่สร้างสรรค์ของคุณ!

## แต่ละบทเรียนประกอบด้วย:

- ภาพสเก็ตช์ (ไม่บังคับ)
- วิดีโอเสริม (ไม่บังคับ)
- แบบทดสอบอุ่นเครื่องก่อนบทเรียน
- บทเรียนที่เขียนไว้
- สำหรับบทเรียนที่เน้นโครงการ มีคำแนะนำทีละขั้นตอนเกี่ยวกับวิธีการสร้างโครงการ
- การตรวจสอบความรู้
- ความท้าทาย
- การอ่านเสริม
- งานมอบหมาย
- [แบบทดสอบหลังบทเรียน](https://ff-quizzes.netlify.app/en/)
> **หมายเหตุเกี่ยวกับแบบทดสอบ**: แบบทดสอบทั้งหมดอยู่ในโฟลเดอร์ Quiz-App ซึ่งมีทั้งหมด 40 แบบทดสอบ โดยแต่ละแบบทดสอบมี 3 คำถาม แบบทดสอบเหล่านี้ถูกเชื่อมโยงจากบทเรียน แต่แอปแบบทดสอบสามารถรันได้ในเครื่องหรือเผยแพร่ไปยัง Azure ให้ทำตามคำแนะนำในโฟลเดอร์ `quiz-app` แบบทดสอบกำลังถูกแปลเป็นภาษาต่างๆ อย่างต่อเนื่อง

## 🎓 ตัวอย่างที่เหมาะสำหรับผู้เริ่มต้น

**ใหม่กับ Data Science?** เราได้สร้าง [โฟลเดอร์ตัวอย่าง](examples/README.md) ที่มีโค้ดง่ายๆ พร้อมคำอธิบายเพื่อช่วยให้คุณเริ่มต้นได้:

- 🌟 **Hello World** - โปรแกรม Data Science แรกของคุณ
- 📂 **การโหลดข้อมูล** - เรียนรู้วิธีอ่านและสำรวจชุดข้อมูล
- 📊 **การวิเคราะห์ง่ายๆ** - คำนวณสถิติและค้นหารูปแบบ
- 📈 **การสร้างภาพพื้นฐาน** - สร้างแผนภูมิและกราฟ
- 🔬 **โครงการในโลกจริง** - กระบวนการทำงานตั้งแต่ต้นจนจบ

แต่ละตัวอย่างมีคำอธิบายละเอียดในทุกขั้นตอน เหมาะสำหรับผู้เริ่มต้นอย่างแท้จริง!

👉 **[เริ่มต้นด้วยตัวอย่าง](examples/README.md)** 👈

## บทเรียน

|![ Sketchnote โดย @sketchthedocs https://sketchthedocs.dev](../../translated_images/00-Roadmap.4905d6567dff47532b9bfb8e0b8980fc6b0b1292eebb24181c1a9753b33bc0f5.th.png)|
|:---:|
| Data Science สำหรับผู้เริ่มต้น: แผนที่นำทาง - _Sketchnote โดย [@nitya](https://twitter.com/nitya)_ |

| หมายเลขบทเรียน | หัวข้อ | กลุ่มบทเรียน | วัตถุประสงค์การเรียนรู้ | ลิงก์บทเรียน | ผู้เขียน |
| :-----------: | :----------------------------------------: | :--------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :----: |
| 01 | การนิยาม Data Science | [บทนำ](1-Introduction/README.md) | เรียนรู้แนวคิดพื้นฐานเกี่ยวกับ Data Science และความสัมพันธ์กับปัญญาประดิษฐ์ การเรียนรู้ของเครื่อง และ Big Data | [บทเรียน](1-Introduction/01-defining-data-science/README.md) [วิดีโอ](https://youtu.be/beZ7Mb_oz9I) | [Dmitry](http://soshnikov.com) |
| 02 | จริยธรรมใน Data Science | [บทนำ](1-Introduction/README.md) | แนวคิดเกี่ยวกับจริยธรรมในข้อมูล ความท้าทาย และกรอบการทำงาน | [บทเรียน](1-Introduction/02-ethics/README.md) | [Nitya](https://twitter.com/nitya) |
| 03 | การนิยามข้อมูล | [บทนำ](1-Introduction/README.md) | วิธีการจัดประเภทข้อมูลและแหล่งข้อมูลทั่วไป | [บทเรียน](1-Introduction/03-defining-data/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 04 | บทนำสู่สถิติและความน่าจะเป็น | [บทนำ](1-Introduction/README.md) | เทคนิคทางคณิตศาสตร์ของความน่าจะเป็นและสถิติเพื่อทำความเข้าใจข้อมูล | [บทเรียน](1-Introduction/04-stats-and-probability/README.md) [วิดีโอ](https://youtu.be/Z5Zy85g4Yjw) | [Dmitry](http://soshnikov.com) |
| 05 | การทำงานกับข้อมูลเชิงสัมพันธ์ | [การทำงานกับข้อมูล](2-Working-With-Data/README.md) | บทนำเกี่ยวกับข้อมูลเชิงสัมพันธ์และพื้นฐานการสำรวจและวิเคราะห์ข้อมูลเชิงสัมพันธ์ด้วย Structured Query Language หรือ SQL (ออกเสียงว่า "ซีเควล") | [บทเรียน](2-Working-With-Data/05-relational-databases/README.md) | [Christopher](https://www.twitter.com/geektrainer) | | |
| 06 | การทำงานกับข้อมูล NoSQL | [การทำงานกับข้อมูล](2-Working-With-Data/README.md) | บทนำเกี่ยวกับข้อมูลที่ไม่ใช่เชิงสัมพันธ์ ประเภทต่างๆ และพื้นฐานการสำรวจและวิเคราะห์ฐานข้อมูลเอกสาร | [บทเรียน](2-Working-With-Data/06-non-relational/README.md) | [Jasmine](https://twitter.com/paladique)|
| 07 | การทำงานกับ Python | [การทำงานกับข้อมูล](2-Working-With-Data/README.md) | พื้นฐานการใช้ Python เพื่อสำรวจข้อมูลด้วยไลบรารี เช่น Pandas แนะนำให้มีความเข้าใจพื้นฐานเกี่ยวกับการเขียนโปรแกรม Python | [บทเรียน](2-Working-With-Data/07-python/README.md) [วิดีโอ](https://youtu.be/dZjWOGbsN4Y) | [Dmitry](http://soshnikov.com) |
| 08 | การเตรียมข้อมูล | [การทำงานกับข้อมูล](2-Working-With-Data/README.md) | หัวข้อเกี่ยวกับเทคนิคการทำความสะอาดและแปลงข้อมูลเพื่อจัดการกับปัญหาข้อมูลที่ขาดหาย ไม่ถูกต้อง หรือไม่สมบูรณ์ | [บทเรียน](2-Working-With-Data/08-data-preparation/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 09 | การสร้างภาพปริมาณข้อมูล | [การสร้างภาพข้อมูล](3-Data-Visualization/README.md) | เรียนรู้วิธีใช้ Matplotlib เพื่อสร้างภาพข้อมูลนก 🦆 | [บทเรียน](3-Data-Visualization/09-visualization-quantities/README.md) | [Jen](https://twitter.com/jenlooper) |
| 10 | การสร้างภาพการกระจายของข้อมูล | [การสร้างภาพข้อมูล](3-Data-Visualization/README.md) | การสร้างภาพการสังเกตและแนวโน้มภายในช่วงเวลา | [บทเรียน](3-Data-Visualization/10-visualization-distributions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 11 | การสร้างภาพสัดส่วน | [การสร้างภาพข้อมูล](3-Data-Visualization/README.md) | การสร้างภาพเปอร์เซ็นต์แบบแยกและแบบกลุ่ม | [บทเรียน](3-Data-Visualization/11-visualization-proportions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 12 | การสร้างภาพความสัมพันธ์ | [การสร้างภาพข้อมูล](3-Data-Visualization/README.md) | การสร้างภาพการเชื่อมโยงและความสัมพันธ์ระหว่างชุดข้อมูลและตัวแปร | [บทเรียน](3-Data-Visualization/12-visualization-relationships/README.md) | [Jen](https://twitter.com/jenlooper) |
| 13 | การสร้างภาพที่มีความหมาย | [การสร้างภาพข้อมูล](3-Data-Visualization/README.md) | เทคนิคและคำแนะนำในการทำให้การสร้างภาพของคุณมีคุณค่าเพื่อการแก้ปัญหาและการให้ข้อมูลเชิงลึกที่มีประสิทธิภาพ | [บทเรียน](3-Data-Visualization/13-meaningful-visualizations/README.md) | [Jen](https://twitter.com/jenlooper) |
| 14 | บทนำสู่วงจรชีวิตของ Data Science | [วงจรชีวิต](4-Data-Science-Lifecycle/README.md) | บทนำเกี่ยวกับวงจรชีวิตของ Data Science และขั้นตอนแรกในการรวบรวมและดึงข้อมูล | [บทเรียน](4-Data-Science-Lifecycle/14-Introduction/README.md) | [Jasmine](https://twitter.com/paladique) |
| 15 | การวิเคราะห์ | [วงจรชีวิต](4-Data-Science-Lifecycle/README.md) | ขั้นตอนนี้ของวงจรชีวิต Data Science มุ่งเน้นไปที่เทคนิคการวิเคราะห์ข้อมูล | [บทเรียน](4-Data-Science-Lifecycle/15-analyzing/README.md) | [Jasmine](https://twitter.com/paladique) | | |
| 16 | การสื่อสาร | [วงจรชีวิต](4-Data-Science-Lifecycle/README.md) | ขั้นตอนนี้ของวงจรชีวิต Data Science มุ่งเน้นไปที่การนำเสนอข้อมูลเชิงลึกจากข้อมูลในรูปแบบที่ทำให้ผู้ตัดสินใจเข้าใจได้ง่ายขึ้น | [บทเรียน](4-Data-Science-Lifecycle/16-communication/README.md) | [Jalen](https://twitter.com/JalenMcG) | | |
| 17 | Data Science ในระบบคลาวด์ | [ข้อมูลในระบบคลาวด์](5-Data-Science-In-Cloud/README.md) | ชุดบทเรียนนี้แนะนำ Data Science ในระบบคลาวด์และประโยชน์ของมัน | [บทเรียน](5-Data-Science-In-Cloud/17-Introduction/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) และ [Maud](https://twitter.com/maudstweets) |
| 18 | Data Science ในระบบคลาวด์ | [ข้อมูลในระบบคลาวด์](5-Data-Science-In-Cloud/README.md) | การฝึกอบรมโมเดลโดยใช้เครื่องมือ Low Code |[บทเรียน](5-Data-Science-In-Cloud/18-Low-Code/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) และ [Maud](https://twitter.com/maudstweets) |
| 19 | Data Science ในระบบคลาวด์ | [ข้อมูลในระบบคลาวด์](5-Data-Science-In-Cloud/README.md) | การเผยแพร่โมเดลด้วย Azure Machine Learning Studio | [บทเรียน](5-Data-Science-In-Cloud/19-Azure/README.md)| [Tiffany](https://twitter.com/TiffanySouterre) และ [Maud](https://twitter.com/maudstweets) |
| 20 | Data Science ในโลกจริง | [ในโลกจริง](6-Data-Science-In-Wild/README.md) | โครงการที่ขับเคลื่อนด้วย Data Science ในโลกจริง | [บทเรียน](6-Data-Science-In-Wild/20-Real-World-Examples/README.md) | [Nitya](https://twitter.com/nitya) |

## GitHub Codespaces

ทำตามขั้นตอนเหล่านี้เพื่อเปิดตัวอย่างนี้ใน Codespace:
1. คลิกเมนูแบบเลื่อนลง Code และเลือกตัวเลือก Open with Codespaces
2. เลือก + New codespace ที่ด้านล่างของแผง
สำหรับข้อมูลเพิ่มเติม ดู [เอกสาร GitHub](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace).

## VSCode Remote - Containers
ทำตามขั้นตอนเหล่านี้เพื่อเปิด repo นี้ใน container โดยใช้เครื่องของคุณและ VSCode ด้วยส่วนขยาย VS Code Remote - Containers:

1. หากนี่เป็นครั้งแรกที่คุณใช้ container สำหรับการพัฒนา โปรดตรวจสอบให้แน่ใจว่าระบบของคุณตรงตามข้อกำหนดเบื้องต้น (เช่น ติดตั้ง Docker) ใน [เอกสารการเริ่มต้นใช้งาน](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started).

ในการใช้ repo นี้ คุณสามารถเปิด repo ใน Docker volume ที่แยกออกมา:

**หมายเหตุ**: เบื้องหลังจะใช้คำสั่ง Remote-Containers: **Clone Repository in Container Volume...** เพื่อโคลนซอร์สโค้ดใน Docker volume แทนที่จะเป็นระบบไฟล์ในเครื่อง [Volumes](https://docs.docker.com/storage/volumes/) เป็นกลไกที่แนะนำสำหรับการเก็บข้อมูล container

หรือเปิด repo ที่โคลนหรือดาวน์โหลดไว้ในเครื่อง:

- โคลน repo นี้ไปยังระบบไฟล์ในเครื่องของคุณ
- กด F1 และเลือกคำสั่ง **Remote-Containers: Open Folder in Container...**
- เลือกสำเนาที่โคลนของโฟลเดอร์นี้ รอให้ container เริ่มต้น และลองใช้งาน

## การเข้าถึงแบบออฟไลน์

คุณสามารถรันเอกสารนี้แบบออฟไลน์โดยใช้ [Docsify](https://docsify.js.org/#/). Fork repo นี้, [ติดตั้ง Docsify](https://docsify.js.org/#/quickstart) บนเครื่องของคุณ จากนั้นในโฟลเดอร์ root ของ repo นี้ ให้พิมพ์ `docsify serve`. เว็บไซต์จะถูกให้บริการบนพอร์ต 3000 บน localhost ของคุณ: `localhost:3000`.

> หมายเหตุ โน้ตบุ๊กจะไม่ถูกแสดงผลผ่าน Docsify ดังนั้นเมื่อคุณต้องการรันโน้ตบุ๊ก ให้ทำแยกต่างหากใน VS Code โดยใช้ Python kernel

## หลักสูตรอื่นๆ

ทีมของเราผลิตหลักสูตรอื่นๆ! ลองดู:

- [Edge AI สำหรับผู้เริ่มต้น](https://aka.ms/edgeai-for-beginners)
- [AI Agents สำหรับผู้เริ่มต้น](https://aka.ms/ai-agents-beginners)
- [Generative AI สำหรับผู้เริ่มต้น](https://aka.ms/genai-beginners)
- [Generative AI สำหรับผู้เริ่มต้น .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet)
- [Generative AI ด้วย JavaScript](https://github.com/microsoft/generative-ai-with-javascript)
- [Generative AI ด้วย Java](https://aka.ms/genaijava)
- [AI สำหรับผู้เริ่มต้น](https://aka.ms/ai-beginners)
- [Data Science สำหรับผู้เริ่มต้น](https://aka.ms/datascience-beginners)
- [Bash สำหรับผู้เริ่มต้น](https://github.com/microsoft/bash-for-beginners)
- [ML สำหรับผู้เริ่มต้น](https://aka.ms/ml-beginners)
- [Cybersecurity สำหรับผู้เริ่มต้น](https://github.com/microsoft/Security-101) 
- [Web Dev สำหรับผู้เริ่มต้น](https://aka.ms/webdev-beginners)
- [IoT สำหรับผู้เริ่มต้น](https://aka.ms/iot-beginners)
- [Machine Learning สำหรับผู้เริ่มต้น](https://aka.ms/ml-beginners)
- [XR Development สำหรับผู้เริ่มต้น](https://aka.ms/xr-dev-for-beginners)
- [การใช้งาน GitHub Copilot สำหรับการเขียนโปรแกรม AI แบบคู่](https://aka.ms/GitHubCopilotAI)
- [XR Development สำหรับผู้เริ่มต้น](https://github.com/microsoft/xr-development-for-beginners)
- [การใช้งาน GitHub Copilot สำหรับนักพัฒนา C#/.NET](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers)
- [เลือกการผจญภัย Copilot ของคุณเอง](https://github.com/microsoft/CopilotAdventures)

## การขอความช่วยเหลือ

หากคุณติดขัดหรือมีคำถามเกี่ยวกับการสร้างแอป AI เข้าร่วม:

[![Azure AI Foundry Discord](https://img.shields.io/badge/Discord-Azure_AI_Foundry_Community_Discord-blue?style=for-the-badge&logo=discord&color=5865f2&logoColor=fff)](https://aka.ms/foundry/discord)

หากคุณมีข้อเสนอแนะเกี่ยวกับผลิตภัณฑ์หรือพบข้อผิดพลาดขณะสร้าง โปรดเยี่ยมชม:
[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

**ข้อจำกัดความรับผิดชอบ**:  
เอกสารนี้ได้รับการแปลโดยใช้บริการแปลภาษา AI [Co-op Translator](https://github.com/Azure/co-op-translator) แม้ว่าเราจะพยายามให้การแปลมีความถูกต้อง แต่โปรดทราบว่าการแปลอัตโนมัติอาจมีข้อผิดพลาดหรือความไม่ถูกต้อง เอกสารต้นฉบับในภาษาดั้งเดิมควรถือเป็นแหล่งข้อมูลที่เชื่อถือได้ สำหรับข้อมูลที่สำคัญ ขอแนะนำให้ใช้บริการแปลภาษามนุษย์ที่มีความเชี่ยวชาญ เราไม่รับผิดชอบต่อความเข้าใจผิดหรือการตีความผิดที่เกิดจากการใช้การแปลนี้