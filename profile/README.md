# Welcome to Spacetop Project 
Explore our multimodal fMRI dataset, blending naturalistic methods with diverse experimental tasks.
<img src="https://github.com/spatialtopology/.github/blob/main/profile/fig1.png" alt="Example Image" width="300">

## Navigating the Repository
* `task-repo`: The six fMRI task codes used on our "Stimulus PC".
  * Explore READMEs for task insights.
  * Utilize our code and cite us!
* `d_beh`: Contains scan-related behavioral data in BIDS format, pushed directly from "Stimulus PC".
* `spacetop-prep`: Preprocessing scripts for behavioral and fMRI data.
   * Installable as a standalone Python package.
   * Contribute your preprocessing or quality control tools via pull requests.
<!--
## Hi there 👋

Welcome to the spacetop project: A multimodal fMRI dataset unifying naturalistic processes with a rich array of experimental tasks.
### How to Navigate the repository structure
* `task-repo`: Each fMRI task is coded as a standalone repository. These code were operated on our "Stimulus PC".
    *  Check out each README to get an idea of the task structure.
    *  Feel free to use our code for future experiments. Remember to cite!
* `d_beh`: This repository hosts the scan-related behavioral data that was directly pushed from our "Stimulus PC". See, when we were collecting data, all of the data was saved in a BIDS format, into this git repo. At the end of scanning a participant, we pushed the data to this repository. In other words, this repository hosts the very raw data of the spacetop dataset.
* `spacetopprep`: Alongside, we host scripts that were part of preprocessing the data, whether it was behavioral processing, redcap organization, or fMRI preprocessing related code.
    * Spacetopprep was designed to be a standalone python package. You should be able to install and import as a library. Check out the README for setup description. 
    * If you happend to develop preprocessing code or quality control tools, please do a pull request so that everyone else can utilize your amazing efforts!


**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->



## Landing page
[ Data Management links ]
@tor
 requested a list of links and paths for data management purposes. This is an extensive list and will continue to grow. Therefore, the following links will be maintained in a google docs, in conjunction to this slack message.
### 1. Github
Code
* alignvideo: https://github.com/spatialtopology/alignvideos/releases/tag/v1.0.0-stable
* faces: https://github.com/spatialtopology/faces/releases
* fractional: https://github.com/spatialtopology/fractional_factorials/releases/tag/v.1.0.0
* narratives: https://github.com/spatialtopology/Narratives/releases/tag/v.1.0.0
* shortvideos: https://github.com/spatialtopology/shortvideos/releases/tag/v1.0.0-stable
* social: https://github.com/spatialtopology/social_influence/releases/tag/v1.0.0-stable
* Behavioral https://github.com/spatialtopology/d_beh
* Demographic data [ Redcap ](https://redcap.dartmouth.edu)

### 2. Scan notes metadata [ google sheets link ]()
  
### 3. Slack channel
private channel
#spacetop_recruitment

### 4. Google Drive [ link ](https://drive.google.com/drive/u/0/folders/0AOBMvoHPv0xkUk9PVA)
* updated 05/15/2023 migration from CU
* updated 05/23/2024 migration from Dartmouth to Shared drive
  
### 5. Project management
* Confluence (Deprecated) https://spacetop.atlassian.net/wiki//
* github.io spatialtopology.github.io

### 6. Server (dartfs-hpc)
#### DATA 
* path: `/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop_data`	
* fMRI data
  * DICOM               `/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/dartmouth/sourcedata`
  * BIDS (source data)   `/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/dartmouth`
  * Fmriprep-processed `/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop_data/derivatives/fmriprep/results/fmriprep`
* Behavioral
  * Raw behavioral data https://github.com/spatialtopology/d_beh
  * Cleaned behavioral data
    * Social: https://github.com/jungheejung/social_influence_analysis/tree/main/data/dartmouth/d01_rawbeh
    * spacetop-prep: [https://github.com/spatialtopology/spacetop-prep/tree/master/spacetop_prep/events](https://github.com/spatialtopology/spacetop-prep/tree/master/spacetop_prep/events)
* Physio data (@Isabel)
  * Raw Physio  `/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/biopac/dartmouth/rawdata`
Cleaned behavioral data [ add link ]
* Redcap questionnaire data 
  * Raw questionnaire (deidentified)
  * Cleaned behavioral data  [ add link ]
 
 
#### PROJECTS 
* path: Tor has suggested that we append the keyword “projects” to the individual folders. e.g. spacetop_projects_align, spacetop_projects_social. I started out with a different scheme - I will update paths to match Tor’s suggestion.

* `task-social`: `/dartfs-hpc/rc/lab/C/CANlab/labdata/projects/spacetop_projects_cue`
  * git repo: [https://github.com/jungheejung/cue_expectancy](https://github.com/jungheejung/cue_expectancy)

* `task-narratives`: `/dartfs-hpc/rc/lab/C/CANlab/labdata/projects/spacetop_projects_narratives`
  * git repo: [https://github.com/spatialtopology/projects_narratives](https://github.com/spatialtopology/projects_narratives)
