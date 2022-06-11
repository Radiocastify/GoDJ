# GoDJ

A modern, cross platform Internet DJ streaming client & console heavily inspired by the awesome Internet DJ Console. (See https://idjc.sourceforge.io/)

** VERY ROUGH FIRST DRAFT **

## Why not just use IDJC?

I don't want to dedicate a machine to run an older version of Linux just to be able to play DJ. While I have had some success running IDJC under WSL2 with a X windows manager for Windows, it was buggy and unreliable.

## My Vision
I'd like to see a community effort to fill in missing functionality of the application I can't yet wrap my head around. Audio processing features like audio ducking, audio normalization, compressor and limiter features, etc should be easy and sound great.

The software should be themable as well, allowing people to choose themes or design their own.

## Help wanted.
I have only ever written a few programs in Go. Audio processing will be the most challenging so any help in this area could make this program a reality much sooner. I'm looking at using Portaudio for it's cross-platform audio interfacing, Fyrne.io for the graphical user interface and a build system to make it available for as many platforms as possible.

I am building a website for GoDJ, but I lack skills for graphic design. I'd love to get some help on a beautiful branding strategy for the website and the software.

## Target platforms
Obviously, the major platforms like Windows, Linux & macOS would be the targets. Going beyond that, it may be possible to bring this software to Android & iOS as well, as long as great care is taken to limit dependencies that are limited to specific platforms and architectures. It is important to write as much of the code in Go as possible. C++ can be used sparingly but only where required.

## Timeline
Sadly, I don't have a lot of free time. I will scaffold the project as much as I can for the point and click/touch interfaces and then begin the process of filling in the features. This could take me many months of hard work. With the assistance of the community, we may have something much sooner than I anticipate.

## Funding
This is a big part of why this project may be slow. After I get scaffolding going, I will begin soliciting sponsorships to keep some money coming in while I work on this project. Code contributions are also greatly appreciated.
