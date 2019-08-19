# ubucon-europe-2019
Repository for Ubucon Europe 2019 related files


## Presentation slides
Check the templates for the presentations.

Formats available (order of preference):
1. HTML ([remark](https://remarkjs.com)) |  **prefered** dependency: browser<br>
1. ODP (Open Document Presentation) | dependency: LibreOffice / OpenOffice
1. Google Slides ([presentation link](https://docs.google.com/presentation/d/1CMGgc3AYt62IExihr3l_ksS9GEZyWUnoJIVHZeGeZhA/edit?usp=sharing)) | dependency: browser
1. PPTX (MS Powerpoint Presentation) | dependency: Windows + MS Office (PowerPoint)
1. KEY (Keynote) | dependency: MacOS + Keynote 

See below the usage instructions for each format, or the color schemes and instructions to build the ubucon theme (wip).


## Usage Instructions

### HTML (remark) **prefered**

**requirements:** browser

1. Copy the source from `presentation-templates/remark`. 
1. Just open the `index.html` and edit the presentation slides inside the `<textarea id="source">` ... `</textarea>`
1. This is just markdown syntax with some css. Pretty easy.
1. Images should go to `img/some_image.jpg` folder and referenced in the presentation as `<img src="img/some_image.jpg" width="200">`. Recommended formats are `.jpg`, `.png` and `.svg`, but you could use [other formats](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Img#Supported_image_formats)  
1. The template should provide enough examples for most use cases. If you want to explore more funcionality, head to https://remarkjs.com, or ask for help in the speakers channel.


### ODP (Open Document Presentation)

**requirements:** libreoffice | openoffice (or other presentation sofware that can read ODP)

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides.


### Google Slides 

**requirements:** browser

**presentation link:** https://docs.google.com/presentation/d/1CMGgc3AYt62IExihr3l_ksS9GEZyWUnoJIVHZeGeZhA/edit?usp=sharing

### PPTX (MS Powerpoint Presentation) 

**requirements:** Windows + MS Office (PowerPoint)

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides.


### KEY (Keynote) 
**requirements:** MacOS + Keynote 

* Open the template file, and edit from there.
* If you already have a presentation in another theme, apply the ubucon theme to it and review all slides:
  * open the `ubucon.europe.2019-keynote.theme.kth`
  * choose "Add to Theme Chooser"
  * then open your presentation
  * go to File > Change Theme
  * validate all slides


## Ubucon theme

This ubucon theme follows the [Ubuntu Brand Guidelines](https://design.ubuntu.com/). Here are some theme specific guidelines.

### Fonts
Download them here (Resources): https://design.ubuntu.com/font/ 

* **Ubuntu Condensed**: 2nd+ order subtitles
* **Ubuntu Mono**: code
* **Ubuntu**: Title, Body, everything else

### Colors 
https://design.ubuntu.com/brand/colour-palette/

* Title: <span style="color:#E95420">&#9632;</span> #E95420
* 2nd sub-title: <span style="color:#ED764D">&#9632;</span> #ED764D
* 3rd sub-title: <span style="color:#AEA79F">&#9632;</span> #AEA79F
* Body: <span style="color:#000000">&#9632;</span> #000000
* Slide number: <span style="color:#FBDDD2">&#9632;</span> #FBDDD2
* Code background: <span style="color:#E2E0DD">&#9632;</span> #E2E0DD
* Code text: <span style="color:#111111">&#9632;</span> #111111
* Highlighted code backgroung: <span style="color:#6B4C61">&#9632;</span> #6B4C61
* Highlighted code text: <span style="color:#EAE9E7">&#9632;</span> #EAE9E7
* Impact/Quote slide background: <span style="color:#5E2750">&#9632;</span> #5E2750
* Impact/Quote slide text: <span style="color:#EEEEEE">&#9632;</span> #EEEEEE