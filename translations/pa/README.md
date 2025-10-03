<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "3beef650c5bafd70d88e2643a2b360fb",
  "translation_date": "2025-10-03T12:17:40+00:00",
  "source_file": "README.md",
  "language_code": "pa"
}
-->
# ਸ਼ੁਰੂਆਤੀ ਸਿਖਲਾਈ ਲਈ ਡਾਟਾ ਸਾਇੰਸ - ਇੱਕ ਪਾਠਕ੍ਰਮ

[![GitHub Codespaces ਵਿੱਚ ਖੋਲ੍ਹੋ](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=344191198)

[![GitHub ਲਾਇਸੈਂਸ](https://img.shields.io/github/license/microsoft/Data-Science-For-Beginners.svg)](https://github.com/microsoft/Data-Science-For-Beginners/blob/master/LICENSE)
[![GitHub ਯੋਗਦਾਨਕਰਤਾ](https://img.shields.io/github/contributors/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/graphs/contributors/)
[![GitHub ਮੁੱਦੇ](https://img.shields.io/github/issues/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/issues/)
[![GitHub ਪੁਲ-ਰਿਕਵੇਸਟ](https://img.shields.io/github/issues-pr/microsoft/Data-Science-For-Beginners.svg)](https://GitHub.com/microsoft/Data-Science-For-Beginners/pulls/)
[![PRs ਸਵਾਗਤ ਹੈ](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

[![GitHub ਦੇਖਣ ਵਾਲੇ](https://img.shields.io/github/watchers/microsoft/Data-Science-For-Beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/Data-Science-For-Beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/Data-Science-For-Beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/Data-Science-For-Beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/Data-Science-For-Beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/Data-Science-For-Beginners/stargazers/)

[![](https://dcbadge.vercel.app/api/server/ByRwuEEgH4)](https://discord.gg/zxKYvhSnVp?WT.mc_id=academic-000002-leestott)

[![Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

Microsoft ਦੇ Azure Cloud Advocates ਨੇ ਡਾਟਾ ਸਾਇੰਸ ਬਾਰੇ 10 ਹਫ਼ਤਿਆਂ ਦਾ, 20 ਪਾਠਾਂ ਦਾ ਪਾਠਕ੍ਰਮ ਪੇਸ਼ ਕਰਨ ਵਿੱਚ ਖੁਸ਼ੀ ਮਹਿਸੂਸ ਕੀਤੀ ਹੈ। ਹਰ ਪਾਠ ਵਿੱਚ ਪਾਠ ਤੋਂ ਪਹਿਲਾਂ ਅਤੇ ਬਾਅਦ ਦੇ ਪ੍ਰਸ਼ਨੋੱਤਰੀ, ਪਾਠ ਪੂਰਾ ਕਰਨ ਲਈ ਲਿਖਤ ਨਿਰਦੇਸ਼, ਇੱਕ ਹੱਲ ਅਤੇ ਇੱਕ ਅਸਾਈਨਮੈਂਟ ਸ਼ਾਮਲ ਹੈ। ਸਾਡੇ ਪ੍ਰੋਜੈਕਟ-ਅਧਾਰਤ ਪੈਡਾਗੌਜੀ ਤੁਹਾਨੂੰ ਸਿੱਖਣ ਦਿੰਦੀ ਹੈ ਜਦੋਂ ਤੁਸੀਂ ਕੁਝ ਬਣਾਉਂਦੇ ਹੋ, ਜੋ ਨਵੀਆਂ ਕੌਸ਼ਲਤਾਵਾਂ ਨੂੰ ਯਾਦ ਰੱਖਣ ਦਾ ਸਾਬਤ ਤਰੀਕਾ ਹੈ।

**ਸਾਡੇ ਲੇਖਕਾਂ ਨੂੰ ਦਿਲੋਂ ਧੰਨਵਾਦ:** [Jasmine Greenaway](https://www.twitter.com/paladique), [Dmitry Soshnikov](http://soshnikov.com), [Nitya Narasimhan](https://twitter.com/nitya), [Jalen McGee](https://twitter.com/JalenMcG), [Jen Looper](https://twitter.com/jenlooper), [Maud Levy](https://twitter.com/maudstweets), [Tiffany Souterre](https://twitter.com/TiffanySouterre), [Christopher Harrison](https://www.twitter.com/geektrainer)।

**🙏 ਵਿਸ਼ੇਸ਼ ਧੰਨਵਾਦ 🙏 ਸਾਡੇ [Microsoft Student Ambassador](https://studentambassadors.microsoft.com/) ਲੇਖਕਾਂ, ਸਮੀਖਿਆਕਾਰਾਂ ਅਤੇ ਸਮੱਗਰੀ ਯੋਗਦਾਨਕਰਤਾਵਾਂ ਨੂੰ,** ਖਾਸ ਤੌਰ 'ਤੇ Aaryan Arora, [Aditya Garg](https://github.com/AdityaGarg00), [Alondra Sanchez](https://www.linkedin.com/in/alondra-sanchez-molina/), [Ankita Singh](https://www.linkedin.com/in/ankitasingh007), [Anupam Mishra](https://www.linkedin.com/in/anupam--mishra/), [Arpita Das](https://www.linkedin.com/in/arpitadas01/), ChhailBihari Dubey, [Dibri Nsofor](https://www.linkedin.com/in/dibrinsofor), [Dishita Bhasin](https://www.linkedin.com/in/dishita-bhasin-7065281bb), [Majd Safi](https://www.linkedin.com/in/majd-s/), [Max Blum](https://www.linkedin.com/in/max-blum-6036a1186/), [Miguel Correa](https://www.linkedin.com/in/miguelmque/), [Mohamma Iftekher (Iftu) Ebne Jalal](https://twitter.com/iftu119), [Nawrin Tabassum](https://www.linkedin.com/in/nawrin-tabassum), [Raymond Wangsa Putra](https://www.linkedin.com/in/raymond-wp/), [Rohit Yadav](https://www.linkedin.com/in/rty2423), Samridhi Sharma, [Sanya Sinha](https://www.linkedin.com/mwlite/in/sanya-sinha-13aab1200),
[Sheena Narula](https://www.linkedin.com/in/sheena-narua-n/), [Tauqeer Ahmad](https://www.linkedin.com/in/tauqeerahmad5201/), Yogendrasingh Pawar , [Vidushi Gupta](https://www.linkedin.com/in/vidushi-gupta07/), [Jasleen Sondhi](https://www.linkedin.com/in/jasleen-sondhi/)।

|![@sketchthedocs ਦੁਆਰਾ ਬਣਾਈ ਗਈ ਸਕੈਚਨੋਟ https://sketchthedocs.dev](../../translated_images/00-Title.8af36cd35da1ac555b678627fbdc6e320c75f0100876ea41d30ea205d3b08d22.pa.png)|
|:---:|
| ਸ਼ੁਰੂਆਤੀ ਸਿਖਲਾਈ ਲਈ ਡਾਟਾ ਸਾਇੰਸ - _[@nitya](https://twitter.com/nitya) ਦੁਆਰਾ ਬਣਾਈ ਗਈ ਸਕੈਚਨੋਟ_ |

### 🌐 ਬਹੁਭਾਸ਼ਾਈ ਸਹਾਇਤਾ

#### GitHub Action ਰਾਹੀਂ ਸਹਾਇਕ (ਸਵੈਚਾਲਿਤ ਅਤੇ ਹਮੇਸ਼ਾ ਅਪ-ਟੂ-ਡੇਟ)

[ਫਰਾਂਸੀਸੀ](../fr/README.md) | [ਸਪੇਨੀ](../es/README.md) | [ਜਰਮਨ](../de/README.md) | [ਰੂਸੀ](../ru/README.md) | [ਅਰਬੀ](../ar/README.md) | [ਫ਼ਾਰਸੀ](../fa/README.md) | [ਉਰਦੂ](../ur/README.md) | [ਚੀਨੀ (ਸਰਲ)](../zh/README.md) | [ਚੀਨੀ (ਪਾਰੰਪਰਿਕ, ਮਕਾਉ)](../mo/README.md) | [ਚੀਨੀ (ਪਾਰੰਪਰਿਕ, ਹਾਂਗਕਾਂਗ)](../hk/README.md) | [ਚੀਨੀ (ਪਾਰੰਪਰਿਕ, ਤਾਈਵਾਨ)](../tw/README.md) | [ਜਾਪਾਨੀ](../ja/README.md) | [ਕੋਰੀਆਈ](../ko/README.md) | [ਹਿੰਦੀ](../hi/README.md) | [ਬੰਗਾਲੀ](../bn/README.md) | [ਮਰਾਠੀ](../mr/README.md) | [ਨੇਪਾਲੀ](../ne/README.md) | [ਪੰਜਾਬੀ (ਗੁਰਮੁਖੀ)](./README.md) | [ਪੁਰਤਗਾਲੀ (ਪੁਰਤਗਾਲ)](../pt/README.md) | [ਪੁਰਤਗਾਲੀ (ਬ੍ਰਾਜ਼ੀਲ)](../br/README.md) | [ਇਟਾਲਵੀ](../it/README.md) | [ਪੋਲੈਂਡੀ](../pl/README.md) | [ਤੁਰਕੀ](../tr/README.md) | [ਯੂਨਾਨੀ](../el/README.md) | [ਥਾਈ](../th/README.md) | [ਸਵੀਡਿਸ਼](../sv/README.md) | [ਡੈਨਿਸ਼](../da/README.md) | [ਨਾਰਵੇਜੀਅਨ](../no/README.md) | [ਫਿਨਿਸ਼](../fi/README.md) | [ਡੱਚ](../nl/README.md) | [ਹਿਬਰੂ](../he/README.md) | [ਵਿਯਤਨਾਮੀ](../vi/README.md) | [ਇੰਡੋਨੇਸ਼ੀਆਈ](../id/README.md) | [ਮਲੇ](../ms/README.md) | [ਟੈਗਾਲੋਗ (ਫਿਲੀਪੀਨੋ)](../tl/README.md) | [ਸਵਾਹਿਲੀ](../sw/README.md) | [ਹੰਗਰੀ](../hu/README.md) | [ਚੈਕ](../cs/README.md) | [ਸਲੋਵਾਕ](../sk/README.md) | [ਰੋਮਾਨੀ](../ro/README.md) | [ਬੁਲਗਾਰੀਆਈ](../bg/README.md) | [ਸਰਬੀ (ਸਿਰਿਲਿਕ)](../sr/README.md) | [ਕ੍ਰੋਏਸ਼ੀਆਈ](../hr/README.md) | [ਸਲੋਵੇਨੀਆਈ](../sl/README.md) | [ਯੂਕਰੇਨੀ](../uk/README.md) | [ਬਰਮੀ (ਮਿਆਂਮਾਰ)](../my/README.md)

**ਜੇ ਤੁਸੀਂ ਹੋਰ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅਨੁਵਾਦ ਕਰਵਾਉਣਾ ਚਾਹੁੰਦੇ ਹੋ, ਤਾਂ ਸਹਾਇਕ ਭਾਸ਼ਾਵਾਂ ਦੀ ਸੂਚੀ [ਇੱਥੇ](https://github.com/Azure/co-op-translator/blob/main/getting_started/supported-languages.md) ਉਪਲਬਧ ਹੈ।**

#### ਸਾਡੇ ਸਮੁਦਾਇ ਵਿੱਚ ਸ਼ਾਮਲ ਹੋਵੋ 
[![Azure AI Discord](https://dcbadge.limes.pink/api/server/kzRShWzttr)](https://aka.ms/ds4beginners/discord)

ਸਾਡੇ ਕੋਲ ਇੱਕ Discord 'Learn with AI' ਸਿਰੀਜ਼ ਚੱਲ ਰਹੀ ਹੈ। ਹੋਰ ਜਾਣੋ ਅਤੇ ਸਾਡੇ ਨਾਲ [Learn with AI Series](https://aka.ms/learnwithai/discord) ਵਿੱਚ 18 - 30 ਸਤੰਬਰ, 2025 ਤੱਕ ਸ਼ਾਮਲ ਹੋਵੋ। ਤੁਹਾਨੂੰ GitHub Copilot ਨੂੰ ਡਾਟਾ ਸਾਇੰਸ ਲਈ ਵਰਤਣ ਦੇ ਟਿੱਪਸ ਅਤੇ ਟ੍ਰਿਕਸ ਮਿਲਣਗੇ।

![Learn with AI series](../../translated_images/1.2b28cdc6205e26fef6a21817fe5d83ae8b50fbd0a33e9fed0df05845da5b30b6.pa.jpg)

# ਕੀ ਤੁਸੀਂ ਵਿਦਿਆਰਥੀ ਹੋ?

ਹੇਠਾਂ ਦਿੱਤੇ ਸਰੋਤਾਂ ਨਾਲ ਸ਼ੁਰੂ ਕਰੋ:

- [ਵਿਦਿਆਰਥੀ ਹੱਬ ਪੇਜ](https://docs.microsoft.com/en-gb/learn/student-hub?WT.mc_id=academic-77958-bethanycheum) ਇਸ ਪੇਜ 'ਤੇ ਤੁਹਾਨੂੰ ਸ਼ੁਰੂਆਤੀ ਸਰੋਤ, ਵਿਦਿਆਰਥੀ ਪੈਕ ਅਤੇ ਇੱਥੋਂ ਤੱਕ ਕਿ ਮੁਫ਼ਤ ਸਰਟੀਫਿਕੇਟ ਵਾਊਚਰ ਪ੍ਰਾਪਤ ਕਰਨ ਦੇ ਤਰੀਕੇ ਮਿਲਣਗੇ। ਇਹ ਇੱਕ ਪੇਜ ਹੈ ਜਿਸਨੂੰ ਤੁਸੀਂ ਬੁੱਕਮਾਰਕ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ ਅਤੇ ਸਮੇਂ-ਸਮੇਂ 'ਤੇ ਚੈੱਕ ਕਰਨਾ ਚਾਹੁੰਦੇ ਹੋ ਕਿਉਂਕਿ ਅਸੀਂ ਘੱਟੋ-ਘੱਟ ਮਹੀਨਾਵਾਰ ਸਮੱਗਰੀ ਬਦਲਦੇ ਹਾਂ।
- [Microsoft Learn Student Ambassadors](https://studentambassadors.microsoft.com?WT.mc_id=academic-77958-bethanycheum) ਵਿਦਿਆਰਥੀ ਰਾਜਦੂਤਾਂ ਦੇ ਗਲੋਬਲ ਸਮੁਦਾਇ ਵਿੱਚ ਸ਼ਾਮਲ ਹੋਵੋ, ਇਹ Microsoft ਵਿੱਚ ਦਾਖਲ ਹੋਣ ਦਾ ਤੁਹਾਡਾ ਤਰੀਕਾ ਹੋ ਸਕਦਾ ਹੈ।

# ਸ਼ੁਰੂਆਤ ਕਰਨਾ

> **ਪੂਰੀ ਤਰ੍ਹਾਂ ਸ਼ੁਰੂਆਤੀ**: ਡਾਟਾ ਸਾਇੰਸ ਵਿੱਚ ਨਵੇਂ ਹੋ? ਸਾਡੇ [ਸ਼ੁਰੂਆਤੀ-ਮਿੱਤਰ ਉਦਾਹਰਣਾਂ](examples/README.md) ਨਾਲ ਸ਼ੁਰੂ ਕਰੋ! ਇਹ ਸਧਾਰਨ, ਵਧੀਆ ਟਿੱਪਣੀ ਕੀਤੇ ਉਦਾਹਰਣ ਤੁਹਾਨੂੰ ਪੂਰੇ ਪਾਠਕ੍ਰਮ ਵਿੱਚ ਡੁੱਬਣ ਤੋਂ ਪਹਿਲਾਂ ਬੁਨਿਆਦੀ ਗੱਲਾਂ ਸਮਝਣ ਵਿੱਚ ਮਦਦ ਕਰਨਗੇ।

> **ਅਧਿਆਪਕਾਂ ਲਈ**: ਅਸੀਂ ਇਸ ਪਾਠਕ੍ਰਮ ਨੂੰ ਵਰਤਣ ਲਈ ਕੁਝ [ਸੁਝਾਵ ਸ਼ਾਮਲ ਕੀਤੇ ਹਨ](for-teachers.md)। ਅਸੀਂ ਤੁਹਾਡਾ ਫੀਡਬੈਕ [ਸਾਡੇ ਚਰਚਾ ਫੋਰਮ](https://github.com/microsoft/Data-Science-For-Beginners/discussions) ਵਿੱਚ ਪਸੰਦ ਕਰਾਂਗੇ!

> **[ਵਿਦਿਆਰਥੀ](https://aka.ms/student-page)**: ਇਸ ਪਾਠਕ੍ਰਮ ਨੂੰ ਆਪਣੇ ਆਪ ਵਰਤਣ ਲਈ, ਪੂਰੇ ਰਿਪੋਜ਼ਟਰੀ ਨੂੰ ਫੋਰਕ ਕਰੋ ਅਤੇ ਆਪਣੇ ਆਪ ਅਭਿਆਸ ਪੂਰੇ ਕਰੋ, ਪਾਠ ਤੋਂ ਪਹਿਲਾਂ ਪ੍ਰਸ਼ਨੋੱਤਰੀ ਨਾਲ ਸ਼ੁਰੂ ਕਰੋ। ਫਿਰ ਲੈਕਚਰ ਪੜ੍ਹੋ ਅਤੇ ਬਾਕੀ ਦੀਆਂ ਗਤੀਵਿਧੀਆਂ ਪੂਰੀਆਂ ਕਰੋ। ਪ੍ਰੋਜੈਕਟ ਬਣਾਉਣ ਦੀ ਕੋਸ਼ਿਸ਼ ਕਰੋ ਪਾਠਾਂ ਨੂੰ ਸਮਝ ਕੇ, ਨਾ ਕਿ ਹੱਲ ਕੋਡ ਨੂੰ ਕਾਪੀ ਕਰਕੇ; ਹਾਲਾਂਕਿ, ਉਹ ਕੋਡ ਹਰ ਪ੍ਰੋਜੈਕਟ-ਅਧਾਰਤ ਪਾਠ ਵਿੱਚ /solutions ਫੋਲਡਰਾਂ ਵਿੱਚ ਉਪਲਬਧ ਹੈ। ਇੱਕ ਹੋਰ ਵਿਚਾਰ ਇਹ ਹੋ ਸਕਦਾ ਹੈ ਕਿ ਦੋਸਤਾਂ ਨਾਲ ਇੱਕ ਅਧਿਐਨ ਸਮੂਹ ਬਣਾਓ ਅਤੇ ਸਮੱਗਰੀ ਨੂੰ ਇਕੱਠੇ ਪੜ੍ਹੋ। ਹੋਰ ਅਧਿਐਨ ਲਈ, ਅਸੀਂ [Microsoft Learn](https://docs.microsoft.com/en-us/users/jenlooper-2911/collections/qprpajyoy3x0g7?WT.mc_id=academic-77958-bethanycheum) ਦੀ ਸਿਫਾਰਸ਼ ਕਰਦੇ ਹਾਂ।

## ਟੀਮ ਨਾਲ ਮਿਲੋ

[![ਪ੍ਰੋਮੋ ਵੀਡੀਓ](../../ds-for-beginners.gif)](https://youtu.be/8mzavjQSMM4 "ਪ੍ਰੋਮੋ ਵੀਡੀਓ")

**Gif ਦੁਆਰਾ** [Mohit Jaisal](https://www.linkedin.com/in/mohitjaisal)

> 🎥 ਉੱਪਰ ਦਿੱਤੀ ਚਿੱਤਰ 'ਤੇ ਕਲਿੱਕ ਕਰੋ ਪ੍ਰੋਜੈਕਟ ਅਤੇ ਇਸਨੂੰ ਬਣਾਉਣ ਵਾਲੇ ਲੋਕਾਂ ਬਾਰੇ ਜਾਣਨ ਲਈ!

## ਪੈਡਾਗੌਜੀ

ਅਸੀਂ ਇਸ ਪਾਠਕ੍ਰਮ ਨੂੰ ਬਣਾਉਂਦੇ ਸਮੇਂ ਦੋ ਪੈਡਾਗੌਜੀਕਲ ਸਿਧਾਂਤਾਂ ਨੂੰ ਚੁਣਿਆ ਹੈ: ਇਹ ਯਕੀਨੀ ਬਣਾਉਣਾ ਕਿ ਇਹ ਪ੍ਰੋਜੈਕਟ-ਅਧਾਰਤ ਹੈ ਅਤੇ ਇਸ ਵਿੱਚ ਵਾਰੰ-ਵਾਰ ਪ੍ਰਸ਼ਨੋੱਤਰੀ ਸ਼ਾਮਲ ਹਨ। ਇਸ ਲੜੀ ਦੇ ਅੰਤ ਤੱਕ, ਵਿਦਿਆਰਥੀ ਡਾਟਾ ਸਾਇੰਸ ਦੇ ਮੁੱਢਲੇ ਸਿਧਾਂਤਾਂ ਨੂੰ ਸਿੱਖ ਲੈਣਗੇ, ਜਿਸ ਵਿੱਚ ਨੈਤਿਕ ਧਾਰਨਾਵਾਂ, ਡਾਟਾ ਤਿਆਰੀ, ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨ ਦੇ ਵੱਖ-ਵੱਖ ਤਰੀਕੇ, ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ, ਡਾਟਾ ਵਿਸ਼ਲੇਸ਼ਣ, ਡਾਟਾ ਸਾਇੰਸ ਦੇ ਅਸਲ-ਜਗਤ ਦੇ ਉਪਯੋਗ ਅਤੇ ਹੋਰ ਬਹੁਤ ਕੁਝ ਸ਼ਾਮਲ ਹਨ।

ਇਸ ਤੋਂ ਇਲਾਵਾ, ਕਲਾਸ ਤੋਂ ਪਹਿਲਾਂ ਇੱਕ ਘੱਟ-ਦਬਾਅ ਵਾਲੀ ਪ੍ਰਸ਼ਨੋੱਤਰੀ ਵਿਦਿਆਰਥੀ ਨੂੰ ਵਿਸ਼ੇ ਨੂੰ ਸਿੱਖਣ ਵੱਲ ਧਿਆਨ ਕੇਂਦਰਿਤ ਕਰਨ ਲਈ ਪ੍ਰੇਰਿਤ ਕਰਦੀ ਹੈ, ਜਦਕਿ ਕਲਾਸ ਤੋਂ ਬਾਅਦ ਦੀ ਦੂਜੀ ਪ੍ਰਸ਼ਨੋੱਤਰੀ ਹੋਰ ਯਾਦਗਾਰੀ ਯਕੀਨੀ ਬਣਾਉਂਦੀ ਹੈ। ਇਹ ਪਾਠਕ੍ਰਮ ਲਚਕੀਲਾ ਅਤੇ ਮਨੋਰੰਜਕ ਬਣਾਇਆ ਗਿਆ ਹੈ ਅਤੇ ਇਸਨੂੰ ਪੂਰਾ ਜਾਂ ਹਿੱਸੇ ਵਿੱਚ ਲਿਆ ਜਾ ਸਕਦਾ ਹੈ। ਪ੍ਰੋਜੈਕਟ ਛੋਟੇ ਸ਼ੁਰੂ ਹੁੰਦੇ ਹਨ ਅਤੇ 10 ਹਫ਼ਤਿਆਂ ਦੇ ਚੱਕਰ ਦੇ ਅੰਤ ਤੱਕ ਵਧੇਰੇ ਜਟਿਲ ਹੋ ਜਾਂਦੇ ਹਨ।

> ਸਾਡੇ [Code of Conduct](CODE_OF_CONDUCT.md), [Contributing](CONTRIBUTING.md), [Translation](TRANSLATIONS.md) ਨਿਰਦੇਸ਼ਾਂ ਨੂੰ ਵੇਖੋ। ਅਸੀਂ ਤੁਹਾਡਾ ਰਚਨਾਤਮਕ ਫੀਡਬੈਕ ਸਵਾਗਤ ਕਰਦੇ ਹਾਂ!

## ਹਰ ਪਾਠ ਵਿੱਚ ਸ਼ਾਮਲ ਹੈ:

- ਵਿਕਲਪਿਕ ਸਕੈਚਨੋਟ
- ਵਿਕਲਪਿਕ ਪੂਰਕ ਵੀਡੀਓ
- ਪਾਠ ਤੋਂ ਪਹਿਲਾਂ ਵਾਰਮਅੱਪ ਪ੍ਰਸ਼ਨੋੱਤਰੀ
- ਲਿਖਤ ਪਾਠ
- ਪ੍ਰੋਜੈਕਟ-ਅਧਾਰਤ ਪਾਠਾਂ ਲਈ, ਪ੍ਰੋਜੈਕਟ ਬਣਾਉਣ ਲਈ ਕਦਮ-ਦਰ-ਕਦਮ ਗਾਈਡ
- ਗਿਆਨ ਜਾਂਚ
- ਇੱਕ ਚੁਣੌਤੀ
- ਪੂਰਕ ਪਾਠਨ
- ਅਸਾਈਨਮੈਂਟ
- [ਪਾਠ ਤੋਂ ਬਾਅਦ ਦੀ ਪ੍ਰਸ਼
> **ਕੁਇਜ਼ਾਂ ਬਾਰੇ ਇੱਕ ਨੋਟ**: ਸਾਰੀਆਂ ਕੁਇਜ਼ਾਂ Quiz-App ਫੋਲਡਰ ਵਿੱਚ ਹਨ, ਜਿੱਥੇ ਕੁੱਲ 40 ਕੁਇਜ਼ ਹਨ, ਹਰ ਇੱਕ ਵਿੱਚ ਤਿੰਨ ਪ੍ਰਸ਼ਨ ਹਨ। ਇਹ ਪਾਠਾਂ ਵਿੱਚੋਂ ਲਿੰਕ ਕੀਤੀਆਂ ਗਈਆਂ ਹਨ, ਪਰ ਕੁਇਜ਼ ਐਪ ਨੂੰ ਸਥਾਨਕ ਤੌਰ 'ਤੇ ਚਲਾਇਆ ਜਾ ਸਕਦਾ ਹੈ ਜਾਂ Azure 'ਤੇ ਡਿਪਲੌਇ ਕੀਤਾ ਜਾ ਸਕਦਾ ਹੈ; `quiz-app` ਫੋਲਡਰ ਵਿੱਚ ਦਿੱਤੇ ਨਿਰਦੇਸ਼ਾਂ ਦੀ ਪਾਲਣਾ ਕਰੋ। ਇਹ ਹੌਲੀ-ਹੌਲੀ ਸਥਾਨਕ ਭਾਸ਼ਾਵਾਂ ਵਿੱਚ ਅਨੁਵਾਦਿਤ ਕੀਤੀਆਂ ਜਾ ਰਹੀਆਂ ਹਨ।

## 🎓 ਸ਼ੁਰੂਆਤੀ ਲਈ ਆਸਾਨ ਉਦਾਹਰਨਾਂ

**ਡਾਟਾ ਸਾਇੰਸ ਵਿੱਚ ਨਵੇਂ ਹੋ?** ਅਸੀਂ ਇੱਕ ਵਿਸ਼ੇਸ਼ [examples directory](examples/README.md) ਬਣਾਈ ਹੈ ਜਿਸ ਵਿੱਚ ਸਧਾਰਨ, ਵਧੀਆ ਟਿੱਪਣੀਆਂ ਵਾਲਾ ਕੋਡ ਹੈ ਜੋ ਤੁਹਾਨੂੰ ਸ਼ੁਰੂਆਤ ਕਰਨ ਵਿੱਚ ਮਦਦ ਕਰੇਗਾ:

- 🌟 **ਹੈਲੋ ਵਰਲਡ** - ਤੁਹਾਡਾ ਪਹਿਲਾ ਡਾਟਾ ਸਾਇੰਸ ਪ੍ਰੋਗਰਾਮ
- 📂 **ਡਾਟਾ ਲੋਡ ਕਰਨਾ** - ਡਾਟਾਸੈਟ ਨੂੰ ਪੜ੍ਹਨ ਅਤੇ ਖੋਜ ਕਰਨ ਦਾ ਸਿਖੋ
- 📊 **ਸਧਾਰਨ ਵਿਸ਼ਲੇਸ਼ਣ** - ਅੰਕੜੇ ਗਣਨਾ ਕਰੋ ਅਤੇ ਪੈਟਰਨ ਲੱਭੋ
- 📈 **ਮੁੱਢਲੀ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ** - ਚਾਰਟ ਅਤੇ ਗ੍ਰਾਫ ਬਣਾਓ
- 🔬 **ਅਸਲ-ਜਗਤ ਪ੍ਰੋਜੈਕਟ** - ਸ਼ੁਰੂ ਤੋਂ ਅੰਤ ਤੱਕ ਪੂਰਾ ਵਰਕਫਲੋ

ਹਰ ਉਦਾਹਰਨ ਵਿੱਚ ਹਰ ਕਦਮ ਦੀ ਵਿਸਥਾਰ ਨਾਲ ਟਿੱਪਣੀ ਸ਼ਾਮਲ ਹੈ, ਜੋ ਇਸਨੂੰ ਬਿਲਕੁਲ ਸ਼ੁਰੂਆਤੀ ਲਈ ਬਹੁਤ ਹੀ ਉਚਿਤ ਬਣਾਉਂਦਾ ਹੈ!

👉 **[ਉਦਾਹਰਨਾਂ ਨਾਲ ਸ਼ੁਰੂ ਕਰੋ](examples/README.md)** 👈

## ਪਾਠ

|![ Sketchnote by @sketchthedocs https://sketchthedocs.dev](../../translated_images/00-Roadmap.4905d6567dff47532b9bfb8e0b8980fc6b0b1292eebb24181c1a9753b33bc0f5.pa.png)|
|:---:|
| ਡਾਟਾ ਸਾਇੰਸ ਸ਼ੁਰੂਆਤੀਆਂ ਲਈ: ਰੋਡਮੈਪ - _[@nitya](https://twitter.com/nitya) ਦੁਆਰਾ ਸਕੈਚਨੋਟ_ |

| ਪਾਠ ਨੰਬਰ | ਵਿਸ਼ਾ | ਪਾਠ ਸਮੂਹ | ਸਿੱਖਣ ਦੇ ਉਦੇਸ਼ | ਲਿੰਕ ਕੀਤਾ ਪਾਠ | ਲੇਖਕ |
| :-----------: | :----------------------------------------: | :--------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------: | :----: |
| 01 | ਡਾਟਾ ਸਾਇੰਸ ਦੀ ਪਰਿਭਾਸ਼ਾ | [ਪ੍ਰਸਤਾਵਨਾ](1-Introduction/README.md) | ਡਾਟਾ ਸਾਇੰਸ ਦੇ ਮੁੱਢਲੇ ਧਾਰਨਾ ਸਿੱਖੋ ਅਤੇ ਇਹ ਕਿਵੇਂ ਕ੍ਰਿਤ੍ਰਿਮ ਬੁੱਧੀ, ਮਸ਼ੀਨ ਲਰਨਿੰਗ ਅਤੇ ਵੱਡੇ ਡਾਟਾ ਨਾਲ ਸੰਬੰਧਿਤ ਹੈ। | [ਪਾਠ](1-Introduction/01-defining-data-science/README.md) [ਵੀਡੀਓ](https://youtu.be/beZ7Mb_oz9I) | [Dmitry](http://soshnikov.com) |
| 02 | ਡਾਟਾ ਸਾਇੰਸ ਨੈਤਿਕਤਾ | [ਪ੍ਰਸਤਾਵਨਾ](1-Introduction/README.md) | ਡਾਟਾ ਨੈਤਿਕਤਾ ਦੇ ਧਾਰਨਾ, ਚੁਣੌਤੀਆਂ ਅਤੇ ਫਰੇਮਵਰਕ। | [ਪਾਠ](1-Introduction/02-ethics/README.md) | [Nitya](https://twitter.com/nitya) |
| 03 | ਡਾਟਾ ਦੀ ਪਰਿਭਾਸ਼ਾ | [ਪ੍ਰਸਤਾਵਨਾ](1-Introduction/README.md) | ਡਾਟਾ ਕਿਵੇਂ ਵਰਗਬੱਧ ਕੀਤਾ ਜਾਂਦਾ ਹੈ ਅਤੇ ਇਸਦੇ ਆਮ ਸਰੋਤ। | [ਪਾਠ](1-Introduction/03-defining-data/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 04 | ਅੰਕੜੇ ਅਤੇ ਸੰਭਾਵਨਾ ਦਾ ਪ੍ਰਸਤਾਵਨਾ | [ਪ੍ਰਸਤਾਵਨਾ](1-Introduction/README.md) | ਡਾਟਾ ਨੂੰ ਸਮਝਣ ਲਈ ਸੰਭਾਵਨਾ ਅਤੇ ਅੰਕੜੇ ਦੇ ਗਣਿਤਕ ਤਕਨੀਕਾਂ। | [ਪਾਠ](1-Introduction/04-stats-and-probability/README.md) [ਵੀਡੀਓ](https://youtu.be/Z5Zy85g4Yjw) | [Dmitry](http://soshnikov.com) |
| 05 | ਰਿਲੇਸ਼ਨਲ ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ | [ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ](2-Working-With-Data/README.md) | ਰਿਲੇਸ਼ਨਲ ਡਾਟਾ ਦਾ ਪ੍ਰਸਤਾਵਨਾ ਅਤੇ ਸਟ੍ਰਕਚਰਡ ਕਵੈਰੀ ਲੈਂਗਵੇਜ (SQL) ਦੀ ਮਦਦ ਨਾਲ ਰਿਲੇਸ਼ਨਲ ਡਾਟਾ ਦੀ ਖੋਜ ਅਤੇ ਵਿਸ਼ਲੇਸ਼ਣ ਦੇ ਮੁੱਢਲੇ ਧਾਰਨਾ। | [ਪਾਠ](2-Working-With-Data/05-relational-databases/README.md) | [Christopher](https://www.twitter.com/geektrainer) | | |
| 06 | NoSQL ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ | [ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ](2-Working-With-Data/README.md) | ਗੈਰ-ਰਿਲੇਸ਼ਨਲ ਡਾਟਾ ਦਾ ਪ੍ਰਸਤਾਵਨਾ, ਇਸਦੇ ਵੱਖ-ਵੱਖ ਕਿਸਮਾਂ ਅਤੇ ਦਸਤਾਵੇਜ਼ ਡਾਟਾਬੇਸ ਦੀ ਖੋਜ ਅਤੇ ਵਿਸ਼ਲੇਸ਼ਣ ਦੇ ਮੁੱਢਲੇ ਧਾਰਨਾ। | [ਪਾਠ](2-Working-With-Data/06-non-relational/README.md) | [Jasmine](https://twitter.com/paladique)|
| 07 | Python ਨਾਲ ਕੰਮ ਕਰਨਾ | [ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ](2-Working-With-Data/README.md) | Pandas ਵਰਗੀਆਂ ਲਾਇਬ੍ਰੇਰੀਆਂ ਦੀ ਮਦਦ ਨਾਲ ਡਾਟਾ ਦੀ ਖੋਜ ਲਈ Python ਦੀ ਵਰਤੋਂ ਦੇ ਮੁੱਢਲੇ ਧਾਰਨਾ। Python ਪ੍ਰੋਗਰਾਮਿੰਗ ਦੀ ਮੁੱਢਲੀ ਸਮਝ ਸਿਫਾਰਸ਼ੀ ਹੈ। | [ਪਾਠ](2-Working-With-Data/07-python/README.md) [ਵੀਡੀਓ](https://youtu.be/dZjWOGbsN4Y) | [Dmitry](http://soshnikov.com) |
| 08 | ਡਾਟਾ ਤਿਆਰੀ | [ਡਾਟਾ ਨਾਲ ਕੰਮ ਕਰਨਾ](2-Working-With-Data/README.md) | ਗੁੰਝਲਦਾਰ, ਗਲਤ ਜਾਂ ਅਧੂਰੇ ਡਾਟਾ ਨੂੰ ਹੱਲ ਕਰਨ ਲਈ ਡਾਟਾ ਸਾਫ ਕਰਨ ਅਤੇ ਰੂਪਾਂਤਰਿਤ ਕਰਨ ਦੀਆਂ ਤਕਨੀਕਾਂ। | [ਪਾਠ](2-Working-With-Data/08-data-preparation/README.md) | [Jasmine](https://www.twitter.com/paladique) |
| 09 | ਮਾਤਰਾ ਦੀ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ | [ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ](3-Data-Visualization/README.md) | 🦆 ਪੰਛੀਆਂ ਦੇ ਡਾਟਾ ਨੂੰ ਵਿਜੁਅਲਾਈਜ਼ ਕਰਨ ਲਈ Matplotlib ਦੀ ਵਰਤੋਂ ਸਿੱਖੋ। | [ਪਾਠ](3-Data-Visualization/09-visualization-quantities/README.md) | [Jen](https://twitter.com/jenlooper) |
| 10 | ਡਾਟਾ ਦੇ ਵੰਡ ਦੀ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ | [ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ](3-Data-Visualization/README.md) | ਇੱਕ ਅੰਤਰਾਲ ਵਿੱਚ ਅਵਲੋਕਨ ਅਤੇ ਰੁਝਾਨਾਂ ਨੂੰ ਵਿਜੁਅਲਾਈਜ਼ ਕਰਨਾ। | [ਪਾਠ](3-Data-Visualization/10-visualization-distributions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 11 | ਅਨੁਪਾਤਾਂ ਦੀ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ | [ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ](3-Data-Visualization/README.md) | ਵਿਸ਼ੇਸ਼ ਅਤੇ ਸਮੂਹਬੱਧ ਪ੍ਰਤੀਸ਼ਤਾਂ ਨੂੰ ਵਿਜੁਅਲਾਈਜ਼ ਕਰਨਾ। | [ਪਾਠ](3-Data-Visualization/11-visualization-proportions/README.md) | [Jen](https://twitter.com/jenlooper) |
| 12 | ਸੰਬੰਧਾਂ ਦੀ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ | [ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ](3-Data-Visualization/README.md) | ਡਾਟਾ ਦੇ ਸੈੱਟ ਅਤੇ ਉਨ੍ਹਾਂ ਦੇ ਵੈਰੀਏਬਲਾਂ ਦੇ ਵਿਚਕਾਰ ਸੰਬੰਧਾਂ ਅਤੇ ਸਹਸੰਬੰਧਾਂ ਨੂੰ ਵਿਜੁਅਲਾਈਜ਼ ਕਰਨਾ। | [ਪਾਠ](3-Data-Visualization/12-visualization-relationships/README.md) | [Jen](https://twitter.com/jenlooper) |
| 13 | ਅਰਥਪੂਰਨ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ | [ਡਾਟਾ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ](3-Data-Visualization/README.md) | ਸਮੱਸਿਆ ਹੱਲ ਕਰਨ ਅਤੇ ਅੰਕੜਿਆਂ ਤੋਂ ਅੰਦਰੂਨੀ ਜਾਣਕਾਰੀ ਪ੍ਰਾਪਤ ਕਰਨ ਲਈ ਤੁਹਾਡੇ ਵਿਜੁਅਲਾਈਜ਼ੇਸ਼ਨ ਨੂੰ ਕੀਮਤੀ ਬਣਾਉਣ ਲਈ ਤਕਨੀਕਾਂ ਅਤੇ ਮਾਰਗਦਰਸ਼ਨ। | [ਪਾਠ](3-Data-Visualization/13-meaningful-visualizations/README.md) | [Jen](https://twitter.com/jenlooper) |
| 14 | ਡਾਟਾ ਸਾਇੰਸ ਲਾਈਫਸਾਈਕਲ ਦਾ ਪ੍ਰਸਤਾਵਨਾ | [ਲਾਈਫਸਾਈਕਲ](4-Data-Science-Lifecycle/README.md) | ਡਾਟਾ ਸਾਇੰਸ ਲਾਈਫਸਾਈਕਲ ਦਾ ਪ੍ਰਸਤਾਵਨਾ ਅਤੇ ਡਾਟਾ ਪ੍ਰਾਪਤ ਕਰਨ ਅਤੇ ਕੱਢਣ ਦਾ ਪਹਿਲਾ ਕਦਮ। | [ਪਾਠ](4-Data-Science-Lifecycle/14-Introduction/README.md) | [Jasmine](https://twitter.com/paladique) |
| 15 | ਵਿਸ਼ਲੇਸ਼ਣ | [ਲਾਈਫਸਾਈਕਲ](4-Data-Science-Lifecycle/README.md) | ਡਾਟਾ ਸਾਇੰਸ ਲਾਈਫਸਾਈਕਲ ਦਾ ਇਹ ਚਰਨ ਡਾਟਾ ਨੂੰ ਵਿਸ਼ਲੇਸ਼ਣ ਕਰਨ ਦੀਆਂ ਤਕਨੀਕਾਂ 'ਤੇ ਧਿਆਨ ਕੇਂਦ੍ਰਿਤ ਕਰਦਾ ਹੈ। | [ਪਾਠ](4-Data-Science-Lifecycle/15-analyzing/README.md) | [Jasmine](https://twitter.com/paladique) | | |
| 16 | ਸੰਚਾਰ | [ਲਾਈਫਸਾਈਕਲ](4-Data-Science-Lifecycle/README.md) | ਡਾਟਾ ਤੋਂ ਪ੍ਰਾਪਤ ਅੰਦਰੂਨੀ ਜਾਣਕਾਰੀ ਨੂੰ ਇਸ ਤਰੀਕੇ ਨਾਲ ਪੇਸ਼ ਕਰਨ 'ਤੇ ਧਿਆਨ ਕੇਂਦ੍ਰਿਤ ਕਰਦਾ ਹੈ ਜੋ ਫੈਸਲੇ ਕਰਨ ਵਾਲਿਆਂ ਲਈ ਸਮਝਣਾ ਆਸਾਨ ਬਣਾਉਂਦਾ ਹੈ। | [ਪਾਠ](4-Data-Science-Lifecycle/16-communication/README.md) | [Jalen](https://twitter.com/JalenMcG) | | |
| 17 | ਕਲਾਉਡ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ | [ਕਲਾਉਡ ਡਾਟਾ](5-Data-Science-In-Cloud/README.md) | ਕਲਾਉਡ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ ਅਤੇ ਇਸਦੇ ਫਾਇਦਿਆਂ ਦਾ ਪ੍ਰਸਤਾਵਨਾ। | [ਪਾਠ](5-Data-Science-In-Cloud/17-Introduction/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) ਅਤੇ [Maud](https://twitter.com/maudstweets) |
| 18 | ਕਲਾਉਡ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ | [ਕਲਾਉਡ ਡਾਟਾ](5-Data-Science-In-Cloud/README.md) | ਘੱਟ ਕੋਡ ਵਾਲੇ ਟੂਲਾਂ ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਮਾਡਲਾਂ ਨੂੰ ਟ੍ਰੇਨ ਕਰਨਾ। |[ਪਾਠ](5-Data-Science-In-Cloud/18-Low-Code/README.md) | [Tiffany](https://twitter.com/TiffanySouterre) ਅਤੇ [Maud](https://twitter.com/maudstweets) |
| 19 | ਕਲਾਉਡ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ | [ਕਲਾਉਡ ਡਾਟਾ](5-Data-Science-In-Cloud/README.md) | Azure Machine Learning Studio ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਮਾਡਲਾਂ ਨੂੰ ਡਿਪਲੌਇ ਕਰਨਾ। | [ਪਾਠ](5-Data-Science-In-Cloud/19-Azure/README.md)| [Tiffany](https://twitter.com/TiffanySouterre) ਅਤੇ [Maud](https://twitter.com/maudstweets) |
| 20 | ਜੰਗਲੀ ਹਾਲਾਤ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ | [ਜੰਗਲੀ ਹਾਲਾਤ](6-Data-Science-In-Wild/README.md) | ਅਸਲ ਜਗਤ ਵਿੱਚ ਡਾਟਾ ਸਾਇੰਸ ਚਲਿਤ ਪ੍ਰੋਜੈਕਟ। | [ਪਾਠ](6-Data-Science-In-Wild/20-Real-World-Examples/README.md) | [Nitya](https://twitter.com/nitya) |

## GitHub Codespaces

ਇਸ ਸੈਂਪਲ ਨੂੰ Codespace ਵਿੱਚ ਖੋਲ੍ਹਣ ਲਈ ਇਹ ਕਦਮ ਅਨੁਸਰਣ ਕਰੋ:
1. Code ਡ੍ਰੌਪ-ਡਾਊਨ ਮੀਨੂ 'ਤੇ ਕਲਿੱਕ ਕਰੋ ਅਤੇ Open with Codespaces ਵਿਕਲਪ ਚੁਣੋ।
2. ਪੈਨ ਦੇ ਹੇਠਾਂ + New codespace ਚੁਣੋ।
ਹੋਰ ਜਾਣਕਾਰੀ ਲਈ, [GitHub ਦਸਤਾਵੇਜ਼](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace) ਵੇਖੋ।

## VSCode ਰਿਮੋਟ - ਕੰਟੇਨਰ
ਇਹ ਕਦਮ ਅਨੁਸਰਣ ਕਰੋ ਤਾਂ ਜੋ ਆਪਣੇ ਸਥਾਨਕ ਮਸ਼ੀਨ ਅਤੇ VSCode ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਇਸ ਰਿਪੋ ਨੂੰ ਕੰਟੇਨਰ ਵਿੱਚ ਖੋਲ੍ਹ ਸਕੋ:

1. ਜੇ ਇਹ ਪਹਿਲੀ ਵਾਰ ਹੈ ਜਦੋਂ ਤੁਸੀਂ ਡਿਵੈਲਪਮੈਂਟ ਕੰਟੇਨਰ ਦੀ ਵਰਤੋਂ ਕਰ ਰਹੇ ਹੋ, ਤਾਂ ਕਿਰਪਾ ਕਰਕੇ ਯਕੀਨੀ ਬਣਾਓ ਕਿ ਤੁਹਾਡਾ ਸਿਸਟਮ ਪ੍ਰੀ-ਰਿਕਵਾਇਰਮੈਂਟਾਂ ਨੂੰ ਪੂਰਾ ਕਰਦਾ ਹੈ (ਜਿਵੇਂ Docker ਇੰਸਟਾਲ ਕੀਤਾ ਹੋਵੇ) [ਸ਼ੁਰੂਆਤੀ ਦਸਤਾਵੇਜ਼](https://code.visualstudio.com/docs/devcontainers/containers#_getting-started) ਵਿੱਚ।

ਇਸ ਰਿਪੋਜ਼ਟਰੀ ਦੀ ਵਰਤੋਂ ਕਰਨ ਲਈ, ਤੁਸੀਂ ਇਸਨੂੰ ਇੱਕ ਅਲੱਗ Docker ਵਾਲਿਊਮ ਵਿੱਚ ਖੋਲ੍ਹ ਸਕਦੇ ਹੋ:

**ਨੋਟ**: ਇਹ ਅੰਦਰੂਨੀ ਤੌਰ 'ਤੇ Remote-Containers: **Clone Repository in Container Volume...** ਕਮਾਂਡ ਦੀ ਵਰਤੋਂ ਕਰੇਗਾ ਤਾਂ ਜੋ ਸੋਰਸ ਕੋਡ ਨੂੰ Docker ਵਾਲਿਊਮ ਵਿੱਚ ਕਲੋਨ ਕੀਤਾ ਜਾ ਸਕੇ ਬਜਾਏ ਸਥਾਨਕ ਫਾਈਲ ਸਿਸਟਮ ਦੇ। [ਵਾਲਿਊਮ](https://docs.docker.com/storage/volumes/) ਕੰਟੇਨਰ ਡਾਟਾ ਨੂੰ ਸਥਾਈ ਬਣਾਉਣ ਲਈ ਪਸੰਦੀਦਾ ਤਰੀਕਾ ਹਨ।

ਜਾਂ ਸਥਾਨਕ ਤੌਰ 'ਤੇ ਕਲੋਨ ਕੀਤੇ ਜਾਂ ਡਾਊਨਲੋਡ ਕੀਤੇ ਗਏ ਰਿਪੋਜ਼ਟਰੀ ਨੂੰ ਖੋਲ੍ਹੋ:

- ਇਸ ਰਿਪੋਜ਼ਟਰੀ ਨੂੰ ਆਪਣੇ ਸਥਾਨਕ ਫਾਈਲ ਸਿਸਟਮ 'ਤੇ ਕਲੋਨ ਕਰੋ।
- F1 ਦਬਾਓ ਅਤੇ **Remote-Containers: Open Folder in Container...** ਕਮਾਂਡ ਚੁਣੋ।
- ਇਸ ਫੋਲਡਰ ਦੀ ਕਲੋਨ ਕੀਤੀ ਕਾਪੀ ਚੁਣੋ, ਕੰਟੇਨਰ ਨੂੰ ਸ਼ੁਰੂ ਕਰਨ ਦੀ ਉਡੀਕ ਕਰੋ, ਅਤੇ ਚੀਜ਼ਾਂ ਨੂੰ ਅਜ਼ਮਾਓ।

## ਆਫਲਾਈਨ ਪਹੁੰਚ

ਤੁਸੀਂ [Docsify](https://docsify.js.org/#/) ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਇਸ ਦਸਤਾਵੇਜ਼ ਨੂੰ ਆਫਲਾਈਨ ਚਲਾ ਸਕਦੇ ਹੋ। ਇਸ ਰਿਪੋ ਨੂੰ ਫੋਰਕ ਕਰੋ, [Docsify ਇੰਸਟਾਲ ਕਰੋ](https://docsify.js.org/#/quickstart) ਆਪਣੇ ਸਥਾਨਕ ਮਸ਼ੀਨ 'ਤੇ, ਫਿਰ ਇਸ ਰਿਪੋ ਦੇ ਰੂਟ ਫੋਲਡਰ ਵਿੱਚ `docsify serve` ਟਾਈਪ ਕਰੋ। ਵੈਬਸਾਈਟ ਤੁਹਾਡੇ localhost `localhost:3000` 'ਤੇ ਪੋਰਟ 3000 'ਤੇ ਸਰਵ ਕੀਤੀ ਜਾਵੇਗੀ।

> ਨੋਟ, Docsify ਦੁਆਰਾ ਨੋਟਬੁੱਕ ਰੈਂਡਰ ਨਹੀਂ ਕੀਤੇ ਜਾਣਗੇ, ਇਸ ਲਈ ਜਦੋਂ ਤੁਹਾਨੂੰ ਨੋਟਬੁੱਕ ਚਲਾਉਣ ਦੀ ਲੋੜ ਹੋਵੇ, ਤਾਂ ਇਸਨੂੰ Python kernel ਚਲਾਉਣ ਵਾਲੇ VS Code ਵਿੱਚ ਅਲੱਗ ਕਰਕੇ ਚਲਾਓ।

## ਹੋਰ ਪਾਠਕ੍ਰਮ

ਸਾਡੀ ਟੀਮ ਹੋਰ ਪਾਠਕ੍ਰਮ ਤਿਆਰ ਕਰਦੀ ਹੈ! ਵੇਖੋ:

- [Edge AI for Beginners](https://aka.ms/edgeai-for-beginners)
- [AI Agents for Beginners](https://aka.ms/ai-agents-beginners)
- [Generative AI for Beginners](https://aka.ms/genai-beginners)
- [Generative AI for Beginners .NET](https://github.com/microsoft/Generative-AI-for-beginners-dotnet)
- [Generative AI with Java
[![GitHub Azure AI Foundry Developer Forum](https://img.shields.io/badge/GitHub-Azure_AI_Foundry_Developer_Forum-blue?style=for-the-badge&logo=github&color=000000&logoColor=fff)](https://aka.ms/foundry/forum)

---

**ਅਸਵੀਕਰਤਾ**:  
ਇਹ ਦਸਤਾਵੇਜ਼ AI ਅਨੁਵਾਦ ਸੇਵਾ [Co-op Translator](https://github.com/Azure/co-op-translator) ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਅਨੁਵਾਦ ਕੀਤਾ ਗਿਆ ਹੈ। ਹਾਲਾਂਕਿ ਅਸੀਂ ਸਹੀਅਤ ਲਈ ਯਤਨਸ਼ੀਲ ਹਾਂ, ਕਿਰਪਾ ਕਰਕੇ ਧਿਆਨ ਦਿਓ ਕਿ ਸਵੈਚਾਲਿਤ ਅਨੁਵਾਦਾਂ ਵਿੱਚ ਗਲਤੀਆਂ ਜਾਂ ਅਸੁੱਤੀਆਂ ਹੋ ਸਕਦੀਆਂ ਹਨ। ਇਸ ਦੀ ਮੂਲ ਭਾਸ਼ਾ ਵਿੱਚ ਮੌਜੂਦ ਅਸਲ ਦਸਤਾਵੇਜ਼ ਨੂੰ ਅਧਿਕਾਰਤ ਸਰੋਤ ਮੰਨਿਆ ਜਾਣਾ ਚਾਹੀਦਾ ਹੈ। ਮਹੱਤਵਪੂਰਨ ਜਾਣਕਾਰੀ ਲਈ, ਪੇਸ਼ੇਵਰ ਮਨੁੱਖੀ ਅਨੁਵਾਦ ਦੀ ਸਿਫਾਰਸ਼ ਕੀਤੀ ਜਾਂਦੀ ਹੈ। ਇਸ ਅਨੁਵਾਦ ਦੀ ਵਰਤੋਂ ਤੋਂ ਪੈਦਾ ਹੋਣ ਵਾਲੇ ਕਿਸੇ ਵੀ ਗਲਤਫਹਿਮੀ ਜਾਂ ਗਲਤ ਵਿਆਖਿਆ ਲਈ ਅਸੀਂ ਜ਼ਿੰਮੇਵਾਰ ਨਹੀਂ ਹਾਂ।