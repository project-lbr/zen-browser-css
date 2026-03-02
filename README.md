# Zen Browser Custom CSS & Stylus Themes

A personal collection of visual enhancements for Zen Browser (Firefox-based). This repository contains UI modifications (Chrome) and site-specific styles managed via Stylus.

## Repository Structure

* userChrome.css - Enhancements for the browser interface (toolbars, tabs, menus).
* userContent.css - Global modifications for web content.
* /stylus - Exported .user.css files for the Stylus extension.
* /assets - Icons or images used in the themes.

## Installation (EndeavourOS / Linux)

### 1. Zen Browser UI (userChrome.css)
To activate these styles, you need to link the file from this repository to your Zen Browser profile directory.

1. Open Zen Browser and go to about:support.
2. Locate the Profile Directory entry and copy the path.
3. In your terminal, create a symbolic link (replace [YOUR_PROFILE] with your actual profile folder name):
