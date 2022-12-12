---
theme: /
layout: image
favicon: ./Kintone/KDP_favicon.png
image: ./Kintone/Red_Background_Right.png
download: true
fonts:
  sans: Raleway
  serif: Raleway
  mono: Raleway
title: Get Started with Kintone Web Database!
selectable: true
---

<div class="mb-4 absolute top-10 left-80" style="text-align:right;user-select:all;">
    <div class="text-7xl text-white text-opacity-100" style="font-weight:600;" >
      Kintone <light-icon icon="settings"/>
    </div>
    <div><br></div>
    <div class="text-7xl text-white text-opacity-100" style="font-weight:600;" >
      Your Project's
    </div>
    <div><br></div>
    <div class="text-7xl text-white text-opacity-100" style="font-weight:600;" >
      Web Database <light-icon icon="database"/>
    </div>
    <div><p></p></div>

  </div>

<div class="absolute bottom-5 right-12">
  <div class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
    <a
      href="https://kintone.dev/"
      target="_blank"
      alt="Kintone Developer Program"
      class="!hover:text-white">
      Kintone Developer Program  <light-icon icon="book" size="24px"/>
    </a>
  </div>
  <div class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
    <a
      href="https://ahandsel.github.io/Talks/Slides_Kintone_Intro_Kids/"
      target="_blank"
      alt="GitHub"
      class="!hover:text-white">
      Slides  <light-icon icon="brand-github" size="24px"/>
    </a>
  </div>
  <span @click="$slidev.nav.next" class="p-1 rounded cursor-pointer hover:bg-white hover:bg-opacity-10 hover:opacity-90 opacity-60 flex justify-center items-center">
    Press Space for the next page  <light-icon icon="arrow-narrow-right" size="24px"/>
  </span>
</div>


---
layout: image-left-bar
image: ./Kintone/Animal_6.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Overview <light-icon icon="color-swatch"/>
  <br><br>
</div>

## ① What is Kintone? 🤔
Web Database

## ② How to Use Kintone? 🧐
Example Projects

## ③ How to Get Started? 💪
When the fun starts


---
layout: my-two-columns
---

<br><br>
<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  What is Kintone? 🤔
</div>
<br>

::left::

<div class="text-4xl text-DEFAULT top-1" style="font-weight:500;user-select:text;line-height: 1.6;" >
  Kintone is a low-code platform that allows you to build <strong>Web Databases</strong> quickly & easily! <light-icon icon="tools"/>
</div>

::right::

![Kintone exchanging data from a smartphone](/Kintone_Intro/Fast_Database.png)

<!--
layout: my-two-columns

<br><br>

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Your Project's Web Database <light-icon icon="sitemap"/>
</div>

::left::

<br>

## Use Kintone to
## **store** incoming data or
## **manage** outgoing data! <light-icon icon="tools"/>

![Kintone exchanging data from a smartphone](/Kintone_Intro/Kintone_DataExchange.png)

::right::

<br>

## Kintone allows you to
## build **Web Databases**
## quickly & easily! <light-icon icon="tool"/>

<br>

![Kintone exchanging data from a smartphone](/Kintone_Intro/Fast_Database.png)
-->

---
layout: my-two-columns
---

<br><br>

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Your Project's Web Database <light-icon icon="sitemap"/>
</div>

::left::

<div class="text-4xl text-DEFAULT top-1" style="font-weight:500;user-select:text;line-height: 1.6;" >
  Use Kintone to <strong>store</strong> incoming data or <strong>manage</strong>
 outgoing data! <light-icon icon="tools"/>
</div>

::right::

![Kintone exchanging data from a smartphone](/Kintone_Intro/Kintone_DataExchange.png)


---
layout: image-left
image: ./Kintone_Intro/Traditional_Database.png
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Traditional Databases <light-icon icon="mood-sad"/>
  <br><br>
</div>


#### Needs a **high-level understanding** of databases

<br>

#### **Servers** need to be **constantly running** & maintained to be accessed


---
layout: image-right
image: ./Kintone_Intro/Build_App_Demo.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Kintone Databases <light-icon icon="mood-happy"/>
  <br><br>
</div>

## Databases are created with intuitive **drag-&-drop** GUI

<br>

## **No servers need** to be set up by the user


---
layout: image
image: ./Kintone/Red_Background_Left.png
---

<div class="mb-4 absolute top-15 right-65" style="text-align:left;user-select:all;">
    <div class="text-6xl text-white text-opacity-100" style="font-weight:600;" >
      How to Use Kintone? 🧐
    </div>
    <div><br><br><br></div>
    <div class="text-4xl text-white text-opacity-100" style="font-weight:600;" >
      Access Kintone Database Data via
    </div>
    <div><br><br></div>
    <div class="text-4xl text-white text-opacity-100" style="font-weight:600;" >
      ‣ Web Browser <light-icon icon="browser"/>
      <br><br>
      ‣ REST API <light-icon icon="exchange"/>
    </div>
    <div><p></p></div>
</div>


---
layout: my-two-columns
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via the Browser <light-icon icon="browser"/>
</div>

::left::

# Use the GUI to:

<br>

* ## Create & Edit Databases <light-icon icon="database"/>

<br>

* ## View/ Add/ Edit Records <light-icon icon="folders"/>

<br>

* ## Add JS Customizations <light-icon icon="code"/>

::right::

![Build a Kintone App from YOUR_SUBDOMAIN.kintone.com](/Kintone_Intro/Kintone_From_Browser.png)


---
layout: image-center
image: ./Kintone_Intro/Kintone_REST_API_Request.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <light-icon icon="exchange"/>
  <br><br>
</div>


---
layout: image-center
image: ./Kintone_Intro/Kintone_REST_API_Response.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <light-icon icon="exchange"/>
  <br><br>
</div>


---
layout: image-center
image: ./Kintone_Intro/Kintone_REST_API_Flow.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Access Kintone DBs via REST API <light-icon icon="exchange"/>
  <br><br>
</div>

<!--
Let’s say you’ve made some databases in Kintone and added some data in.
You can make REST API calls from your App pointing to your Kintone environment, the Database ID you want to access and an API token for authentication to get your results.
You can call REST APIs from most languages, wether it be node.js, python, php, Ruby etc.
-->

---
layout: image-right
image: ./Kintone_Intro/Example_Samurai.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  IoT Samurai Swords <light-icon icon="slice"/>
</div>

<br>

### Created by [@RyBB](https://github.com/RyBB) - [Article](https://dev.to/will_yama/kintone-at-maker-faire-tokyo-2020-215k)

Users are challenged to slice their enemies as quickly as possible with a samurai sword!

* Sensor records the sword action speed
* Kintone hosts the game, scoreboard, & IoT data
* Doll's magnetic head falls off when the user wins

<!--
layout: image-center
image: ./Kintone_Intro/Example_flowerpot.png

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Hibotan / Flowerpot Project <light-icon icon="trees "/>
</div>

<br>

<div class="text-2xl text-dark top-1" style="font-weight:500;user-select:all;" >
  A moving flowerpot that uses <strong>Kintone as the backend</strong> to store sensor data.
</div>
<br>

* Sensors are attached to the Mbed Micro-controller.
* Sensor values are periodically sent to Kintone via Node.js.
* Node.js checks Kintone’s sensor values over time and controls motors of the flowerpot.
* The flowerpot moves to are sunny location. -->

<!--
* Goal: Make attendees feel like super fast anime samurais
* Sword: magnet sensors to detect in & out motion speed
* doll with electric magnet to have its head fall off
* 2 M5Stick micro-controllers were used for sword & doll
* The score ranking displayed information stored in the Kintone App, where scores of participants were automatically recorded via REST API after they finished playing the game.
-->

---
layout: image-right
image: ./Kintone_Intro/Example_SpaceInvaders.gif
equal: true
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Space Invaders Game <light-icon icon="alien"/>
</div>

<br>

### Created by [@will_yama](https://twitter.com/will_yama) & [@ahandsel](https://github.com/ahandsel/) - [Article](https://dev.to/will_yama/having-fun-with-phaser-io-games-web-databases-4f08)

Run a [Space Invaders game](https://phaser.io/examples/v2/games/invaders) on a Kintone App!

Game specifications (number of aliens, aliens' health, etc.) are specified as Kintone records.

High scores can also be stored in Kintone.


---
layout: my-two-columns
---

::left::

<br>

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Get Your Free Kintone <light-icon icon="bolt"/>
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
layout: image-left-bar
image: ./Kintone/Animal_3.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:all;" >
  Where to get help? <light-icon icon="help"/>
</div>

<br>

Here are some resources to help you use Kintone as your project's database!

| <light-icon icon="home"/> | [kintone.dev](https://kintone.dev/) | Read API Docs & Tutorials
| --- | --- | --- |
| <light-icon icon="lifebuoy"/> | [forum.kintone.dev](https://forum.kintone.dev/) | Post Questions |
| <light-icon icon="brand-youtube"/> | [@KintoneDeveloperProgram](https://www.youtube.com/@KintoneDeveloperProgram) | Watch Tutorials |


---
layout: image-left-bar
image: ./Kintone/Animal_10.png
---

<div class="text-5xl text-primary dark:text-primary top-1" style="font-weight:500;user-select:text;" >
  Thank You Gift! <light-icon icon="rocket"/>
</div>

<br>

## As a **Thank You** for using Kintone in your project, we are giving away some Kintone Swag!

<br><br>

<img src="/Kintone/KDP_Swag.png" alt="Bottles, backpacks, PopSockets, & more!" style="width: 60%;">


---
layout: image
image: ./Kintone/Slide20.png
---
