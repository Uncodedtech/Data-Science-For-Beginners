<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "3beef650c5bafd70d88e2643a2b360fb",
  "translation_date": "2025-10-03T12:47:35+00:00",
  "source_file": "README.md",
  "language_code": "sr"
}
-->
# Наука о подацима за почетнике - Наставни план

Azure Cloud Advocates у Microsoft-у са задовољством представљају наставни план од 10 недеља и 20 лекција посвећен науци о подацима. Свака лекција укључује квизове пре и после лекције, писана упутства за завршетак лекције, решење и задатак. Наш приступ заснован на пројектима омогућава вам да учите кроз практичан рад, што је доказан начин да нове вештине остану трајно усвојене.

**Срдачна захвалност нашим ауторима:** [Jasmine Greenaway](https://www.twitter.com/paladique), [Dmitry Soshnikov](http://soshnikov.com), [Nitya Narasimhan](https://twitter.com/nitya), [Jalen McGee](https://twitter.com/JalenMcG), [Jen Looper](https://twitter.com/jenlooper), [Maud Levy](https://twitter.com/maudstweets), [Tiffany Souterre](https://twitter.com/TiffanySouterre), [Christopher Harrison](https://www.twitter.com/geektrainer).

**🙏 Посебна захвалност 🙏 нашим [Microsoft Student Ambassador](https://studentambassadors.microsoft.com/) ауторима, рецензентима и сарадницима,** укључујући Aaryan Arora, [Aditya Garg](https://github.com/AdityaGarg00), [Alondra Sanchez](https://www.linkedin.com/in/alondra-sanchez-molina/), [Ankita Singh](https://www.linkedin.com/in/ankitasingh007), [Anupam Mishra](https://www.linkedin.com/in/anupam--mishra/), [Arpita Das](https://www.linkedin.com/in/arpitadas01/), ChhailBihari Dubey, [Dibri Nsofor](https://www.linkedin.com/in/dibrinsofor), [Dishita Bhasin](https://www.linkedin.com/in/dishita-bhasin-7065281bb), [Majd Safi](https://www.linkedin.com/in/majd-s/), [Max Blum](https://www.linkedin.com/in/max-blum-6036a1186/), [Miguel Correa](https://www.linkedin.com/in/miguelmque/), [Mohamma Iftekher (Iftu) Ebne Jalal](https://twitter.com/iftu119), [Nawrin Tabassum](https://www.linkedin.com/in/nawrin-tabassum), [Raymond Wangsa Putra](https://www.linkedin.com/in/raymond-wp/), [Rohit Yadav](https://www.linkedin.com/in/rty2423), Samridhi Sharma, [Sanya Sinha](https://www.linkedin.com/mwlite/in/sanya-sinha-13aab1200), [Sheena Narula](https://www.linkedin.com/in/sheena-narua-n/), [Tauqeer Ahmad](https://www.linkedin.com/in/tauqeerahmad5201/), Yogendrasingh Pawar, [Vidushi Gupta](https://www.linkedin.com/in/vidushi-gupta07/), [Jasleen Sondhi](https://www.linkedin.com/in/jasleen-sondhi/)

|![Илустрација од @sketchthedocs https://sketchthedocs.dev](../../translated_images/00-Title.8af36cd35da1ac555b678627fbdc6e320c75f0100876ea41d30ea205d3b08d22.sr.png)|
|:---:|
| Наука о подацима за почетнике - _Илустрација од [@nitya](https://twitter.com/nitya)_ |

### 🌐 Подршка за више језика

#### Подржано преко GitHub Action (аутоматски и увек ажурирано)

[Француски](../fr/README.md) | [Шпански](../es/README.md) | [Немачки](../de/README.md) | [Руски](../ru/README.md) | [Арапски](../ar/README.md) | [Персијски (Фарси)](../fa/README.md) | [Урду](../ur/README.md) | [Кинески (поједностављени)](../zh/README.md) | [Кинески (традиционални, Макао)](../mo/README.md) | [Кинески (традиционални, Хонг Конг)](../hk/README.md) | [Кинески (традиционални, Тајван)](../tw/README.md) | [Јапански](../ja/README.md) | [Корејски](../ko/README.md) | [Хинди](../hi/README.md) | [Бенгалски](../bn/README.md) | [Марати](../mr/README.md) | [Непалски](../ne/README.md) | [Пенџабски (Гурмуки)](../pa/README.md) | [Португалски (Португалија)](../pt/README.md) | [Португалски (Бразил)](../br/README.md) | [Италијански](../it/README.md) | [Пољски](../pl/README.md) | [Турски](../tr/README.md) | [Грчки](../el/README.md) | [Тајландски](../th/README.md) | [Шведски](../sv/README.md) | [Дански](../da/README.md) | [Норвешки](../no/README.md) | [Фински](../fi/README.md) | [Холандски](../nl/README.md) | [Хебрејски](../he/README.md) | [Вијетнамски](../vi/README.md) | [Индонежански](../id/README.md) | [Малајски](../ms/README.md) | [Тагалог (Филипински)](../tl/README.md) | [Свахили](../sw/README.md) | [Мађарски](../hu/README.md) | [Чешки](../cs/README.md) | [Словачки](../sk/README.md) | [Румунски](../ro/README.md) | [Бугарски](../bg/README.md) | [Српски (Ћирилица)](./README.md) | [Хрватски](../hr/README.md) | [Словеначки](../sl/README.md) | [Украјински](../uk/README.md) | [Бурмански (Мјанмар)](../my/README.md)

**Ако желите да додате подршку за додатне језике, списак је доступан [овде](https://github.com/Azure/co-op-translator/blob/main/getting_started/supported-languages.md)**

#### Придружите се нашој заједници 
[![Azure AI Discord](https://dcbadge.limes.pink/api/server/kzRShWzttr)](https://aka.ms/ds4beginners/discord)

Имамо серију учења са AI на Discord-у, сазнајте више и придружите нам се на [Learn with AI Series](https://aka.ms/learnwithai/discord) од 18. до 30. септембра 2025. Добићете савете и трикове за коришћење GitHub Copilot-а за науку о подацима.

![Learn with AI series](../../translated_images/1.2b28cdc6205e26fef6a21817fe5d83ae8b50fbd0a33e9fed0df05845da5b30b6.sr.jpg)

# Да ли сте студент?

Започните са следећим ресурсима:

- [Студентска страница](https://docs.microsoft.com/en-gb/learn/student-hub?WT.mc_id=academic-77958-bethanycheum) На овој страници ћете пронаћи ресурсе за почетнике, студентске пакете и чак начине да добијете бесплатан ваучер за сертификат. Ово је страница коју желите да обележите и повремено проверавате, јер садржај мењамо најмање једном месечно.
- [Microsoft Learn Student Ambassadors](https://studentambassadors.microsoft.com?WT.mc_id=academic-77958-bethanycheum) Придружите се глобалној заједници студентских амбасадора, ово би могао бити ваш пут ка Microsoft-у.

# Почетак

> **Потпуни почетници**: Нови сте у науци о подацима? Почните са нашим [примерима прилагођеним почетницима](examples/README.md)! Ови једноставни, добро коментарисани примери помоћи ће вам да разумете основе пре него што се упустите у комплетан наставни план.

> **Наставници**: укључили смо [неке предлоге](for-teachers.md) о томе како да користите овај наставни план. Волели бисмо да чујемо ваше повратне информације [у нашем форуму за дискусију](https://github.com/microsoft/Data-Science-For-Beginners/discussions)!

> **[Студенти](https://aka.ms/student-page)**: да бисте користили овај наставни план самостално, направите форк целог репозиторијума и завршите вежбе самостално, почевши од квиза пре предавања. Затим прочитајте предавање и завршите остале активности. Покушајте да креирате пројекте разумевањем лекција уместо копирања кода решења; међутим, тај код је доступан у /solutions фолдерима у свакој лекцији заснованој на пројектима. Друга идеја би била да формирате групу за учење са пријатељима и заједно прођете кроз садржај. За даље учење, препоручујемо [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/qprpajyoy3x0g7?WT.mc_id=academic-77958-bethanycheum).

## Упознајте тим

[![Промо видео](../../ds-for-beginners.gif)](https://youtu.be/8mzavjQSMM4 "Promo video")

**Gif од** [Mohit Jaisal](https://www.linkedin.com/in/mohitjaisal)

> 🎥 Кликните на слику изнад за видео о пројекту и људима који су га креирали!

## Педагошки приступ

Приликом креирања овог наставног плана изабрали смо два педагошка принципа: осигурање да је заснован на пројектима и да укључује честе квизове. До краја ове серије, студенти ће научити основне принципе науке о подацима, укључујући етичке концепте, припрему података, различите начине рада са подацима, визуализацију података, анализу података, стварне примере примене науке о подацима и још много тога.

Поред тога, квиз са ниским ризиком пре часа поставља намеру студента ка учењу теме, док други квиз након часа осигурава даље задржавање знања. Овај наставни план је дизајниран да буде флексибилан и забаван и може се узети у целини или делимично. Пројекти почињу малим и постају све сложенији до краја циклуса од 10 недеља.

> Пронађите наш [Кодекс понашања](CODE_OF_CONDUCT.md), [Упутства за допринос](CONTRIBUTING.md), [Упутства за превод](TRANSLATIONS.md). Добродошли сте да нам доставите конструктивне повратне информације!

## Свака лекција укључује:

- Опциона илустрација
- Опциони допунски видео
- Квиз за загревање пре лекције
- Писана лекција
- За лекције засноване на пројектима, водиче корак по корак како да изградите пројекат
- Провере знања
- Изазов
- Допунско читање
- Задатак
- [Квиз након лекције](https://ff-quizzes.netlify.app/en/)
> **Напомена о квизовима**: Сви квизови се налазе у фасцикли Quiz-App, укупно 40 квизова са по три питања. Они су повезани унутар лекција, али апликација за квизове може се покренути локално или распоредити на Azure; пратите упутства у фасцикли `quiz-app`. Постепено се локализују.

## 🎓 Примери за почетнике

**Нови сте у науци о подацима?** Направили смо посебан [директоријум са примерима](examples/README.md) са једноставним, добро коментарисаним кодом који ће вам помоћи да почнете:

- 🌟 **Hello World** - Ваш први програм у науци о подацима
- 📂 **Учитавање података** - Научите како да читате и истражујете скупове података
- 📊 **Једноставна анализа** - Израчунајте статистике и пронађите обрасце
- 📈 **Основна визуализација** - Направите графиконе и дијаграме
- 🔬 **Пројекат из стварног света** - Комплетан ток рада од почетка до краја

Сваки пример садржи детаљне коментаре који објашњавају сваки корак, што их чини савршеним за апсолутне почетнике!

👉 **[Почните са примерима](examples/README.md)** 👈

## Лекције

|![ Скетч од @sketchthedocs https://sketchthedocs.dev](../../translated_images/00-Roadmap.4905d6567dff47532b9bfb8e0b8980fc6b0b1292eebb24181c1a9753b33bc0f5.sr.png)|
|:---:|
| Наука о подацима за почетнике: План - _Скетч од [@nitya](https://twitter.com/nitya)_ |

| Број лекције | Тема | Груписање лекција | Циљеви учења | Повезана лекција | Аутор |
| :-----------: | :----------------------------------------: | :--------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :----: |
| 01 | Дефинисање науке о подацима | [Увод](1-Introduction/README.md) | Научите основне концепте науке о подацима и како је она повезана са вештачком интелигенцијом, машинским учењем и великим подацима. | [лекција](1-Introduction/01-defining-data-science/README.md) [видео](https://youtu.be/beZ7Mb_oz9I) | [Дмитриј](http://soshnikov.com) |
| 02 | Етика у науци о подацима | [Увод](1-Introduction/README.md) | Концепти етике података, изазови и оквири. | [лекција](1-Introduction/02-ethics/README.md) | [Нитија](https://twitter.com/nitya) |
| 03 | Дефинисање података | [Увод](1-Introduction/README.md) | Како се подаци класификују и који су њихови уобичајени извори. | [лекција](1-Introduction/03-defining-data/README.md) | [Јасмин](https://www.twitter.com/paladique) |
| 04 | Увод у статистику и вероватноћу | [Увод](1-Introduction/README.md) | Математичке технике вероватноће и статистике за разумевање података. | [лекција](1-Introduction/04-stats-and-probability/README.md) [видео](https://youtu.be/Z5Zy85g4Yjw) | [Дмитриј](http://soshnikov.com) |
| 05 | Рад са релационим подацима | [Рад са подацима](2-Working-With-Data/README.md) | Увод у релационе податке и основе истраживања и анализе релационих података помоћу језика SQL. | [лекција](2-Working-With-Data/05-relational-databases/README.md) | [Кристофер](https://www.twitter.com/geektrainer) | | |
| 06 | Рад са NoSQL подацима | [Рад са подацима](2-Working-With-Data/README.md) | Увод у нерелационе податке, њихове различите типове и основе истраживања и анализе докумената базе података. | [лекција](2-Working-With-Data/06-non-relational/README.md) | [Јасмин](https://twitter.com/paladique)|
| 07 | Рад са Python-ом | [Рад са подацима](2-Working-With-Data/README.md) | Основе коришћења Python-а за истраживање података са библиотекама као што је Pandas. Препоручује се основно разумевање Python програмирања. | [лекција](2-Working-With-Data/07-python/README.md) [видео](https://youtu.be/dZjWOGbsN4Y) | [Дмитриј](http://soshnikov.com) |
| 08 | Припрема података | [Рад са подацима](2-Working-With-Data/README.md) | Теме о техникама чишћења и трансформације података за решавање изазова као што су недостајући, нетачни или непотпуни подаци. | [лекција](2-Working-With-Data/08-data-preparation/README.md) | [Јасмин](https://www.twitter.com/paladique) |
| 09 | Визуелизација количина | [Визуелизација података](3-Data-Visualization/README.md) | Научите како да користите Matplotlib за визуелизацију података о птицама 🦆 | [лекција](3-Data-Visualization/09-visualization-quantities/README.md) | [Џен](https://twitter.com/jenlooper) |
| 10 | Визуелизација дистрибуције података | [Визуелизација података](3-Data-Visualization/README.md) | Визуелизација запажања и трендова унутар интервала. | [лекција](3-Data-Visualization/10-visualization-distributions/README.md) | [Џен](https://twitter.com/jenlooper) |
| 11 | Визуелизација пропорција | [Визуелизација података](3-Data-Visualization/README.md) | Визуелизација дискретних и груписаних процената. | [лекција](3-Data-Visualization/11-visualization-proportions/README.md) | [Џен](https://twitter.com/jenlooper) |
| 12 | Визуелизација односа | [Визуелизација података](3-Data-Visualization/README.md) | Визуелизација веза и корелација између скупова података и њихових варијабли. | [лекција](3-Data-Visualization/12-visualization-relationships/README.md) | [Џен](https://twitter.com/jenlooper) |
| 13 | Смислене визуелизације | [Визуелизација података](3-Data-Visualization/README.md) | Технике и смернице за прављење визуелизација које су вредне за ефикасно решавање проблема и увиде. | [лекција](3-Data-Visualization/13-meaningful-visualizations/README.md) | [Џен](https://twitter.com/jenlooper) |
| 14 | Увод у животни циклус науке о подацима | [Животни циклус](4-Data-Science-Lifecycle/README.md) | Увод у животни циклус науке о подацима и његов први корак - прикупљање и екстракција података. | [лекција](4-Data-Science-Lifecycle/14-Introduction/README.md) | [Јасмин](https://twitter.com/paladique) |
| 15 | Анализа | [Животни циклус](4-Data-Science-Lifecycle/README.md) | Ова фаза животног циклуса науке о подацима фокусира се на технике анализе података. | [лекција](4-Data-Science-Lifecycle/15-analyzing/README.md) | [Јасмин](https://twitter.com/paladique) | | |
| 16 | Комуникација | [Животни циклус](4-Data-Science-Lifecycle/README.md) | Ова фаза животног циклуса науке о подацима фокусира се на представљање увида из података на начин који доносиоцима одлука олакшава разумевање. | [лекција](4-Data-Science-Lifecycle/16-communication/README.md) | [Џејлен](https://twitter.com/JalenMcG) | | |
| 17 | Наука о подацима у облаку | [Облачни подаци](5-Data-Science-In-Cloud/README.md) | Ова серија лекција уводи науку о подацима у облаку и њене предности. | [лекција](5-Data-Science-In-Cloud/17-Introduction/README.md) | [Тифани](https://twitter.com/TiffanySouterre) и [Мод](https://twitter.com/maudstweets) |
| 18 | Наука о подацима у облаку | [Облачни подаци](5-Data-Science-In-Cloud/README.md) | Тренирање модела коришћењем алата са ниским кодом. |[лекција](5-Data-Science-In-Cloud/18-Low-Code/README.md) | [Тифани](https://twitter.com/TiffanySouterre) и [Мод](https://twitter.com/maudstweets) |
| 19 | Наука о подацима у облаку | [Облачни подаци](5-Data-Science-In-Cloud/README.md) | Распоређивање модела помоћу Azure Machine Learning Studio. | [лекција](5-Data-Science-In-Cloud/19-Azure/README.md)| [Тифани](https://twitter.com/TiffanySouterre) и [Мод](https://twitter.com/maudstweets) |
| 20 | Наука о подацима у стварном свету | [У стварном свету](6-Data-Science-In-Wild/README.md) | Пројекти вођени науком о подацима у стварном свету. | [лекција](6-Data-Science-In-Wild/20-Real-World-Examples/README.md) | [Нитија](https://twitter.com/nitya) |

## GitHub Codespaces

Пратите ове кораке да отворите овај пример у Codespace-у:
1. Кликните на падајући мени Code и изаберите опцију Open with Codespaces.
2. Изаберите + New codespace на дну панела.
За више информација, погледајте [GitHub документацију](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace).

## VSCode Remote - Containers
Пратите ове кораке да отворите овај репозиторијум у контејнеру користећи ваш локални рачунар и VSCode са екстензијом VS Code Remote - Containers:

1. Ако први пут користите развојни контејнер, уверите се да ваш систем испуњава предуслове (нпр. да имате инсталиран Docker) у [документацији за почетак](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started).

Да бисте користили овај репозиторијум, можете га отворити у изолованом Docker волумену:

**Напомена**: У позадини, ово ће користити Remote-Containers: **Clone Repository in Container Volume...** команду за клонирање изворног кода у Docker волумен уместо на локални фајл систем. [Волумени](https://docs.docker.com/storage/volumes/) су пожељан механизам за чување података контејнера.

Или отворите локално клонирану или преузету верзију репозиторијума:

- Клонирајте овај репозиторијум на ваш локални фајл систем.
- Притисните F1 и изаберите команду **Remote-Containers: Open Folder in Container...**.
- Изаберите клонирану копију ове фасцикле, сачекајте да се контејнер покрене и испробајте.

## Офлајн приступ

Можете покренути ову документацију офлајн користећи [Docsify](https://docsify.js.org/#/). Форкујте овај репозиторијум, [инсталирајте Docsify](https://docsify.js.org/#/quickstart) на ваш локални рачунар, а затим у корену овог репозиторијума укуцајте `docsify serve`. Веб-сајт ће бити доступан на порту 3000 на вашем локалном хосту: `localhost:3000`.

> Напомена, бележнице неће бити приказане преко Docsify-а, па када треба да покренете бележницу, урадите то одвојено у VS Code-у са Python језгром.

## Остали курикулуми

Наш тим производи и друге курикулуме! Погледајте:

- [Edge AI за почетнике](https://aka.ms/edgeai-for-beginners)
- [AI агенти за почетнике](https://aka.ms/ai-agents-beginners)
- [Генеративна AI за почетнике](https://aka.ms/genai-beginners)
- [Генеративна AI за почетнике .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet)
- [Генеративна AI са JavaScript-ом](https://github.com/microsoft/generative-ai-with-javascript)
- [Генеративна AI са Java-ом](https://aka.ms/genaijava)
- [AI за почетнике](https://aka.ms/ai-beginners)
- [Наука о подацима за почетнике](https://aka.ms/datascience-beginners)
- [Bash за почетнике](https://github.com/microsoft/bash-for-beginners)
- [Машинско учење за почетнике](https://aka.ms/ml-beginners)
- [Сајбер безбедност за почетнике](https://github.com/microsoft/Security-101) 
- [Веб развој за почетнике](https://aka.ms/webdev-beginners)
- [IoT за почетнике](https://aka.ms/iot-beginners)
- [Машинско учење за почетнике](https://aka.ms/ml-beginners)
- [XR развој за почетнике](https://aka.ms/xr-dev-for-beginners)
- [Савладавање GitHub Copilot-а за AI парно програмирање](https://aka.ms/GitHubCopilotAI)
- [XR развој за почетнике](https://github.com/microsoft/xr-development-for-beginners)
- [Савладавање GitHub Copilot-а за C#/.NET програмере](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers)
- [Изаберите своју авантуру са Copilot-ом](https://github.com/microsoft/CopilotAdventures)

## Добијање помоћи

Ако запнете или имате било каква питања о изградњи AI апликација, придружите се:

[![Azure AI Foundry Discord](https://img.shields.io/badge/Discord-Azure_AI_Foundry_Community_Discord-blue?style=for-the-badge&logo=discord&color=5865f2&logoColor=fff)](https://aka.ms/foundry/discord)

Ако имате повратне информације о производу или грешке током изградње, посетите:
[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

**Одрицање од одговорности**:  
Овај документ је преведен помоћу услуге за превођење уз помоћ вештачке интелигенције [Co-op Translator](https://github.com/Azure/co-op-translator). Иако се трудимо да обезбедимо тачност, молимо вас да имате у виду да аутоматски преводи могу садржати грешке или нетачности. Оригинални документ на његовом изворном језику треба сматрати меродавним извором. За критичне информације препоручује се професионални превод од стране људи. Не преузимамо одговорност за било каква погрешна тумачења или неспоразуме који могу настати услед коришћења овог превода.