# 🎬 Stremio Flow Launcher Plugin

<img width="3840" height="2160" alt="recommendations" src="https://github.com/user-attachments/assets/68dc7063-2ef2-4cac-a8d9-963d813db234" />

> **A powerful Flow Launcher plugin for searching and launching content directly in Stremio.**
>
> *Seamlessly integrates with Stremio Desktop, Stremio Web, and Stremio Enhanced.*

---

## 📑 Table of Contents
* [✨ Features](#-features)
* [📥 Installation](#-installation)
* [🕹️ Usage](#-usage)
    * [Basic Search](#basic-search)
    * [Smart Filters](#smart-filters)
    * [Quick Actions](#quick-actions)
* [⚙️ Settings](#-settings)
* [📝 Notes](#-notes)
* [❤️ Credits](#-credits)

---

## ✨ Features

* **⚡ Quick Search**
  Search movies and TV shows instantly from Flow Launcher and launch them into Stremio!
* **🖥️ Multiple Clients**
  Switch between Desktop, Web, or Enhanced clients on the fly.
* **🔍 Smart Filters**
  Stack filters to narrow down results:
  * `movie` - Only movies
  * `tv year:2024` - TV shows from 2024
  * `movie genre:action year:2008` - Action movies from 2008
  * `actor:Christian Bale` - Content with specific actors

  <img width="3840" height="2160" alt="filters" src="https://github.com/user-attachments/assets/75e07443-323d-418e-af74-f16c0b7d5dea" />

* **🔥 Recommendations**
  See trending content right in the main menu.
* **🚀 Stremio Enhanced Support**
  Automatically handles single-instance launching without opening Desktop.

---

## 📥 Installation

1.  **Download** the latest release.
2.  **Extract** to:
    ```path
    %APPDATA%\FlowLauncher\Plugins\Stremio
    ```
3.  **Restart** Flow Launcher.
4.  Type `st` to start using it.

---

## 🕹️ Usage

### Basic Search
* `st game of thrones` - Search TV shows

### Filtered Search
You can stack multiple filters for precise results:

| Filter | Description |
| :--- | :--- |
| `st movie` | Only movies |
| `st tv year:2024` | 2024 TV shows |
| `st genre:horror` | Horror content |
| `st movie actor:Tom Hanks genre:drama` | Stack multiple filters |

### Quick Actions
* `st` - Main menu with recommendations
* `st trending` - Popular content this week
* `st filters` - Browse all available filters
* `st settings` - Configure the plugin

---

## ⚙️ Settings

### Player Selection
Choose between Desktop, Web, or Stremio Enhanced.

<img width="3840" height="2160" alt="stremioenhanced" src="https://github.com/user-attachments/assets/816988c0-2e50-44f1-9751-1d4dbf0dbb4d" />

### Toggle Features
Enable/disable recommendations, trending, or filters menus to suit your preference.

### Stremio Enhanced Configuration
Auto-restart functionality to prevent Desktop app conflicts.

<img width="3840" height="2160" alt="stremioenhancedsettings" src="https://github.com/user-attachments/assets/72c0e529-1658-42d2-9a86-7c08cea9b89f" />
<br>
<span style="color:red">**This option must be enabled if using Stremio Enhanced.**</span>

---

## 📝 Notes

* Uses **TMDB** for search results.
* Maintains TMDB's relevance scoring for accurate search results.
* Filters use popularity sorting for best content discovery.
* Enhanced mode automatically closes/reopens to avoid multi-instance issues.

---

## ❤️ Credits

Built for the **Stremio** and **Flow Launcher** communities.
*TMDB data provided by The Movie Database API.*
