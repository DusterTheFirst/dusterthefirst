# Zachary Kohnen

<details open>
  <summary><b>Contact</b></summary>

[me@dusterthefirst.com](mailto:me@dusterthefirst.com) \
[https://dusterthefirst.com](https://dusterthefirst.com) \
[https://github.com/dusterthefirst](https://github.com/dusterthefirst)

</details>

I am a High School Senior who loves to program and work on hobby electronics in
my free time. I have recently gotten into active stabilization of model rocketry
and keep a (somewhat up to date) devlog on my website [rocketry.dusterthefirst.com][rocketry].
I am an absolute fanatic for [rust], [react], [typescript], and the new
[Raspberry PI Pico][pico].

## Current Projects

<sup>Last updated June 30, 2021</sup>

<details>
 <summary><b>Expand/Collapse</b></summary>

- [annoy] was a small hobby project to create a little annoying toy that my S/O
  could control remotely and get my attention when I get sucked into a project.
  It uses an ESP8266 and a whole load of reverse proxying to be accessible on
  the internet. When put together, it is a little annoying box of fun.

- [sd] is an online D&D like magic card creator, designed for custom campaigns.
  The tool was never really used in a campaign, but has been very useful for
  the DM it was created for. It was a great project for working on a full
  client side app in react, and probably was the reason I chose to use React
  Native for the WHS Helper App.

- [teensyduino-rs] is a somewhat ongoing project to create safe rust bindings to
  the teensyduino library which goes along with [my fork][arduinoteensy-better-ffi]
  of the [platformio teensyduino framework][arduinoteensy] which exposes many more
  of the functions as a C ABI so that it can be lined into rust.

- [rocketry] is an ongoing learning project of creating and flying a thrust vector
  controlled rocket. I try to keep an [ongoing devlog][rocketry-website] but keep
  no promises. This project has been superseded by the pico-pilot project.

- [preflight] is an attempt at end to end testing of flight software with as little
  setup as needed. It aims to be able to run SITL (Software In The Loop) simulations
  interfacing with firmware directly with the ease of running unit tests. In its
  current state, it would not make sense to, but the system may grow to be able
  to run HITL (Hardware In The Loop) simulations. This is built around the Rust
  macro system.

- [pico-pilot] is my most recent rocketry project using the raspberry pi pico as
  the main controller for rocketry avionics. This project consists of several parts.
  pico-pilot housing the firmware and any libraries used.

  - [pico-avionics] houses the kicad and other mechanical designs that describe
    the physical form of the avionics.
  - [pico-mct] Houses the mission control software that interfaces with the pico-pilot
    firmware to relay live telemetry data and to send commands to the flight control
    software.

- [kicad-library] is a conglomeration of all custom kicad footprints, 3d models,
  and libraries that I was unable to find existing versions of. This library is
  layed out in a way that others can use it, but is very specific to my projects
  and use cases.

  - [RP_Silicon_KiCad] Is a fork of someone's copy of the official Raspberry Pi
    Pico and RP2040 kicad libraries that I have expanded on with 3d models and
    other fixes and improvements.

- [vote] is a tool used to authenticate discord users in polls to prevent and
  detect vote manipulation. Yes, this is not super serious or super important
  but it makes polls with middle school children much easier since they
  can not manipulate it for fun.

</details>

## Notable Previous Projects

<sup>Last updated June 30, 2021</sup>

<details>
 <summary><b>Expand/Collapse</b></summary>

- [calc-ab-senior-project] was an animation created for my AP Calculus AB class
  senior year of high school. The animation describes, visually, the connection
  between derivatives and the secant lines of a curve. This animation was created
  with [manim], a tool created by [Grant Sanderson (3Blue1Brown)][3blue1brown]
  like to programmatically generate the animations seen in his videos.

- [WHS Helper App][whsha] was my first big user facing project. An IOS/Android
  app to help students manage their confusing schedule in my school. This app was
  a large success at first, but I have learned a lot about app development through
  the process of making it, and definitely learned that spending almost all of my
  waking hours on this project had been wearing me down. Since no one in the school
  was able to or willing to take up the app, when I graduate, it will more or less
  fade into oblivion.

- [sxfs] was maybe the first project I have made, that had a successful 2nd version.
  This app is a simple file server for screenshot uploads from the ShareX utility.
  I have since switched to daily driving linux, meaning that I can no longer use
  ShareX. I know that this basically could have been implemented in nginx configs,
  but it was a good learning experience for backend rust and typescript projects.

- [stfu] being a personal hobby project, it has an unprofessional name, but
  actually is a little useful project. It is a daemon/client duo that can easily
  mute a whole discord channel with ease and quickly (after the first cold run
  due to the slowness of the daemon starting)

- [BicBacBoe] was my first full stack web application that was a simple 1v1
  tic-tac-toe game. It's server code has long been lost, but it was my first project
  I was able to share with friends. I even tried to make a second (failed) version
  that can be found [here][bicbacboe-2]

- [Beepus], [WHS Help Bot][whshelpbot], and [RobbieBotten] were discord bots that
  I had made for specific discord servers. Beepus was a great moderation bot, but
  was never used enough before the server ended up dying. Robbie Botten on the other
  hand was deployed in a huge community server and got tons of use, but after I had
  left the server, its use became limited and eventually was taken offline. The WHS
  Help Bot never really became much, but its goal was to be a role management bot
  for a school discord server, that like many, died before the bot was done.

- [LoginWithDiscord] was maybe and biggest library that I have made. It was
  designed to be a super simple, one function call, login button for discord.
  It was never reliable enough to truly use but many people picked it up, (many of
  who had no idea what they were doing, they just saw the words login and discord)
  and it became a mess to maintain, eventually being released into the dustyard
  after a failed rewrite of the library.

- [StoragePlus] was a small spigot minecraft plugin that provided backpack/shulker
  box like tools. Minecraft eventually added native tools to achieve this better,
  which lead to me abandoning the project.

- [Mechan.js] was maybe the library that I put the most work into, a command
  handling library for discord, in typescript. It involved a bunch of new challenges,
  such as parsing and creating a good, well thought out user facing API. This library
  was eventually scrapped, as I moved away from typescript for backend services,
  but still holds a place near and dear in my heart. The part I am most proud of
  are the documentation website which has detailed documentation written all out
  by hand ([mechan.js.org])

- [GUIShopMinus] was going to be a FOSS (Free and Open Source Software) alternative
  to the popular GUIShopPlus spigot plugin with a web GUI to configure the shop.
  The MC server that it was commissioned for eventually fell through, but the shop
  plugin still had a lot of work to be done, so it was abandoned.

- [Matts Mashups][lemmiejustyeet] was a commissioned website for a friend who
  wanted a place to store and share their musical mashups of songs. It came fully
  to fruition, but the person who it was created for never ended up using it and
  eventually I took the server offline. It was very useful as practice to learn
  about databases, for it was the first heavily database centered program I made.

- [React TypeDoc][reacttypedoc] was a failed attempt to automate the process of
  making typescript docs and to put them in a cool, sexy, react based SPI. The
  documentation on typedoc at the time was sparse, so making a tool to understand
  the typedoc output was a pain, more than it was worth, eventually leaving me to
  abandon the project.

- [BYOB] or Build Your Own Bot, was an idea to create a modular discord bot which
  could serve almost all purposes. People would be able to develop their modules
  for the bot and users of the bot could enable and disable the modules according
  to their use case. The modules were meant to be super simple, either in LUA or
  some other custom programming language so that anyone could just pick it up and
  make a plugin for their server. This ended up not making sense in the long run,
  due to the complexities.

- [MGMT] was an idea to create a custom server management panel, tightly integrated
  into minecraft so that you could more closely control you minecraft servers, and
  waste less clock cycles on the webpanel, by writing it in rust, over the more
  common Java.

- [MCProxy] was an extension of MGMT that actually came to fruition. It was a
  reverse proxy for minecraft servers, allowing multiple discord servers to run
  over the same port. This, if integrated into MGMT would remove the need to port
  forward every single mc server, and instead just create A/CNAME records to point
  to the same server, which will then get filtered by their connecting record.

</details>

## Abandoned Projects

All of my old/abandoned projects can be found under the organization [@TheDustyard]
and also on the website [dustyard.dusterthefirst.com][dustyard]. This organization
is purely to unclutter my account from old and abandoned projects, that have not
been touched for a while.

[@thedustyard]: https://github.com/TheDustyard
[3blue1brown]: https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw
[annoy]: https://github.com/DusterTheFirst/annoy
[arduinoteensy-better-ffi]: https://github.com/DusterTheFirst/framework-arduinoteensy-better-ffi
[arduinoteensy]: https://docs.platformio.org/en/latest/frameworks/arduino.html
[beepus]: https://github.com/TheDustyard/beepus
[bicbacboe-2]: https://github.com/TheDustyard/bicbacboe
[bicbacboe]: https://github.com/TheDustyard/bicbacboe-1.0
[byob]: https://github.com/TheDustyard/BYOB
[calc-ab-senior-project]: https://github.com/DusterTheFirst/calc-ab-senior-project
[dustyard]: https://dustyard.dusterthefirst.com/
[guishopminus]: https://github.com/whsmc/GUIShopMinus
[kicad-library]: https://github.com/DusterTheFirst/kicad-library
[lemmiejustyeet]: https://github.com/lemmiejustyeet
[loginwithdiscord]: https://github.com/TheDustyard/Login-With-Discord
[manim]: https://github.com/ManimCommunity/manim
[mcproxy]: https://github.com/DusterTheFirst/mcproxy
[mechan.js.org]: https://mechan.js.org/docs
[mechan.js]: https://github.com/TheDustyard/mechan.js
[mgmt]: https://github.com/DusterTheFirst/MGMT
[pico-avionics]: https://github.com/DusterTheFirst/pico-avionics
[pico-mct]: https://github.com/DusterTheFirst/pico-mct
[pico-pilot]: https://github.com/DusterTheFirst/pico-pilot
[pico]: https://www.raspberrypi.org/products/raspberry-pi-pico/
[preflight]: https://github.com/DusterTheFirst/preflight
[react]: https://reactjs.org/
[reacttypedoc]: https://github.com/reacttypedoc
[robbiebotten]: https://github.com/TheDustyard/RobbieBotten
[rocketry-website]: https://rocketry.dusterthefirst.com
[rocketry]: https://github.com/DusterTheFirst/rocketry
[rp_silicon_kicad]: https://github.com/DusterTheFirst/RP_Silicon_KiCad
[rust]: https://www.rust-lang.org/
[sd]: https://github.com/DusterTheFirst/sd
[stfu]: https://github.com/DusterTheFirst/stfu
[storageplus]: https://github.com/TheDustyard/StoragePlus
[sxfs]: https://github.com/DusterTheFirst/sxfs
[teensyduino-rs]: https://github.com/DusterTheFirst/teensyduino-rs
[typescript]: https://www.typescriptlang.org/
[vote]: https://github.com/DusterTheFirst/vote
[whsha]: https://github.com/whsha
[whshelpbot]: https://github.com/TheDustyard/WHS-Help-Bot
