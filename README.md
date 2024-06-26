# Blot, the plotter bot from Hack Club

**[🕸 Landing Page](https://blot.hackclub.com)** | **[💻 Online Editor](https://blot.hackclub.com/editor)** | **[👀 Gallery](https://blot.hackclub.com/gallery)**

Create programmatic art in our web-based editor and submit it to the gallery and we'll send you a CNC machine which can make that art.
Blot is a [**You Ship, We Ship**](https://github.com/hackclub/blot/tree/main?tab=readme-ov-file#you-ship-we-ship) project from [Hack Club](https://hackclub.com). 

> Everything about Blot is open source. The online editor and drawing library can be freely used by anyone, and we encourage all to submit to the gallery through PRs! However, you must be a teenager or younger to receive a free machine.

<img width="600" alt="blot-white-bg" src="https://github.com/hackclub/blot/assets/27078897/e332631f-1232-4ac5-a573-57b0c570e980" />

A piece of art made for Blot can be the first program you ever write, but it can also be a challenge for a master programmer. Check out some of the art made already in our [gallery](https://blot.hackclub.com/gallery). Every piece of art you see is actually a program. Many of them create unique pieces everytime the art is run. You may be looking at an artwork which has never been seen before, even by the creator.

# How It Works

### 1) Create a piece of programatic art in the web editor.

To learn the Blot drawing library follow our [getting started guide](https://blot.hackclub.com/editor?guide=start). Check out the examples in the [gallery](https://blot.hackclub.com/gallery) and then follow along with some of our [guides](https://blot.hackclub.com/guides).

<img width="500" alt="editor" src="https://github.com/hackclub/blot/assets/27078897/ec685c69-ec9b-405a-9dbc-fda82c3f1d2b">

### 2) Submit that art to the public gallery.

The [submission rules to get a Blot for a PR are here](https://github.com/hackclub/blot/blob/main/docs/GET_A_BLOT.md). **You must be a teenager (or younger to qualify for a free machine)** but anyone can make art and make a PR.

[<img width="500" src="https://github.com/hackclub/blot/assets/27078897/5666011a-089e-44d9-8956-5c283f00ff14"/>](https://blot.hackclub.com/gallery)

### 3) Receive the parts to build your own Blot that can draw that art in real life.

The [bill of materials can be found here](/docs/BOM.toml) and an [assembly guide here](/docs/ASSEMBLY.md).

<img width="500" alt="all-parts" src="https://github.com/hackclub/blot/assets/27078897/8559466d-fd36-4126-bf9c-45cb913be6da" />

<img width="500" alt="drawing" src="https://github.com/hackclub/blot/assets/27078897/87f7e5b3-1aee-4082-8ae5-36006ec1ab0d" />

<!-- <img height="341" alt="drawing" src="https://github.com/hackclub/blot/assets/27078897/2f7c9c17-3b67-4674-b2ca-2a4dbd26a3d1" /> -->

# Blot is...

**A custom CNC drawing machine** designed from scratch to introduce you to digital fabrication. 
It's made of 6 unique 3D printed parts with a custom control board and easy to understand firmware, which can be interfaced with through JavaScript in the browser.
Blot is designed in OnShape. Check out the [3D model of the project](https://cad.onshape.com/documents/0bcd2f50d2614ea26189f43b/w/23913e7defc94fc29f7833e6/e/72ea852bfc1822955e506e37?renderMode=0&uiState=6538235d42737a70b1996741).
You can find the [bill of materials here](/docs/BOM.toml) if you'd like to 3D print your Blot [the parts are here](https://github.com/hackclub/blot/tree/main/hardware/mechanical/drawing-thing-v4). The entire build costs about $150 dollars. If you're a teen we will give you all the parts for a PR with your an art piece you coded yourself.

**A web based editor for programmatic art** that we designed specifically for pen plotting with a [custom geometry library](/docs/DOCUMENTATION.md).
We practiced programmatic pen plotting with [some](https://github.com/LingDong-) [amazing artists](https://static1.squarespace.com/static/63fbc39db5b01b5fa30423db/t/649b424d33b2ce3e0d5b63a5/1687896656015/June+Cohort+Zine.pdf). 
There is so much to learn and explore on the programming and the aesthetic side. 

<img width="300" alt="parts" src="https://github.com/hackclub/blot/assets/27078897/04ab7345-03fa-4b60-9870-64a99327e8cd">

<img width="300" src="https://github.com/hackclub/blot/assets/27078897/0ffc0ca8-516b-4f9a-b34e-4f09218e41cd"/>

# It's All Open Source

Every part of Blot is freely available for you to investigate and discover. 
That includes the editor, the hardware design, the electronics, and even the finances around the project.
We think people deserve tools they can take ownership of. That's why we give away the source for free. 

Our projects at Hack Club have hundreds of teenage contributors from all over the world, if you want to learn how to program we invite you to jump in and start building tools used by thousands.

You're also welcome to participate and use our tools if you aren't a teen (like making art or building your own blot). But our [online community](https://hackclub.com/slack) is for teens only.

# You Ship, We Ship

At Hack Club we're reimagining a new type of public education for technology. We believe people learn best by creating things they care about and sharing them with others. We build open source creative tools with young people all around the world. These tools are gateways to new subjects in technology like [embedded systems](https://sprig.hackclub.com), [circuits](https://onboard.hackclub.com) or digital fabrication robotics. When teenagers build things with our tools we send them more creative materials for free. 

Our goal is to build a new type of library online that offers learners not just media to consume but tools to create. And it is free and open source to all. We're just getting started...

# Development

Join the `#blot` channel on the [Hack Club Slack](https://hackclub.com/slack). 

The Blot editor is run with an express server.

```
Git
Node.js
Yarn
```

After installing those, clone the repo.

```
git clone https://github.com/hackclub/blot/
yarn install
```

To run the development server.

```
yarn dev
```

# License
The Hack Club Blot is open source and licensed under the [MIT License](https://github.com/hackclub/blot/LICENSE.md). Fork, remix, and make it your own! Pull requests and other contributions greatly appreciated.
