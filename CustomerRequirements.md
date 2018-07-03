# Requirements Document

This document shows the requirements in form of epics and more detailed user stories.  
It is subject to change every iteration and features a changelog.

latest version **0.1**

## Table of Contents

   * [Requirements Document](#requirements-document)
      * [Changelog](#changelog)
      * [Epics and User Stories](#epics-and-user-stories)
         * [Theme: Input Source](#theme-input-source)
         * [Theme: Satellite Configuration](#theme-satellite-configuration)
         * [Theme: Data Visualization](#theme-data-visualization)
         * [Theme: Digital Signal Processing (DSP)](#theme-digital-signal-processing-dsp)
         * [Theme: Data Persistency](#theme-data-persistency)
         * [Theme: Data Publication](#theme-data-publication)

## Changelog

* 0.1 - first draft of requirements

---
## Epics and User Stories
### Theme: Input Source

| # | Epic |
|:--- |:--- |
| 1.1 | As a **radio amateur** I can **change the Input Source** to work with **flexible hardware equipment** |
| 1.2 | As a **teacher** I  can **load a sound clip** to **reenter data at a later time** |

### Theme: Satellite Configuration

| # | Epic |
|:--- |:--- |
| 2.1 | As a **space engineer** I can **add/remove satellites without reinstalling** to **simplify satellite management** |
| 2.2 | As a **space engineer** I can **change a satellite's settings without leaving/restarting the tool** to **increase efficiency** |

### Theme: Data Visualization

| # | Epic |
|:--- |:--- |
| 3.1 | As a **teacher** I can **select visualized data** to **filter unneeded views** |
| 3.2 | As a **space engineer** I can **filter for date/time** to **view older data** |
| 3.3 | As a **teacher** I can **arrange the views** to **group them logically** |
| 3.4 | As a **space engineer** I can **add new views** to **keep visualization on date** |
| 3.5 | As a **radio amateur** I can **see the quality of signal** to **adjust receiver hardware** |
| 3.6 | As a **space engineer** I can **see which satellite is viewed** to **avoid misinformation** |
| 3.7 | As a **space engineer** I can **select which satellite the data is shown from** to **be able to track the right satellite** |

### Theme: Digital Signal Processing (DSP)

| # | Epic |
|:--- |:--- |
| 4.1 | As a **radio amateur** I can **track multiple satellites in one tool** to **reduce tool overhead** |
| 4.2 | As a **space engineer** I can **add new decoder** to **increase coverage of satellites** |
| 4.3 | As a **radio amateur** I can **track satellites synchronously** to **reduce waiting/blocking time** |

### Theme: Data Persistency

| # | Epic |
|:--- |:--- |
| 5.1 | As a **radio amateur** I can **store my data locally** so that I can **view the data later** |
| 5.2 | As a **space engineer** the data is **stored with integrity** so I **don't loose important data** |
| 5.3 | s a **radio amateur** I can **save data remotely** so that **others can view this data** |

### Theme: Data Publication

| # | Epic |
|:--- |:--- |
| 6.1 | As a **radio amateur** I can **export my data** so that I can **distribute them** |
| 6.2 | As a **space engineer** I can **print the data** so that I can **publish them in other media** |