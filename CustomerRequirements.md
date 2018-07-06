# Requirements Document

This document shows the requirements in form of epics and more detailed user stories.  
It is subject to change every iteration and features a changelog.

current version **0.3**

## Table of Contents

   * [Requirements Document](#requirements-document)
      * [Changelog](#changelog)
      * [Personas](#personas)
      * [Epics and User Stories](#epics-and-user-stories)
         * [Theme: Input Source](#theme-input-source)
         * [Theme: Satellite Configuration](#theme-satellite-configuration)
         * [Theme: Data Visualization](#theme-data-visualization)
         * [Theme: Digital Signal Processing (DSP)](#theme-digital-signal-processing-dsp)
         * [Theme: Data Persistency](#theme-data-persistency)
         * [Theme: Data Publication](#theme-data-publication)
      * [Priorization Matrix](#priorization-matrix)

## Changelog

* 0.1 - first draft of requirements
* 0.2 - change epic 3.1 and add epic 3.8
* 0.3 - first estimation added, epic 4.4 added

---

## Personas

| Nr | Titel | Description |
| --- | --- | --- |
| 1 | Radio Amateur | He receives signales from satellites and uses the tool to decode the signal and see the satellites content |
| 2 | Teacher | A teacher wants to bring the STEM fields closer to his students |
| 3 | Space Engineer | He uses the tool to follow his satellites, add new satellites and analyze the provided data |

## Epics and User Stories
### Theme: Input Source

| # | Epic | Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 1.1 | As a **radio amateur** I can **change the Input Source** to work with **flexible hardware equipment** |13 | -|
| 1.2 | As a **teacher** I  can **load a sound clip** to **reenter data at a later time** |20 | -|

### Theme: Satellite Configuration

| # | Epic |Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 2.1 | As a **space engineer** I can **add/remove satellites without reinstalling** to **simplify satellite management** | 8 | -|
| 2.2 | As a **space engineer** I can **change a satellite's settings without leaving/restarting the tool** to **increase efficiency** | 8 | -|

### Theme: Data Visualization

| # | Epic | Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 3.1 | As a **teacher** I can **select data view** to **filter unneeded views** | 5 | -|
| 3.2 | As a **space engineer** I can **filter for date/time** to **view older data** | 3 | -|
| 3.3 | As a **teacher** I can **arrange the views** to **group them logically** | 8 | -|
| 3.4 | As a **space engineer** I can **add new views for selection** to **keep visualization on date** | 40 | -|
| 3.5 | As a **radio amateur** I can **see the quality of signal** to **adjust receiver hardware** | 20 | -|
| 3.6 | As a **space engineer** I can **see which satellite is viewed** to **avoid misinformation** | 3 | -|
| 3.7 | As a **space engineer** I can **select which satellite the data is shown from** to **be able to track the right satellite** | 5 | -|
| 3.8 | As a **teacher** I can **see different views** to **have a variety of analysis** | 13 |- |

### Theme: Digital Signal Processing (DSP)

| # | Epic | Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 4.1 | As a **radio amateur** I can **track multiple satellites in one tool** to **reduce tool overhead** | 20 |- |
| 4.2 | As a **space engineer** I can **add new decoder** to **increase coverage of satellites** | 40 |- |
| 4.3 | As a **radio amateur** I can **track satellites synchronously** to **reduce waiting/blocking time** | 40 |- |
| 4.4 | As a **radio amateur** I can **feed a signal** to **receive a satellites data in decoded form** | 20 | -|

### Theme: Data Persistency

| # | Epic | Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 5.1 | As a **radio amateur** I can **store my data locally** so that I can **view the data later** | 40 |- |
| 5.2 | As a **space engineer** the data is **stored with integrity** so I **don't loose important data** | 40 |- |
| 5.3 | As a **radio amateur** I can **save data remotely** so that **others can view this data** | 40 |- |

### Theme: Data Publication

| # | Epic | Est. Effort | Est. Value |
|:--- |:--- |:---:|:---:|
| 6.1 | As a **radio amateur** I can **export my data** so that I can **distribute them** | 20 | - |
| 6.2 | As a **radio amateur** I can **import data** from **other radio amateurs** so that I can **view it** | 20 | - |
| 6.3 | As a **space engineer** I can **print the data** so that I can **publish them in other media** | 20 | - |

## Priorization Matrix

Implementation Effort vs Business Value

| | 1 | 2 | 3 | 5 | 8 | 13 | 20 | 40 | 100 | ? |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| **undef.** | - | - | 3.2, 3.6 | 3.1, 3.7 | 2.1, 2.2, 3.3 | 1.1, 3.8 | 1.2, 3.5, 4.1, 4.4, 6.1, 6.2 | 3.4, 4.2, 4.3, 5.1, 5.2, 5.3 | - | - |
| **100** | - | - | - | - | - | - | - | - | - | - |
| **200** | - | - | - | - | - | - | - | - | - | - |
| **300** | - | - | - | - | - | - | - | - | - | - |
| **500** | - | - | - | - | - | - | - | - | - | - |
| **800** | - | - | - | - | - | - | - | - | - | - |
| **1300**| - | - | - | - | - | - | - | - | - | - |
| **2000**| - | - | - | - | - | - | - | - | - | - |
| **4000**| - | - | - | - | - | - | - | - | - | - |
| **10000**| - | - | - | - | - | - | - | - | - | - |
