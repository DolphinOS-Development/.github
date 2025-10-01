# DolphinOS

## What is DolphinOS

DolphinOS is project that can convert any x86_64 system into a functional Wii console.

The OS itself is a modified Arch Linux distribution, and the main piece of software it uses is the Dolphin Wii emulator.
The OS is configured so that the system automatically "seems to boot" directly into the Wii system. 

## Why DolphinOS

The main idea of this project lied on the possiblity to be able to mimic or use a computer as if it was a "real" gaming console. The main reason to use Dolphin or the Wii emulation is because Dolphin can load the Wii OS and its main menu, as well as the ability to run games from the Wii main menu, so it can give the feel to be using a real system.

This idea evolved and it became my final Computer Engineering degree project. 

## Final degree project

This project began as my final degree project. The first steps that were carried out was to create and build the development and DevOps environment using GitHub technologies, such as the online repositories for the Git VCS and GitHub Actions for the DevOps build automation part. After getting the infrastructure working the development of the OS began.

This project thesis was finally defended on 20/07/2023, awarded with an outstanding score of 9.7 out of 10.

The thesis dissertation in Spanish can be checked [here](Thesis/Trabajo%20Fin%20de%20Grado%20-%20Diego%20Jesus%20Berenguel%20Garcia.pdf)

## Current and future work

The idea of this project was to not only build a demo for my thesis, but to create an OS that people can be able to use and enjoy. Currently, the project is in the status of being improved and continued. Most of the DevOps automation on GitHub Actions has been rebuilt to be more robust and fail proof, although there are still some things to improve.

### Future lines of work

The TO-DO list of things that are going to be carried out in a short-mid term are the following:

- [x] Rebuild DevOps automation (GitHub Actions).
- [ ] Improve DolphinOS installation system.
- [ ] Improve and continue development of DolphinOS-WebApp.
- [ ] Develop a way to update the system from the WebApp, bearing in mind failsafe mechanisms if the update fails.
- [ ] Migration from Xorg (X11) to Wayland compositors (gamescope).

At long term, one of the things I am thinking would be to be able to migrate the project from Arch Linux to an inmutable OS approach, maybe based on Ublue or similar distributions, which could allow to create a custom distribution with a custom installer, and which could create reproducible builds and be easier to maintain.
