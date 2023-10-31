---
theme: /
colorSchema: light
layout: image
favicon: ./Kintone/KDP_favicon.png
image: ./Kintone/Red_Background_Right.png
download: true
fonts:
  sans: Raleway
  serif: Raleway
  mono: Raleway
title: React & REST API Workshop by Kintone!
selectable: true
---

<div class="mb-4 absolute top-20 left-70" style="text-align:right;user-select:all;">
    <div class="text-7xl text-white text-opacity-100" style="font-weight:600;" >
      React x REST API <mdi-cog/>
    </div>
    <div><br></div>
    <div class="text-6xl text-white text-opacity-100" style="font-weight:600;" >
      JavaScript Workshop <mdi-database/>
    </div>
    <div><p><br></p></div>
    <!-- <div class="text-5xl text-white text-opacity-100" style="font-weight:600;" >
      <i>By Kintone</i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
    </div> -->
    <div><p></p></div>
  </div>

<div class="text-3xl absolute bottom-5 right-4" style="text-align:left">
  <div class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-75" style="text-align:left">
    <a
      href="https://kintone.dev/"
      target="_blank"
      alt="Kintone Developer Program"
      class="!hover:text-white">
      <mdi-book/>
      Kintone Developer Program  
    </a>
  </div>
  <br>
  <div class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-75" style="text-align:left">
    <a
      href="https://github.com/ahandsel/Talks"
      target="_blank"
      alt="GitHub"
      class="!hover:text-white">
      <mdi-cloud-download/>
      bit.ly/KDP_React_Slides  
    </a>
  </div>
  <br>
  <span @click="$slidev.nav.next" class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-75">
    <mdi-arrow-right-circle/> Hit Space for the next page
  </span>
</div>


---
layout: simple
---

<div class="text-4xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  Hello <mdi-human-greeting-variant/>
</div>

<br>

We are from the Kintone Developer Relations Team!

<br>

<div>
  <table>
    <thead>
      <tr>
        <th>Sean</th>
        <th>Jesslyn</th>
        <th>Genji</th>
        <th>Naberina</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Presenter</td>
        <td>Writer</td>
        <td>Organizer</td>
        <td>Supporter</td>
      </tr>
      <tr>
        <td><img src="/KDP_React_Workshop/KDP_Sean.png" alt="Photo of Sean" width="235"></td>
        <td><img src="/KDP_React_Workshop/KDP_Jesslyn.png" alt="Photo of Jesslyn" width="235"></td>
        <td><img src="/KDP_React_Workshop/KDP_Genji.png" alt="Photo of Genji" width="235"></td>
        <td><img src="/KDP_React_Workshop/KDP_Naberina.png" alt="Photo of Naberina" width="235"></td>
      </tr>
    </tbody>
  </table>
</div>

<style> .slidev-layout th { font-weight: bold; text-align: center } .slidev-layout td { text-align: center } .slidev-layout table { text-align: center;} .slidev-layout img { display: block; margin: auto; } </style>


---
layout: my-two-columns
---

<div class="text-4xl text-primary dark:text-primary top-1" style="font-weight:500;text-align:left" >

Prep <mdi-lightning-bolt/>

</div>

<br>

::left::

## Wi-Fi <material-symbols-wifi/>

<br>

#### Network: `cc_guest_5ghz`

#### &nbsp;

#### Password: `alwaysbekind`

#### &nbsp;

<img src="/KDP_React_Workshop/QRCode_CodeChrysalisWiFi.png" alt="QR Code for Code Chrysalis WiFi Login" width="225">

::right::

## Node.JS <material-symbols-code/>

**Node.js v18.16.1** or higher is required!  
([The current LTS version](https://nodejs.org/) is recommended)

Refer to our Node.JS Install Guide for details:  
→ [bit.ly/nodejs-setup-guide](https://bit.ly/nodejs-setup-guide)

<div text-align="center">
  <img src="/KDP_React_Workshop/QRCode_NodeInstallGuide.png" alt="QR Code for Node.js & npm Installation Guide" width="225">
</div>


---
layout: my-two-columns
---

<div class="text-4xl text-primary dark:text-primary top-1" style="font-weight:500;text-align:left" >

Get Started <mdi-fire/>

</div>

<br>

::left::

## Clone the GitHub Repo <mdi-github/>
### Boilerplate Code for the Workshop
###  
###  

<br>

## [bit.ly/react-x-rest](https://bit.ly/react-x-rest)

<img src="/KDP_React_Workshop/QRCode_GitHub.png" alt="QR Code for bit.ly/react-x-rest" width="225">

::right::

## Web Database - Kintone <material-symbols-database/>
### Low-Code / No-Code Platform
###  
###  

<br>

## [kintone.dev/new](https://kintone.dev/new)

<div text-align="center">
  <img src="/KDP_React_Workshop/QRCode_Kintone.png" alt="QR Code for kintone.dev/new" width="225">
</div>


---
layout: image-center
---

<Youtube id="un_vMKv_6hM" width="890" height="450"/>


---
layout: my-two-columns
---

::left::

<br>

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Get Your Free Kintone <mdi-lightning-bolt/>
</div>
<br>

## Go to [Kintone.dev/new](https://Kintone.dev/new)!

<br>

Fill out the Developer License Registration form for your free Kintone Subdomain!

* ✅ Use Chrome or Firefox ( _NOT Safari_ )
* ⚡ Accept Cookies First
* 🚧 Only use lowercase, numbers, and hyphens (-) for subdomain names
* Ex: weekend-hacker4life

::right::

![Kintone exchanging data from a smartphone](/Kintone/Kintone_New.png)

---
layout: image-right
image: ./Kintone_Intro/Example_Samurai.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  IoT Samurai Swords <mdi-knife/>
</div>

<br>

### Created by [@RyBB](https://github.com/RyBB) - [Article](https://dev.to/will_yama/kintone-at-maker-faire-tokyo-2020-215k)

Users are challenged to slice their enemies as quickly as possible with a samurai sword!

Sensor records the sword action speed

Kintone hosts the game, scoreboard, & IoT data

Doll's magnetic head falls off when the user wins


---
layout: image-right
image: ./Kintone_Intro/Example_SpaceInvaders.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Space Invaders Game <material-symbols-robot-2/>
</div>

<br>

### Created by [@will_yama](https://twitter.com/will_yama) & [@ahandsel](https://github.com/ahandsel/) - [Article](https://dev.to/will_yama/having-fun-with-phaser-io-games-web-databases-4f08)

Run a [Space Invaders game](https://phaser.io/examples/v2/games/invaders) on a Kintone App!

Game specifications (number of aliens, aliens' health, etc.) are specified as Kintone records.

High scores can also be stored in Kintone.


---
layout: image-right
image: ./KDP_React_Workshop/Kintone_OpenAI_ImageGenerator_Demo.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Art Generator <material-symbols-format-paint/>
</div>

<br>

### Created by [@sean-kintone](https://github.com/sean-kintone) - [GitHub](https://github.com/kintone-workshops/ai-kintone-gallery)

Like cats with too many fingers or dogs with depressed human eyes?

If so, watch our tutorial as we go over how to create a gallery with a built-in AI Art generator using OpenAI APIs & Kintone!

The text prompt inputting and image storage is all done in Kintone!

#### <mdi-youtube/> [youtu.be/fnjteLW8F8I](https://youtu.be/fnjteLW8F8I)


---
layout: image-left-bar
image: ./Kintone/Animal_3.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Where to get help? <mdi-bulb/>
</div>

<br>

Here are some resources to help you use Kintone as your project's database!

| <material-symbols-book/>          | [kintone.dev](https://kintone.dev/)                                          | Read API Docs & Tutorials |
| --------------------------------- | ---------------------------------------------------------------------------- | ------------------------- |
| <material-symbols-help/>          | [forum.kintone.dev](https://forum.kintone.dev/)                              | Post Questions            |
| <mdi-youtube/> | [@KintoneDeveloperProgram](https://www.youtube.com/@KintoneDeveloperProgram) | Watch Tutorials           |


---
layout: image-left-bar
image: ./Kintone/Animal_10.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Thank You Gift! <material-symbols-rocket/>
</div>

<br>

## As a **Thank You** for using Kintone in your project, we are giving away some Kintone Swag!

<br><br>

<img src="/Kintone/KDP_Swag.png" alt="Bottles, backpacks, PopSockets, & more!" style="width: 60%;">


---
layout: intro
image: ./background/tokyo_blue-ryo-yoshitake-rD28m9BmXVs-unsplash.png
---

<div class="mb-4 absolute top-20 left-12" style="right:0; text-align: right;">
  <span class="text-6xl text-primary-lighter text-opacity-80" style="font-weight:500; font-weight: bold;" >
    Join our DevRel Team <material-symbols-supervised-user-circle/> &nbsp;
  </span>
  <div><br><br></div>
  <div style="font-weight:500; font-weight: bold;">
    <p>
      Check out the full list of open positions at Cybozu at: &nbsp; <a href="https://cybozu.co.jp/recruit/entry/">cybozu.co.jp/recruit/entry/</a>
      &nbsp; &nbsp; &nbsp; &nbsp;
      <br><br>
      Our Global Kintone Developer Relations Team has a open role:
      &nbsp; &nbsp; &nbsp; &nbsp;
      <br>
      <br>
      <mdi-fountain-pen/> API Technical Writer
      &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
    </p>
  </div>
</div>


---
layout: image-left-bar
image: ./KDP_Hiring_Jun_2022/technical_content_creator.png
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  API Technical Writer <mdi-fountain-pen/>
</div>

### Mission?
Create vital content for global engineers to use & build on Kintone!
### How?

* Produce [technical tutorials](https://kintone.dev/en/tutorials/)
* Write [API documentation](https://kintone.dev/en/docs/)
* Execute [marketing campaigns](https://kintone.dev/en/landing-page/hackathon/)
* Optimize our [kintone.dev](https://kintone.dev/) site
* Manage our [developer forum](https://forum.kintone.dev/)
* Connect with engineers around the world!


---
layout: image-right
image: ./KDP_React_Workshop/Job_Bar.png
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
  Requirements for the Roles <mdi-pencil/>
</div>

<br>

### Requirements

* Fluent in English
* Business level Japanese {N2-ish}
* 1+ year of coding experience at a company <br> *or* graduated from a Coding Bootcamp

<br>

### Nice To Haves

* Written & published technical tutorials
* Created instructional videos
* Experience in data analysis for website analytics

<br>

#### <mdi-cursor-default-click/> [cybozu.co.jp/recruit/entry/career/api-technical-writer.html](https://cybozu.co.jp/recruit/entry/career/api-technical-writer.html)


---
layout: my-two-columns
---

<div class="text-3xl text-primary dark:text-primary top-1" style="font-weight:500;" >
    <a href="https://cybozu.co.jp/recruit/job/system-consulting.html">
      Other Engineering Positions <mdi-sitemap/>
    </a>
  </div>

###   
###   
<br>


::left::

## Technical Engineer <mdi-tools/>
### Technical Engineering Division

This division provides technical support to our partner firms with everything from servers, networks, databases, backups, and integrations.

Technical Engineering is a great role for those who want to work with backend technologies, stress test our products & client setup, and work as a bridge between the Tokyo & US offices.

::right::

## Developer Tools Engineer <material-symbols-tools-power-drill/>
### System Development Division

This division creates tools that external developers use to build integrations and customizations on Cybozu's products.
They oversee our products' various SDKs such as [js-sdk](https://github.com/kintone/js-sdk), & [kintone-ui-component](https://github.com/kintone-labs/kintone-ui-component).

Developer Tools Engineering is a great role for those who want to build everything from VS Code extensions to CLI tools.


---
layout: my-two-columns
---

<div class="text-4xl text-primary dark:text-primary top-1" style="font-weight:500;" >

Want to learn more? <mdi-lightning-bolt/>

</div>

<br>

::left::

Check out this Japanese article to learn more about Cybozu's System Consulting Department and the aforementioned engineering positions:

<div class="text-primary dark:text-primary pb-2 pt-4" style="line-height: 2;">
  <a href="https://www.wantedly.com/companies/cybozu/post_articles/241621">
    サイボウズのシステムコンサルティング本部とは？
  </a>
</div>

::right::

  Coding bootcamp alumni are recommended to apply to Cybozu's 新卒採用 (*しんそつさいよう*) -- new graduate hiring track.

  <div class="text-primary dark:text-primary pb-2 pt-4" style="line-height: 1.6;">
  Learn more about the new graduate hiring track at:
  <br>
    <a href="https://cybozu.co.jp/recruit/entry/newgrad/">
      cybozu.co.jp/company/job/recruitment/newgrad/
    </a>
  </div>


---
layout: image
image: ./Kintone/Slide20.png
---

<!-- Thank You Slide -->

<!-- 
layout: image-right
image: ./KDP_React_Workshop/Contest_Bar.png

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Kintone Customization Contest 2023 <material-symbols-trophy/>
</div>

<br>

Deadline: **Thu, August 31, 23:59**

Prizes: **$100 gift cards** to **15 winners**

How to Enter:

1. <mdi-bulb/> Build a cool Kintone customization (Web app, plug-in, etc.)
2. <mdi-pencil/> Write up how you built it & [post your article on DEV](https://dev.to/new)
3. <material-symbols-cloud-upload/> Submit on the [Contest Submission](https://forum.kintone.dev/t/799) topic.

Criteria: **Creativity**, **Look & Feel**, **Article Quality**, & **Kintone Usage**

## <mdi-cursor-default-click/> [bit.ly/kintonecontest23](https://bit.ly/kintonecontest23) <mdi-cursor-default-click/>
-->
