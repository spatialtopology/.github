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
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
