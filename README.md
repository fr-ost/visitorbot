<div align="center">

<img width="100%" alt="visitorbot — auto visitor for Blogger and WordPress" src="https://capsule-render.vercel.app/api?type=waving&color=0:6C2BD9,50:FF2E93,100:FFB703&height=220&section=header&text=visitorbot&fontSize=58&fontColor=ffffff&fontAlignY=32&animation=fadeIn&desc=Auto%20visitor%20for%20Blogger%20and%20WordPress&descAlignY=58&descAlign=50&descSize=18"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3600&pause=700&color=FFB703&center=true&vCenter=true&width=820&height=48&lines=Auto+visitor+for+Blogger+and+WordPress;PHP+%2B+cURL+with+a+random+user+agent;Android+app%3A+Frost+BOT;Created+by+Al+Sayeed" />
  <source media="(prefers-color-scheme: light)" srcset="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3600&pause=700&color=6C2BD9&center=true&vCenter=true&width=820&height=48&lines=Auto+visitor+for+Blogger+and+WordPress;PHP+%2B+cURL+with+a+random+user+agent;Android+app%3A+Frost+BOT;Created+by+Al+Sayeed" />
  <img width="820" alt="Auto visitor for Blogger and WordPress. PHP and cURL with a random user agent. Android app: Frost BOT. Created by Al Sayeed." src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3600&pause=700&color=6C2BD9&center=true&vCenter=true&width=820&height=48&lines=Auto+visitor+for+Blogger+and+WordPress;PHP+%2B+cURL+with+a+random+user+agent;Android+app%3A+Frost+BOT;Created+by+Al+Sayeed" />
</picture>

*A PHP page that requests one URL as many times as you ask, and the Android wrapper that opens the hosted copy.*

<br/>

<a href="https://github.com/fr-ost/visitorbot/releases/tag/1.0"><img alt="GitHub release 1.0, Alpha Stage" src="https://img.shields.io/github/v/release/fr-ost/visitorbot?style=for-the-badge&color=FF2E93&label=release"/></a>
<img alt="Written in PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img alt="Uses the cURL extension" src="https://img.shields.io/badge/cURL-073551?style=for-the-badge&logo=curl&logoColor=white"/>
<img alt="HTML form" src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img alt="Android project shipped as android_source.tar.gz" src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=1A1024"/>
<img alt="App name Frost BOT" src="https://img.shields.io/badge/Frost_BOT-6C2BD9?style=for-the-badge&logo=android&logoColor=white"/>

<br/>
<br/>

<a href="#overview">Overview</a> ·
<a href="#key-features">Features</a> ·
<a href="#tech-stack">Stack</a> ·
<a href="#getting-started">Getting started</a> ·
<a href="#configuration">Configuration</a> ·
<a href="#usage">Usage</a> ·
<a href="#project-structure">Structure</a> ·
<a href="#android-app">Android</a> ·
<a href="#contributing">Contributing</a> ·
<a href="#credits">Credits</a>

</div>

## ✨ Overview

**visitorbot** is a small PHP auto visitor. The repository describes it as an auto visitor for Blogger and WordPress. The page title in `script/index.php` is **Auto Visitor For All**, and the form's sample address is `https://YourBloggerLink.Com`.

You enter a URL and a count. The page sends that many HTTP requests to the URL. Each request carries a newly generated browser user agent and a referer drawn from a fixed list. The page then prints one line per pass.

The script was created by **Al Sayeed**. The Android app, **Frost BOT**, was developed by **[Shahriar Ahmed](https://github.com/fr-ost)**.

The form sits under this warning:

> অতিরিক্ত কোন কিছুই ভাল না।
> লোভে পাপ,পাপে মৃত্যু।

Nothing in excess is good. Greed is sin, and sin is death.

The loop sends real HTTP requests to whatever address is in the form, including the sample value if you leave it there. The original page points questions to [fb.me/ig.Frostt](http://fb.me/ig.Frostt). The README contact is [fb.com/ig.frostt](https://fb.com/ig.frostt).

## 🚀 Key features

| | |
| --- | --- |
| **Form** | Two fields, `url` and `max`, submitted with GET. |
| **Repeat** | One cURL request per count, from `1` through `max`. |
| **User agent** | A random Firefox, Safari, Internet Explorer, Opera, or Chrome string. |
| **Referer** | Drawn from a fixed list of Google country hosts, Facebook, Twitter, Yahoo, and `beinyu.com`. |
| **Live output** | The class flushes the buffer so lines can appear while the loop is still going. |
| **Android shell** | `android_source.tar.gz` is a [GoNative](https://gonative.io/) WebView app named Frost BOT. |

The visit loop is the three files in `script/`. Accounts, a database, and Composer packages sit outside this repository.

## 🧰 Tech stack

<div align="center">

<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img alt="cURL" src="https://img.shields.io/badge/cURL-073551?style=for-the-badge&logo=curl&logoColor=white"/>
<img alt="HTML" src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img alt="CSS" src="https://img.shields.io/badge/CSS-FFB703?style=for-the-badge&logo=css3&logoColor=1A1024"/>
<img alt="Android" src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=1A1024"/>
<img alt="GoNative WebView" src="https://img.shields.io/badge/GoNative_WebView-6C2BD9?style=for-the-badge"/>

</div>

The page style is inline CSS. It loads [Play](http://fonts.googleapis.com/css?family=Play:400,700) and [Kelly Slab](http://fonts.googleapis.com/css?family=Kelly+Slab) from Google Fonts, and it also names Consolas and Lucida Console. The favicon href is `http://res7ock.org/assets/img/favicon.png`. The background image `bg.jpg` is referenced from the stylesheet and is not in this repository.

`script/randomua.class.php` is the random user-agent class, version 1.0, dated 28 September 2012, by Randolph Burgos (exeQutor).

`.github/workflows/php.yml` is GitHub's stock **PHP Composer** workflow. On pushes and pull requests to `main` it checks out the tree, runs `composer validate`, caches `vendor` from `composer.lock`, and runs `composer install` when the cache misses. The test step in that file is commented out. The workflow is looking for `composer.json` and `composer.lock`, and neither file is in this repository.

## 🏁 Getting started

| Requirement | Why it is here |
| --- | --- |
| PHP | `script/index.php` is a PHP page. |
| cURL extension | `autovisitor.class.php` calls `curl_init`. |
| A PHP server | The form is an ordinary web page. |

Clone the repo and start PHP's built-in server with `script/` as the document root. `index.php` loads `autovisitor.class.php`, and that file loads `randomua.class.php`, both by bare filename. PHP resolves those names from the directory of the file that requires them, and from the process working directory. Starting the server inside `script/` covers both.

```bash
git clone https://github.com/fr-ost/visitorbot.git
cd visitorbot/script
php -S localhost:8000
```

Open [http://localhost:8000/](http://localhost:8000/). The same `script/` folder can sit on any PHP host. Keep the three PHP files side by side so the bare `require` calls resolve.

When the loop ends, `index.php` includes `auth/startup.php`, `data/data-functions.php`, and `assets/comp/header.php`, then calls `all_settings()`. Those three files are not in this repository. The requests have already been sent by then. On a stock checkout the page stops afterwards with a PHP error on `all_settings()`.

## ⚙️ Configuration

This project reads no environment variables and ships no `.env` file.

The form is the configuration. Both fields travel as query parameters on `script/index.php`.

| Field | Form default | What the code does with it |
| --- | --- | --- |
| `url` | `https://YourBloggerLink.Com` | Passed straight to `autovisitor` and requested once per pass. |
| `max` | `1000` | The loop is `for ($i = 1; $i < $max + 1; $i++)`. |

The count input is written as `type="max"`. Browsers treat that unknown type as text. A request with any query string at all gets past `if (!$_GET) die();`. Opening the page with an empty query string stops before the loop.

Android settings live in `android/app/src/main/assets/appConfig.json` inside `android_source.tar.gz`.

| Setting | Value stored in the archive |
| --- | --- |
| `general.initialUrl` | `https://frosttrafficbot.000webhostapp.com/` |
| `general.appName` | Frost BOT |
| `general.androidPackageName` | `com.frost.bot` |
| `general.androidVersionName` | `1.0.1` |
| Sidebar **Bot** | `https://frosttrafficbot.000webhostapp.com` |
| Sidebar **Contact** | `https://www.facebook.com/ig.frostt` |

That host is also the homepage field on this GitHub repository. A deployment of it is not part of the tree. A second sidebar in the same file is marked inactive. Its entries are labeled Sample Home and Sample About, and they point at `https://frosttrafficbot.000webhostapp.com//home` and `https://frosttrafficbot.000webhostapp.com//about`.

## ▶️ Usage

Submit the form, or open the page with both query fields filled in. Three passes look like this in the browser:

```
http://localhost:8000/?url=https://YourBloggerLink.Com&max=3
```

```
1. SUCCESSFUL - [referer drawn after that request]
2. SUCCESSFUL - [referer drawn after that request]
3. SUCCESSFUL - [referer drawn after that request]
```

The text comes from `echo $i.". SUCCESSFUL - [".$class->jalankan()."]<br>";`. The value in brackets is a **new** call to `acakReferer()` after `curl()` returns, so it can differ from the `Referer` header on that request. **SUCCESSFUL** is printed for every pass: the cURL result is discarded, and the HTTP status is never read.

Each request follows redirects (`CURLOPT_FOLLOWLOCATION` is true). SSL peer and host checks are off (`CURLOPT_SSL_VERIFYPEER` and `CURLOPT_SSL_VERIFYHOST` are `0`). The class sets `error_reporting(0)`, so cURL failures stay quiet. The code has no delay between requests and no proxy setting. A second `xflush()` sits after the `return` in `jalankan()`, so that call never runs.

<details>
<summary><strong>Referers the class can attach</strong></summary>

<br/>

`acakReferer()` draws one entry with `array_rand`. Four addresses are pushed twice, so they come up more often: `http://facebook.com`, `http://google.com.sg`, `http://twitter.com`, and `http://google.by`.

| | | |
| --- | --- | --- |
| `http://facebook.com` | `http://twitter.com` | `http://google.com.sg` |
| `http://google.co.id` | `http://google.com.my` | `http://google.jp` |
| `http://google.us` | `http://google.bd` | `http://google.com.bd` |
| `http://google.ac` | `http://google.ad` | `http://google.ae` |
| `http://google.af` | `http://google.ag` | `http://google.ru` |
| `http://google.by` | `http://google.ca` | `http://google.cn` |
| `http://google.cl` | `http://google.cm` | `http://google.cv` |
| `http://google.gg` | `http://google.tk` | `http://google.cf` |
| `http://google.gq` | `http://google.ge` | `http://google.gr` |
| `http://google.com.tw` | `https://search.yahoo.com` | `http://www.beinyu.com` |

</details>

<details>
<summary><strong>How the user agent is built</strong></summary>

<br/>

`Random_UA::generate()` rolls 1 through 5:

| Roll | String it builds |
| --- | --- |
| 1 | `Mozilla/5.0` and a Firefox token (the pools cover roughly Firefox 3.6 through 7) |
| 2 | `Mozilla/5.0` and a Safari token |
| 3 | `Mozilla/4.0` or `Mozilla/5.0` and an Internet Explorer token |
| 4 | `Opera/8` or `Opera/9` and a Presto token |
| 5 | `Mozilla/5.0` and a Chrome 13–15 token |

Platforms in the pools are Windows NT, Linux (`i686` or `x86_64`), Mac OS X (Intel or PPC), and, on the Safari path, an iPod. Language tags in the pools are `en-US` and `sl-SI`.

The file header credits Randolph Burgos (exeQutor), [burgosoft.com/php-scripts/random-uagent](http://burgosoft.com/php-scripts/random-uagent/), and names [github.com/lukapusic/random-uagent](https://github.com/lukapusic/random-uagent) as the file source.

`curl()` calls `generate()` twice: once for the `User-Agent` request header, and once for `CURLOPT_USERAGENT`. The two calls return different strings.

</details>

## 📁 Project structure

```
visitorbot/
├── script/
│   ├── index.php                 # form, request loop, trailing includes
│   ├── autovisitor.class.php     # one cURL request and the referer list
│   └── randomua.class.php        # random browser user agent
├── apk-releases/
│   └── info.md                   # "SDK 26 or Higher."
├── android_source.tar.gz         # GoNative Android project (Frost BOT)
├── .github/workflows/php.yml     # stock PHP Composer workflow
├── CONTRIBUTING.md
└── README.md
```

The [1.0 release](https://github.com/fr-ost/visitorbot/releases/tag/1.0) is named **Alpha Stage 1.0**. The release notes say "Auto Visitor for Blogger", mark it alpha, and name Shahriar Ahmed as the developer. No files are attached to that release. `apk-releases/` holds the SDK line and no APK.

## 📱 Android app

Unpack `android_source.tar.gz` and import the project into Android Studio. The README inside the archive says to edit `appConfig.json` to taste. The wrapper itself is the native Android code from [gonative.io](https://gonative.io/), where that project's licensing notes live.

| | |
| --- | --- |
| App name | Frost BOT (`strings.xml` and `appConfig.json`) |
| Package | `com.frost.bot` |
| Version name | `1.0.1` in `appConfig.json` |
| Version code | `2` in `app/build.gradle` |
| Note in `apk-releases/info.md` | SDK 26 or higher |
| Gradle SDK | `minSdkVersion` 16, `compileSdkVersion` 29, `targetSdkVersion` 29 |
| First screen | `https://frosttrafficbot.000webhostapp.com/` |
| Drawer | **Bot** on that host, **Contact** at `https://www.facebook.com/ig.frostt` |

Release and upload signing in `app/build.gradle` point at `release.keystore` and `upload.keystore` one directory above the Android project. Those keystores are not in the archive.

## 🤝 Contributing

`CONTRIBUTING.md` is one line: if you want to improve this script, you are welcome to, and the script is fully open sourced.

The tree has no `LICENSE` file, so that sentence is the only grant written down. The Composer workflow under `.github/workflows/` is the only automation checked in, and it is waiting on Composer files this repo does not have.

## 💜 Credits

| | |
| --- | --- |
| Script | **Al Sayeed** |
| Android app | **[Shahriar Ahmed](https://github.com/fr-ost)**, Co-Founder & COO of **[Unique Labs](https://www.uniquelabs.org)** |
| Contact | [fb.com/ig.frostt](https://fb.com/ig.frostt) |
| User-agent class | Randolph Burgos (exeQutor), [random-uagent](https://github.com/lukapusic/random-uagent) |
| Android wrapper | [GoNative](https://gonative.io/) |
| Lab | [uniquelabs.org](https://www.uniquelabs.org) · [shahriarahmed.net](https://shahriarahmed.net) |

<div align="center">

<a href="https://github.com/fr-ost"><img alt="Shahriar Ahmed on GitHub" src="https://img.shields.io/badge/Shahriar_Ahmed-6C2BD9?style=for-the-badge&logo=github&logoColor=white"/></a>
<a href="https://www.uniquelabs.org"><img alt="Unique Labs" src="https://img.shields.io/badge/Unique_Labs-00A896?style=for-the-badge"/></a>
<a href="https://fb.com/ig.frostt"><img alt="Facebook contact ig.frostt" src="https://img.shields.io/badge/ig.frostt-FF2E93?style=for-the-badge&logo=facebook&logoColor=white"/></a>
<a href="https://shahriarahmed.net"><img alt="shahriarahmed.net" src="https://img.shields.io/badge/shahriarahmed.net-FFB703?style=for-the-badge&logoColor=1A1024"/></a>

<br/>

<img width="100%" alt="Violet, pink, and amber footer wave" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFB703,50:FF2E93,100:6C2BD9&height=120&section=footer"/>

</div>
