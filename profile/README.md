# Welcome to Spacetop Project 🪐🧠🧑‍🔬
Explore our multimodal fMRI dataset, comprised of naturalistic data with diverse experimental tasks.
<img src="https://github.com/spatialtopology/.github/blob/main/profile/fig1.png" alt="Example Image" width="800">

## Navigating the Repository
* `task-{repo}`: The six fMRI task codes used on our "Stimulus PC".
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



## Data management link
> @tor requested a list of links and paths for data management purposes. This is an extensive list and will continue to grow. Therefore, the following links will be maintained in a google docs, in conjunction to this slack message.
> 
> For external users: checkout details from headers marked with "🚀".
> 
> For internal CANlab spacetop team members, request access if you are part of the active IRB.

### 1. 🚀 Github repositories per task
<details>
<summary style="font-size: 1.7em; font-weight: bold;">Click to expand</summary>
Code
<ul>
  <li>alignvideo: <a href="https://github.com/spatialtopology/alignvideos/releases/tag/v1.0.0-stable">https://github.com/spatialtopology/alignvideos/releases/tag/v1.0.0-stable</a></li>
  <li>faces: <a href="https://github.com/spatialtopology/faces/releases">https://github.com/spatialtopology/faces/releases</a></li>
  <li>fractional: <a href="https://github.com/spatialtopology/fractional_factorials/releases/tag/v.1.0.0">https://github.com/spatialtopology/fractional_factorials/releases/tag/v.1.0.0</a></li>
  <li>narratives: <a href="https://github.com/spatialtopology/Narratives/releases/tag/v.1.0.0">https://github.com/spatialtopology/Narratives/releases/tag/v.1.0.0</a></li>
  <li>shortvideos: <a href="https://github.com/spatialtopology/shortvideos/releases/tag/v1.0.0-stable">https://github.com/spatialtopology/shortvideos/releases/tag/v1.0.0-stable</a></li>
  <li>social: <a href="https://github.com/spatialtopology/social_influence/releases/tag/v1.0.0-stable">https://github.com/spatialtopology/social_influence/releases/tag/v1.0.0-stable</a></li>
  <li>Behavioral: <a href="https://github.com/spatialtopology/d_beh">https://github.com/spatialtopology/d_beh</a></li>
  <li>Demographic data: <a href="https://redcap.dartmouth.edu">https://redcap.dartmouth.edu</a></li>
</ul>
</details>

### 2. Scan notes metadata [ google sheets link ]()

  
### 3. Slack channel
<ul>
<li>#spacetop_recruitment</li>
<li>#spatialtopology (private channel)</li>
<li>#spacetop_qc</li>
</ul>


### 4. Google Drive [ link ](https://drive.google.com/drive/u/0/folders/0AOBMvoHPv0xkUk9PVA)
* updated 05/15/2023 migration from CU
* updated 05/23/2024 migration from individual google drive to Shared Google drive ([link](https://drive.google.com/drive/u/0/folders/0AOBMvoHPv0xkUk9PVA))
* NOTE: only members who are part of the active IRB are granted access

  
### 5. Project management
* Confluence (Deprecated) https://spacetop.atlassian.net/wiki//
* github.io [spatialtopology.github.io](spatialtopology.github.io)


### 6. 🚀 Paths on discovery.dartmouth.edu (dartfs-hpc)
<details>
<summary style="font-size: 1.7em; font-weight: bold;">Click to expand</summary>
<strong>DATA</strong>
  <ul>
    <li>path: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop_data</code></li>
    <li>fMRI data</li>
    <ul>
      <li>DICOM: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/dartmouth/sourcedata</code></li>
      <li>BIDS (source data): <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/dartmouth</code></li>
      <li>Fmriprep-processed: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop_data/derivatives/fmriprep/results/fmriprep</code></li>
    </ul>
    <li>Behavioral</li>
    <ul>
      <li>Raw behavioral data: <a href="https://github.com/spatialtopology/d_beh">https://github.com/spatialtopology/d_beh</a></li>
      <li>Cleaned behavioral data</li>
      <ul>
        <li>Social: <a href="https://github.com/jungheejung/social_influence_analysis/tree/main/data/dartmouth/d01_rawbeh">https://github.com/jungheejung/social_influence_analysis/tree/main/data/dartmouth/d01_rawbeh</a></li>
        <li>spacetop-prep: <a href="https://github.com/spatialtopology/spacetop-prep/tree/master/spacetop_prep/events">https://github.com/spatialtopology/spacetop-prep/tree/master/spacetop_prep/events</a></li>
      </ul>
    </ul>
    <li>Physio data <a href="https://github.com/isabeln23">@isabeln23</a></li>
    <ul>
      <li>Raw Physio: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/data/spacetop/biopac/dartmouth/rawdata</code></li>
    </ul>
    <li>Redcap questionnaire data</li>
    <ul>
      <li>Raw questionnaire (deidentified)</li>
      <li>Cleaned behavioral data [add link]</li>
    </ul>
  </ul>

<strong>PROJECTS</strong>
  <ul>
    <li><code>task-social</code>: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/projects/spacetop_projects_cue</code></li>
   <ul>
     <li>git repo: <a href="https://github.com/jungheejung/cue_expectancy">https://github.com/jungheejung/cue_expectancy</a></li>
   </ul>
    <li><code>task-narratives</code>: <code>/dartfs-hpc/rc/lab/C/CANlab/labdata/projects/spacetop_projects_narratives</code></li>
   <ul>
    <li>git repo: <a href="https://github.com/spatialtopology/projects_narratives">(https://github.com/spatialtopology/projects_narratives</a></li>
   </ul>
  </ul>
  </details

</details>




