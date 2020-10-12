# Google Pac-Man doodle (with offline mode)

Google's 30th anniversary Pac-Man doodle, extracted from the [Doodles Archive](https://www.google.com/logos/2010/pacman10-hp.html?=en), fully functional to work offline.

<p align="center">
  <img src="https://user-images.githubusercontent.com/68722732/95759774-c6bb5100-0c6f-11eb-8310-e38bf6b0841c.jpg" alt="google-pacman" style="max-width:100%;">
</p>

<p align="center">
  <a href="https://manuel.life/download-google-pacman-play-offline/"><strong>DEMO</strong></a>
</p>

## Instructions

1. Download the [latest version](https://github.com/ManuelFte/Google-Pacman/archive/master.zip) and unzip it
2. Install [Python 3](https://www.python.org/downloads/) (if your system doesn't have it already)
3. Open a terminal and browse to the `Google-Pacman-master` folder
4. Run Python's local server: 
   
   ```
   python3 -m http.server 8000
   ```

5. The doodle is now available at `http://localhost:8000`

## Modifications

Besides the necessary adaptations to work outside Google's website, the following alterations were made to the source code:

1. Beautified HTML, CSS, and JS for readability purposes
2. Moved inline CSS and JS to separate files, also for readability
3. Restored search box and "Google Search" button, as the original 2010 Pac-Man doodle had

## Copyrights

*PAC-MAN™ & ©1980 NAMCO BANDAI Games Inc.*

*©2010 Google, LLC*
