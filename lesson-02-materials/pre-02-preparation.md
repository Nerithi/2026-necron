---
title: Pre-lesson 02 preparation instructions
author: Elisabeth Maria Magin
date: February 2026
---

# Software for the second lesson

For the second lesson, please follow the instructions below regarding software installation:

1. If you attended the first lesson and already have the required software for that installed, you only need to install [LaTeχ](#latex-install) in addition.
2. If you did not attend the first lesson and have not installed the software required for that, please ensure you install [the software from the first lesson](https://github.com/Nerithi/2026-necron/blob/fe6698ddfe9efea38d267d4a4c8875b0cd5eb3ad/lesson-01-materials/pre-01-preparation.md) in addition to [LaTeχ](#latex-install). Please also familiarise yourself with the Zettlr interface.

## LaTeχ {#latex-install}

LaTeχ is software that typesets documents and also a high-level markup language. It is very popular in the natural sciences and widely available for download from the institutional software centres at universities and other institutions. While vastly more powerful than Markdown (you can, for example, produce entire flowcharts and illustrations with LaTeχ alone), it is also more complex and difficult to learn.

However, with LaTeχ installed in the background on your computer, Markdown documents can easily be exported into and further processed into print-ready PDF documents without you having to directly interact with LaTeχ. In the second lesson, we are going to start using LaTeχ as the background output engine for PDF documents.

To install it, you should first check if your institution offers LaTeχ via their software centre. If it isn’t available or you are working on your personal computer, you can choose between the two distributions below, but only install **one** of them. If you run into trouble, please contact me at <e.m.magin+necron@khm.uio.no>.

**Installing LaTeχ can take up to several hours, especially when installing from an institutional source. It can run in the background while you work, but make sure you can give it at least 2-3 hours to run, more if your internet connection is bad or your hardware is old.**

### TeX Live

[TeX Live](https://www.tug.org/texlive/) is available for Windows, Linux and MacOS. While the page may look slightly intimidating at first, please be assured that if you follow the instructions for your system, the install is fairly straightforward. Find the right instructions and download for your system and follow them. Linux users can also check whether their distribution has TeX Live in the repositories. Be aware that it may be an older version. If in question, you can contact me.

Note that a full install of TeX Live might take up to 10GB on your computer. You’re unlikely to ever use all of the packages (there are hundreds) for your work, but if you want to keep it simple, a full install is the easiest option. On Windows, once you double-click, the [installer](https://tug.org/texlive/doc/texlive-en/texlive-en.html#x1-15001r1) should open. It will ask you for confirmation again, and if you agree, a window with green code pops up. *That is normal, expected and should happen.* You don’t need to worry about that window, just don’t close it until everything has finished installing. Another [window](https://tug.org/texlive/doc/texlive-en/texlive-en.html#x1-18062r3) will open in addition. Click Advanced for [more options](https://tug.org/texlive/doc/texlive-en/texlive-en.html#x1-18063r4). Under **Selections,** you can choose to install a different scheme, meaning the installation size will shrink. Clicking on **Customise** next to *N. of collections* lets you choose precisely which packages you would like to install – you can, for example, choose not to install all languages.

**You don’t have to customise your install if you’re feeling uncertain. Please only customise your install if you’re pressed for space or you feel comfortable doing so.**

Once you click "install", TeX Live will start installing on your computer. Simply let it run in the background and don’t close either of the two windows.

### MiKTeX

[MiKTeX](https://miktex.org/download) is available for Windows, Linux and MacOS, but supports fewer versions of operating systems. Remember the check the prerequisites before you install.

Other than TeX Live, which installs all packages by default, MiKTeX only installs the basic scheme. For the natural sciences, this is usually enough. As Humanities scholars, however, we may need packages not included in the basic install. Once you accept the conditions, you can choose between installing for everyone or just for yourself. If you’re on an institutional computer, definitely choose the latter. On your private computer, choose whichever suits you best. Leave the installation directory as is and in the next step, set “install missing packages on-the-fly” to **Yes**. That is the easiest way to ensure that MiKTeX will automatically fetch and install every package you’re missing without you having to do anything.

**When packages are installed on the fly and your document needs a previously-uninstalled package, the first export will take longer, perhaps even several minutes depending on how big the new package is. Do *not* interrupt or abort the export process, it will eventually finish after the new package has been installed.**

## Portable LaTeχ-installations

If you cannot install LaTeχ from an institutional source nor directly on our computer, there is the option of installing it as a portable installation on an external medium such as a USB, HDD or SSD. Both TeX Live and MikTeX offer an option for a portable install and provide instructions for how to do it. For MiKTeX, this means renaming the installation file to “miktex-portable.exe” and following [the instructions](https://miktex.org/howto/portable-edition), for TeX Live, you need to choose “Portable setup” in the Advanced installation options. In both cases, **ensure that the installation path points at your portable medium.**

If you struggle with it, please get in touch with me directly at <e.m.magin+necron@khm.uio.no>.
