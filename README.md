# Curriculum Map

A visualization solution for curriculum and course relationships of Hongkong University of Science and Technology(HKUST)

![](./example.png)

## Installation

[![GitHub release (latest by date and asset)](https://img.shields.io/github/downloads/Zory123/CurriculumMap/v1.0/CurriculumMap-win.zip?color=green)](https://github.com/Zory123/CurriculumMap/releases/tag/v1.0)

[![GitHub release (latest by date and asset)](https://img.shields.io/github/downloads/Zory123/CurriculumMap/v1.0/CurriculumMap-mac.dmg?color=green)](https://github.com/Zory123/CurriculumMap/releases/tag/v1.0)

[![GitHub release (latest by date and asset)](https://img.shields.io/github/downloads/Zory123/CurriculumMap/v1.0/CurriculumMap-linux.zip?color=green)]((https://github.com/Zory123/CurriculumMap/releases/tag/v1.0))

If you think the courses.csv (in get-information folder) is old, you could run `/get-information/get-information.py` to get the newest one. 

p.s. the url is set through `base_url = ['https://prog-crs.ust.hk/ugcourse/2021-22/']`

More information about project source structure -> `/project_doc_H26.pdf`

## Building

Clone this repo

Dependencies:

- Qt Kit v6.1.1 and above (not the creator's version).
- We haven’t use any third-party library except for Qt library, so just compile it would be fine.

After building the project, copy `/get-information/courses.csv` to `/build-<blablabla>/`

## Using CurriculumMap

### Hints

TO ZOOM IN/OUT: Pinch on TrackPad; +/- button; mouse wheel

TO MOVE: Swipe on TrackPad; arrow button ;mouse hold&move

Rightclick course in map to add/delete flags 

Click item above to navigate course(with mouse jumping):

### Flags

Enrolled flag is helpful for simplifing

Reversely search only show courses that need the queried course, so pre-requisite of them may not be shown completely on map(sometimes strange), for accurate imformation, right click and then search for that course.

### Legend

1. for exclusion, if A excludes B, which means you can't take A after B, there will be a red cross near A on line between A and B

2. A rectangle represents courses inside excludes each other

## Contributor:

XU, Han

WANG, Yucheng

WANG, Yicheng

ZHANG, Yujun 





insteresting course code: BIEN3320

![GitHub all releases](https://img.shields.io/github/downloads/Zory123/CurriculumMap/total)
