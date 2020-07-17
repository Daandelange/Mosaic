![Mosaic logo](https://github.com/d3cod3/Mosaic/raw/master/process/logo/logo_150.png)

# [MOSAIC](https://mosaic.d3cod3.org) - an openFrameworks based Visual Patching Creative-Coding Platform

![Mosaic](https://github.com/d3cod3/Mosaic/raw/master/process/img/24_videoSynth.jpg)

[![Slack MosaicProcess](https://img.shields.io/badge/slack-Mosaic-green.svg?logo=slack&longCache=true&colorB=E80C7A)](https://mosaicprocess.slack.com)

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V21B90C)


“[YOUR REPO] is being sponsored by the following tool; please help to support us by taking a look and signing up to a free trial”

<a href="https://tracking.gitads.io/?repo=YOUR_REPO"> <img src="https://images.gitads.io/YOUR_REPO" alt="GitAds"/> </a>

__

Table of Contents
=================

   * [INSTALL](#install)
   * [OF_COMPATIBLE_RELEASE](#of_compatible_release)
   * [DEPENDENCIES](#dependencies)
   * [DESCRIPTION](#description)
   * [SPECIFICATIONS](#specifications)
   * [SCREENSHOTS](#screenshots)
   * [LICENSE](#license)
   * [CREDITS](#credits)


# INSTALL

## LINUX

Check the Mosaic installer here: https://github.com/d3cod3/Mosaic-Installer

## MACOS

Get Mosaic last release here: https://github.com/d3cod3/Mosaic/releases
Just unzip the downloaded release and copy Mosaic app in your Application folder, that's it!

## WINDOWS

Check the Mosaic installer here: https://github.com/d3cod3/Mosaic-Installer

# OF COMPATIBLE RELEASE

## 0.11.0 STABLE (official download from [OF site](https://openframeworks.cc/))
> Compiled/tested with QTCreator on osx/linux/windows

If you want to build Mosaic, just download OF0.11.0 for your OS (osx, linux, windows) and follow the correspondent setup guide.

# DESCRIPTION

![Mosaic-Data-Flow-Diagram](https://github.com/d3cod3/Mosaic/raw/master/process/img/10_Mosaic-Data-Flow-Diagram.jpg)

Mosaic is an open source multi-platform (osx, linux, windows) live coding and visual programming application, based on openFrameworks.

This project deals with the idea of integrate/amplify human-machine communication, offering a real-time flowchart based visual interface for high level creative coding. As live-coding scripting languages offer a high level coding environment, ofxVisualProgramming and the Mosaic Project as his parent layer container, aim at a high level visual-programming environment, with embedded multi scripting languages availability (Lua, GLSL, Python and BASH(macOS & linux) ).

As this project is based on openFrameworks, one of the goals is to offer as more objects as possible, using the pre-defined OF classes for trans-media manipulation (audio, text, image, video, electronics, computer vision), plus all the gigantic ofxaddons ecosystem actually available (machine learning, protocols, web, hardware interface, among a lot more).

While the described characteristics could potentially offer an extremely high complex result (OF and OFXADDONS ecosystem is really huge, and the possibility of multiple scripting languages could lead every unexperienced user to confusion), the idea behind the interface design aim at avoiding the "high complex" situation, embodying a direct and natural drag&drop connect/disconnet interface (mouse/trackpad) on the most basic level of interaction, adding text editing (keyboard) on a intermediate level of interaction (script editing), following most advanced level of interaction for experienced users (external devices communication, automated interaction, etc...)


#### KEYWORDS
Mosaic, ofxVisualProgramming, openframeworks, linux, macOS, windows, creative-coding, live-coding, physical, visual, scripting, transmedia, programming, visual-programming

# DEPENDENCIES

#### [ofxAudioAnalyzer](https://github.com/d3cod3/ofxAudioAnalyzer) -- Fork

#### [ofxAudioFile](https://github.com/npisanti/ofxAudioFile)

#### [ofxBTrack](https://github.com/d3cod3/ofxBTrack) -- Fork

#### [ofxChromaKeyShader](https://github.com/d3cod3/ofxChromaKeyShader) -- Fork

#### [ofxCv](https://github.com/kylemcdonald/ofxCv)

#### [ofxDatGui](https://github.com/d3cod3/ofxDatGui) -- Fork

#### [ofxEasing](https://github.com/arturoc/ofxEasing)

#### [ofxFFmpegRecorder](https://github.com/d3cod3/ofxFFmpegRecorder) -- Fork

#### [ofxFontStash](https://github.com/d3cod3/ofxFontStash) -- Fork

#### [ofxGLEditor](https://github.com/d3cod3/ofxGLEditor) -- Fork

#### [ofxHistoryPlot](https://github.com/armadillu/ofxHistoryPlot)

#### [ofxJava](https://github.com/d3cod3/ofxJava)

#### [ofxJSON](https://github.com/jeffcrouse/ofxJSON)

#### [ofxImGui](https://github.com/d3cod3/ofxImGui) -- Fork

#### [ofxInfiniteCanvas](https://github.com/d3cod3/ofxInfiniteCanvas) -- Fork

#### [ofxLua](https://github.com/d3cod3/ofxLua) -- Fork

#### [ofxMidi](https://github.com/d3cod3/ofxMidi) -- Fork

#### [ofxMtlMapping2D](https://github.com/d3cod3/ofxMtlMapping2D) -- Fork

#### [ofxNDI](https://github.com/d3cod3/ofxNDI) -- Fork

#### [ofxParagraph](https://github.com/d3cod3/ofxParagraph) -- Fork

#### [ofxPd](https://github.com/danomatika/ofxPd)

#### [ofxPdExternals](https://github.com/d3cod3/ofxPdExternals)

#### [ofxPDSP](https://github.com/npisanti/ofxPDSP)

#### [ofxPython](https://github.com/d3cod3/ofxPython) -- Fork

#### [ofxSimpleHttp](https://github.com/armadillu/ofxSimpleHttp)

#### [ofxThreadedFileDialog](https://github.com/d3cod3/ofxThreadedFileDialog)

#### [ofxTimeline](https://github.com/d3cod3/ofxTimeline) -- Fork

#### [ofxTimeMeasurements](https://github.com/armadillu/ofxTimeMeasurements)

#### [ofxVisualProgramming](https://github.com/d3cod3/ofxVisualProgramming)

#### [ofxWarp](https://github.com/d3cod3/ofxWarp) -- Fork

Some addons are forks of the original, due to some mods, compatibility with OF0.11 and the intention of cross-platform compiling (osx,linux,win)


# SPECIFICATIONS

    - cross-platform
    - multi-threaded
    - non-blocking system dialogs
    - lua/python/glsl/bash live-coding
    - pure data live-patching
    - non-linear interactive timeline
    - warping integrated on output window object
    - mapmap style projection mapping module


#### OFXADDONS

Clone all the required addons listed:

```bash
cd <your_openframeworks_release_folder>/addons

git clone https://github.com/d3cod3/ofxAudioAnalyzer
git clone https://github.com/npisanti/ofxAudioFile
git clone https://github.com/d3cod3/ofxBTrack
git clone https://github.com/d3cod3/ofxChromaKeyShader
git clone https://github.com/kylemcdonald/ofxCv
git clone https://github.com/d3cod3/ofxDatGui
git clone https://github.com/arturoc/ofxEasing
git clone https://github.com/d3cod3/ofxFFmpegRecorder
git clone https://github.com/d3cod3/ofxFontStash
git clone https://github.com/d3cod3/ofxGLEditor
git clone https://github.com/armadillu/ofxGLError
git clone https://github.com/armadillu/ofxHistoryPlot
git clone https://github.com/d3cod3/ofxJava
git clone https://github.com/jeffcrouse/ofxJSON
git clone https://github.com/d3cod3/ofxImGui
git clone https://github.com/d3cod3/ofxInfiniteCanvas
git clone --branch=of-0.10.0 https://github.com/d3cod3/ofxLua
git clone https://github.com/d3cod3/ofxMidi
git clone https://github.com/d3cod3/ofxMtlMapping2D
git clone https://github.com/d3cod3/ofxNDI
git clone --branch=OF0.9.8 https://github.com/d3cod3/ofxPython
git clone https://github.com/d3cod3/ofxParagraph
git clone https://github.com/danomatika/ofxPd
git clone https://github.com/d3cod3/ofxPdExternals
git clone https://github.com/npisanti/ofxPDSP
git clone https://github.com/armadillu/ofxSimpleHttp
git clone https://github.com/d3cod3/ofxThreadedFileDialog
git clone https://github.com/d3cod3/ofxTimeline
git clone https://github.com/armadillu/ofxTimeMeasurements
git clone https://github.com/d3cod3/ofxVisualProgramming
git clone https://github.com/d3cod3/ofxWarp

```

Then clone Mosaic project as an openFrameworks example:

```bash
cd <your_openframeworks_release_folder>/apps/myApps

git clone --recursive https://github.com/d3cod3/Mosaic
```

Now you're ready to compile Mosaic! Load the .qbs project in QTCreator and compile it. Or just enter in Mosaic folder and run a make Release.

# SCREENSHOTS

![Mosaic pre_0.2.0](https://github.com/d3cod3/Mosaic/raw/master/process/img/23_helloSonogram.jpg)

![Mosaic pre_0.2.0](https://github.com/d3cod3/Mosaic/raw/master/process/img/22_Ry_ofLoffler.jpg)

![Mosaic 0.1.7](https://github.com/d3cod3/Mosaic/raw/master/process/img/21_mappingBebop.jpg)

![Mosaic 0.1.7](https://github.com/d3cod3/Mosaic/raw/master/process/img/20_jupiterBlues.jpg)

![Mosaic pre_0.1.7](https://github.com/d3cod3/Mosaic/raw/master/process/img/19_rememberPD.jpg)

![Mosaic pre_0.1.6](https://github.com/d3cod3/Mosaic/raw/master/process/img/18_pre0.1.6.jpg)

![Mosaic pre_alpha_0.1.0](https://github.com/d3cod3/Mosaic/raw/master/process/img/09_we_are_near_alpha_station.png)

![Mosaic pre_alpha_0.1.0](https://github.com/d3cod3/Mosaic/raw/master/process/img/08_life_is_full_of_possibilities.png)

![Mosaic on linux](https://github.com/d3cod3/Mosaic/raw/master/process/img/03_Mosaic_linux_cinnamon_screenshot.png)

![Mosaic on windows](https://github.com/d3cod3/Mosaic/raw/master/process/img/04_Mosaic_windows_screenshot.png)

# LICENSE

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

All contributions are made under the [MIT License](https://opensource.org/licenses/MIT). See [LICENSE](https://github.com/d3cod3/Mosaic/blob/master/LICENSE.md).

# CREDITS

Mosaic is an open source project.

The Mosaic team is composed by Emanuele Mazza and Maria José Martínez de Pisón.

Mosaic uses [FFTW3](http://fftw.org/),  [essentia](http://essentia.upf.edu/documentation/), [kiss_fft](https://github.com/mborgerding/kissfft), [libsamplerate](https://github.com/erikd/libsamplerate), [dr_libs](https://github.com/mackron/dr_libs), [fontstash](https://github.com/memononen/fontstash) and code from openframeworks all the included ofxAddons.
