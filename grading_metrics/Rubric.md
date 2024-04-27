### Project Summary

For the final project, you will identify an Unsupervised Learning problem to perform EDA and model analysis.  The project has 140 total points. In the instructions is a summary of the criteria you will use to guide your submission and review others’ submissions.   You will submit three deliverables:

* Deliverable 1 — A Jupyter notebook showing an Unsupervised Learning problem description, EDA procedure, analysis (model building and training), result, and discussion/conclusion. 
  * Suppose your work becomes so large that it doesn’t fit into one notebook (or you think it will be less readable by having one large notebook). In that case, you can make several notebooks or scripts in a GitHub repository (as deliverable 3) and submit a report-style notebook or pdf instead. 
  * If your project doesn't fit into Jupyter notebook format, write your approach as a report and submit it in a pdf form.

* Deliverable 2 — A video presentation or demo of your work. The presentation should be a condensed version as if you're doing a short pitch to advertise your work, so please focus on the highlights: 

  * What problem do you solve? 

  * What ML approach do you use, or what methods does your app use? 

  * Show the result or run an app demo. 

  * The minimum video length is 5 min, the maximum length is 15 min. The recommended length is about 10 min. Submit the video in .mp4 format.

* Deliverable 3 — A public project GitHub repository with your work (please also include the GitHub repo URL in your notebook/report and slides). 

#### Data byproduct

If your project creates data and you want to share it, an excellent way to share would be through a Kaggle dataset or similar. Similarly, suppose you want to make your video public. In that case, we recommend uploading it to YouTube or similar and posting the link(s) to your repository or blog instead of a direct upload to GitHub. It is generally a good practice not to upload big files to a Git repository.


### Gather data, determine the method of data collection and provenance of the data (3 points)

In the earliest phase, select a data source and problem. Feel free to share and discuss your idea on the class discussion board.

### Identify an Unsupervised Learning Problem (6 points)

Model building and training may depend on their data type(s) and task type(s). When using multiple models, at least one of them should be an unsupervised approach. 
If you're going to use a Kaggle competition or similar, you must focus more on model building and/or analysis to be a valid project. Replicating what's in the Kaggle kernel or other notebooks available online is not a valid project. It is reasonable to add different approaches and compare them with the Kaggle kernel or other notebooks available online. It is also good to find a research paper, implement an algorithm, and run experiments comparing its performance to different algorithms.  

### Exploratory Data Analysis (EDA) - Inspect, Visualize, and Clean the Data (26 points)

Go through the initial data cleaning and EDA and judge whether you need to collect more or different data. 

#### EDA Procedure Example:

* Describe the factors or components that make up the dataset (The "factors" here are called "features" in the machine learning term. These factors are often columns in the tabulated data). For each factor, use a box-plot, scatter plot, histogram, etc., to describe the data distribution as appropriate.
* Describe correlations between different factors of the dataset and justify your assumption that they are correlated or not correlated. You may use numeric or qualitative/graphical analysis for this step.
* Determine if any data needs to be transformed. For example, if you're planning on using an SVM method for prediction, you may need to normalize or scale the data if there is a considerable difference in the range of the data.
* Using your hypothesis, indicate if it's likely that you should transform data, such as using a log transform or other transformation of the dataset.
* You should determine if your data has outliers or needs to be cleaned in any way. Are there missing data values for specific factors? How will you handle the data cleaning? Will you discard, interpolate or otherwise substitute data values?
* If you believe that specific factors will be more important than others in your analysis, you should mention which and why. You will use this to confirm your intuitions in your final write-up.

### Perform Analysis Using Unsupervised Learning Models of your Choice, Present Discussion, and Conclusions (70 points)

* Model building and training may depend on their data type(s) and task type(s). Depending on your project, you may have one model or more. Generally, it is deemed a higher quality project if you compare multiple models and show your understanding of why specific models work better than the other or what limitations or cautions specific models may have. When using multiple models, at least one of them should be an unsupervised approach. 
  * For machine learning models, another recommendation is to show enough effort on the hyperparameter optimization.
  * If your project involves making a web app (not required), you can include the demo.

### Produce Deliverables: High-Quality, Organized Jupyter Notebook Report, Video presentation, and GitHub Repository (35 points)

These deliverables serve two purposes- grade for this course and your project portfolio that you can show when you apply for jobs.
If you haven’t used GitHub previously, please find a tutorial and get acquainted with it before the project deadline. For the sake of this project, you can use GitHub to showcase your codebase. In the real world, versioning with GitHub is vital for collaboration. Sometimes Jupyter notebooks don’t seem particularly well-suited to versioning with GitHub due to hard-to-read diffs and the like. If you want to use this project as an opportunity to practice versioning with GitHub, consider something like the following: 
https://www.reviewnb.com