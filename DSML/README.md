Last login: Mon Dec 10 10:05:59 on ttys000
Imanis-MBP:~ blackpanther$ git clone https://github.com/inp2/education
Cloning into 'education'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Imanis-MBP:~ blackpanther$ ls
Applications			Nextcloud
Desktop				Pictures
Documents			UIUC-iSchool-DataViz
Downloads			Virtual Machines.localized
Library				education
Movies				hello-world
Music				priv-analysis
Imanis-MBP:~ blackpanther$ cd education/
Imanis-MBP:education blackpanther$ ls
README.md
Imanis-MBP:education blackpanther$ mkdir DataViz
Imanis-MBP:education blackpanther$ ls
DataViz		README.md
Imanis-MBP:education blackpanther$ cd ..
Imanis-MBP:~ blackpanther$ ls
Applications			Nextcloud
Desktop				Pictures
Documents			UIUC-iSchool-DataViz
Downloads			Virtual Machines.localized
Library				education
Movies				hello-world
Music				priv-analysis
Imanis-MBP:~ blackpanther$ cd UIUC-iSchool-DataViz/
Imanis-MBP:UIUC-iSchool-DataViz blackpanther$ ls
README.md	_config.yml	fall2018
Imanis-MBP:UIUC-iSchool-DataViz blackpanther$ mv fall2018/ ../education/DataViz/
Imanis-MBP:UIUC-iSchool-DataViz blackpanther$ ls
README.md	_config.yml
Imanis-MBP:UIUC-iSchool-DataViz blackpanther$ cd ..
Imanis-MBP:~ blackpanther$ ls
Applications			Nextcloud
Desktop				Pictures
Documents			UIUC-iSchool-DataViz
Downloads			Virtual Machines.localized
Library				education
Movies				hello-world
Music				priv-analysis
Imanis-MBP:~ blackpanther$ cd education/
Imanis-MBP:education blackpanther$ ls
DataViz		README.md
Imanis-MBP:education blackpanther$ git add -A .
Imanis-MBP:education blackpanther$ git commit -m "placing old educational material"
[master 3585887] placing old educational material
 Committer: Imani Palmer <blackpanther@Imanis-MBP.reisner.co>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 116 files changed, 627026 insertions(+)
 create mode 100644 DataViz/fall2018/.gitignore
 create mode 100644 DataViz/fall2018/.ipynb_checkpoints/lecture_week05_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/Final Exam/FinalProject.md
 create mode 100644 DataViz/fall2018/Final Exam/FinalProjectGroupSchedule.md
 create mode 100644 DataViz/fall2018/Final Exam/FinalProjectPresentation.md
 create mode 100644 DataViz/fall2018/Final Exam/ProjectProposal.md
 create mode 100644 DataViz/fall2018/LICENSE
 create mode 100644 DataViz/fall2018/README.md
 create mode 100644 DataViz/fall2018/syllabus.md
 create mode 100644 DataViz/fall2018/week01/.ipynb_checkpoints/lecture_week01_git_02-Copy1-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week01/README.md
 create mode 100644 DataViz/fall2018/week01/data/hubble_data.csv
 create mode 100644 DataViz/fall2018/week01/images/anscombe.png
 create mode 100644 DataViz/fall2018/week01/images/bubble chart.png
 create mode 100644 DataViz/fall2018/week01/images/create-new-repo.png
 create mode 100644 DataViz/fall2018/week01/images/histogram.svg
 create mode 100644 DataViz/fall2018/week01/images/london.jpg
 create mode 100644 DataViz/fall2018/week01/images/pie chart.svg
 create mode 100644 DataViz/fall2018/week01/images/scatter plot.png
 create mode 100644 DataViz/fall2018/week01/lecture_week01_git_02.ipynb
 create mode 100644 DataViz/fall2018/week01/lecture_week01_intro_to_python_03.ipynb
 create mode 100644 DataViz/fall2018/week01/lecture_week01_overview_01.ipynb
 create mode 100644 DataViz/fall2018/week01/readme
 create mode 100644 DataViz/fall2018/week01/videos/County_Diurnal.mp4
 create mode 100644 DataViz/fall2018/week01/videos/internet.gif
 create mode 100644 DataViz/fall2018/week02/README.md
 create mode 100644 DataViz/fall2018/week02/data/iris.csv
 create mode 100644 DataViz/fall2018/week02/data/la-county-restaurant-inspections.csv
 create mode 100644 DataViz/fall2018/week02/data/mlb_salaries_2014.csv
 create mode 100644 DataViz/fall2018/week02/lecture_week02.ipynb
 create mode 100644 DataViz/fall2018/week03/README.md
 create mode 100644 DataViz/fall2018/week03/data/Building_Inventory.csv
 create mode 100644 DataViz/fall2018/week03/data/gun-violence.csv
 create mode 100644 DataViz/fall2018/week03/lecutre_week03.ipynb
 create mode 100644 DataViz/fall2018/week04/.DS_Store
 create mode 100644 DataViz/fall2018/week04/README.md
 create mode 100644 DataViz/fall2018/week04/data/.DS_Store
 create mode 100644 DataViz/fall2018/week04/data/Building_Inventory.csv
 create mode 100644 DataViz/fall2018/week04/data/us-marriages-divorces-1867-2014.csv
 create mode 100644 DataViz/fall2018/week04/examples_subsampling.ipynb
 create mode 100644 DataViz/fall2018/week04/images/.DS_Store
 create mode 100644 DataViz/fall2018/week04/images/binning.png
 create mode 100644 DataViz/fall2018/week04/images/palette.png
 create mode 100644 DataViz/fall2018/week04/images/sampling_examples.png
 create mode 100644 DataViz/fall2018/week04/images/sampling_examples1.png
 create mode 100644 DataViz/fall2018/week04/images/sampling_examples2.png
 create mode 100644 DataViz/fall2018/week04/images/splitting1.png
 create mode 100644 DataViz/fall2018/week04/images/splitting2.png
 create mode 100644 DataViz/fall2018/week04/lecture_week04.ipynb
 create mode 100644 DataViz/fall2018/week04/lecture_week04.pdf
 create mode 100644 DataViz/fall2018/week05/.ipynb_checkpoints/lecture_week05_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week05/.ipynb_checkpoints/lecture_week05_02-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week05/README.md
 create mode 100644 DataViz/fall2018/week05/data/a1-burtin.csv
 create mode 100644 DataViz/fall2018/week05/data/lin2012xyz10e_fine_7sf.csv
 create mode 100644 DataViz/fall2018/week05/data/lin2012xyz2e_fine_7sf.csv
 create mode 100644 DataViz/fall2018/week05/data/sbrgb10w.csv
 create mode 100644 DataViz/fall2018/week05/data/sbrgb2.csv
 create mode 100644 DataViz/fall2018/week05/images/Chart Suggestions.png
 create mode 100644 DataViz/fall2018/week05/images/relationship.png
 create mode 100644 DataViz/fall2018/week05/lecture_week05_01.ipynb
 create mode 100644 DataViz/fall2018/week05/lecture_week05_02.ipynb
 create mode 100644 DataViz/fall2018/week06/.ipynb_checkpoints/lecture_week06-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week06/README.md
 create mode 100644 DataViz/fall2018/week06/data/cereal.csv
 create mode 100644 DataViz/fall2018/week06/images/.DS_Store
 create mode 100644 DataViz/fall2018/week06/lecture_week06.ipynb
 create mode 100644 DataViz/fall2018/week07/.ipynb_checkpoints/lecture_week07_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week07/.ipynb_checkpoints/lecture_week07_02-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week07/.ipynb_checkpoints/lecture_week07_03-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week07/README.md
 create mode 100644 DataViz/fall2018/week07/circos_plot.png
 create mode 100644 DataViz/fall2018/week07/data/Divvy_Stations_2013.csv
 create mode 100644 DataViz/fall2018/week07/data/Divvy_Trips_2013.csv
 create mode 100644 DataViz/fall2018/week07/data/asoiaf-book1-edges.csv
 create mode 100644 DataViz/fall2018/week07/data/asoiaf-book2-edges.csv
 create mode 100644 DataViz/fall2018/week07/data/asoiaf-book3-edges.csv
 create mode 100644 DataViz/fall2018/week07/data/asoiaf-book4-edges.csv
 create mode 100644 DataViz/fall2018/week07/data/asoiaf-book5-edges.csv
 create mode 100644 DataViz/fall2018/week07/data/member-edges.csv
 create mode 100644 DataViz/fall2018/week07/images/divvy.png
 create mode 100644 DataViz/fall2018/week07/lecture_week07_01.ipynb
 create mode 100644 DataViz/fall2018/week07/lecture_week07_02.ipynb
 create mode 100644 DataViz/fall2018/week07/lecture_week07_03.ipynb
 create mode 100644 DataViz/fall2018/week08/.ipynb_checkpoints/lecture_week08_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week08/.ipynb_checkpoints/lecture_week08_02-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week08/.ipynb_checkpoints/lecture_week08_03-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week08/README.md
 create mode 100644 DataViz/fall2018/week08/data/Building_Inventory.csv
 create mode 100644 DataViz/fall2018/week08/data/flights.csv
 create mode 100644 DataViz/fall2018/week08/data/flights_map.csv
 create mode 100644 DataViz/fall2018/week08/lecture_week08_01.ipynb
 create mode 100644 DataViz/fall2018/week08/lecture_week08_02.ipynb
 create mode 100644 DataViz/fall2018/week08/lecture_week08_03.ipynb
 create mode 100644 DataViz/fall2018/week09/.ipynb_checkpoints/lecture_week09-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week09/README.md
 create mode 100644 DataViz/fall2018/week09/data/dc-wikia-data.csv
 create mode 100644 DataViz/fall2018/week09/data/marvel-wikia-data.csv
 create mode 100644 DataViz/fall2018/week09/lecture_week09.ipynb
 create mode 100644 DataViz/fall2018/week10/README.md
 create mode 100644 DataViz/fall2018/week11/.ipynb_checkpoints/lecture_week11_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week11/.ipynb_checkpoints/lecture_week11_02-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week11/README.md
 create mode 100644 DataViz/fall2018/week11/data/test.csv
 create mode 100644 DataViz/fall2018/week11/data/train.csv
 create mode 100644 DataViz/fall2018/week11/images/eda_diagram.png
 create mode 100644 DataViz/fall2018/week11/lecture_week11_01.ipynb
 create mode 100644 DataViz/fall2018/week11/lecture_week11_02.ipynb
 create mode 100644 DataViz/fall2018/week12/.ipynb_checkpoints/lecture_week12_01-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week12/.ipynb_checkpoints/visualize-population-projections-checkpoint.ipynb
 create mode 100644 DataViz/fall2018/week12/README.md
 create mode 100644 DataViz/fall2018/week12/data/auto96.csv
 create mode 100644 DataViz/fall2018/week12/lecture_week12_01.ipynb
 create mode 100644 DataViz/fall2018/week12/pivottablejs.html
 create mode 100644 DataViz/fall2018/week14/README.md
 create mode 100644 DataViz/fall2018/week15/README.md
Imanis-MBP:education blackpanther$ git push -u origin master
Counting objects: 151, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (140/140), done.
Writing objects: 100% (151/151), 40.33 MiB | 1.25 MiB/s, done.
Total 151 (delta 6), reused 0 (delta 0)
remote: Resolving deltas: 100% (6/6), done.
To https://github.com/inp2/education
   eef4708..3585887  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
Imanis-MBP:education blackpanther$ ls
DataViz		README.md
Imanis-MBP:education blackpanther$ mkdir DS&ML
[1] 5542
-bash: ML: command not found
[1]+  Done                    mkdir DS
Imanis-MBP:education blackpanther$ mkdir DSML
Imanis-MBP:education blackpanther$ ls
DS		DSML		DataViz		README.md
Imanis-MBP:education blackpanther$ rm DS
rm: DS: is a directory
Imanis-MBP:education blackpanther$ ls
DS		DSML		DataViz		README.md
Imanis-MBP:education blackpanther$ rm -rf DS
Imanis-MBP:education blackpanther$ s
-bash: s: command not found
Imanis-MBP:education blackpanther$ ls
DSML		DataViz		README.md
Imanis-MBP:education blackpanther$ cd DSML
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ cd DSML
-bash: cd: DSML: No such file or directory
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ ls
Imanis-MBP:DSML blackpanther$ cd 
Imanis-MBP:~ blackpanther$ ls
Applications			Nextcloud
Desktop				Pictures
Documents			UIUC-iSchool-DataViz
Downloads			Virtual Machines.localized
Library				education
Movies				hello-world
Music				priv-analysis
Imanis-MBP:~ blackpanther$ cd Nextcloud/
Imanis-MBP:Nextcloud blackpanther$ ls
Andrew			Passwords		TSD
Cybersecurity Ethics	Projects		Transcripts
Ethics			Proposals		books
ITI			Resumes			conferences
Jobs			Steve Resumes		todo.txt
Imanis-MBP:Nextcloud blackpanther$ cd conferences/
Imanis-MBP:conferences blackpanther$ ls
InfrGuard (2018)	InsomniHack19		NolaCon19
Imanis-MBP:conferences blackpanther$ cd NolaCon19/
Imanis-MBP:NolaCon19 blackpanther$ ls
NolaCon_Training_Outline.text	NolaCon_Training_Overview.text
Imanis-MBP:NolaCon19 blackpanther$ cat NolaCon_Training_O
cat: NolaCon_Training_O: No such file or directory
Imanis-MBP:NolaCon19 blackpanther$ cat NolaCon_Training_Outline.text 
Class Materials Laptop with Virtualbox (or VMWare) installed, 6GB of
RAM and 10GB of storage Instructors will provide a preconfigured
virtual machine (VM) containing all the software needed for the
class. The VM will also contain: Course slides, notebooks, reference
sheets and handouts, documentation Skeleton code examples for in-class
exercises

Module 1: Data

In this section, you’ll learn how to quickly and efficiently ingest a
variety of data types and prepare them for analysis. You’ll also learn
the concepts behind vectorized computing.

Introduction: Data, and Data Preparation with Pandas What is data?
Working Categorical and Continuous Data What is Pandas and using the
Pandas library to quickly manipulate tabular data The Series,
DataFrame, and Panel objects The Pandas ecosystem: Scikit-learn,
Seaborn, Bokeh Creating a DataFrame Reading logfiles, APIs and other
sources Manipulating data in data frames Applying functions to data
frames Aggregating data in data frames

Module 2: Data Exploration

You’ll learn the concepts and techniques behind exploratory data
analysis as well as practical data visualization techniques.

Statistical Summaries 5-Number summaries Normalizing data
Understanding Distributions Correlations Confidence Intervals and
P-Values

Concepts of Data Visualization (Comparison, Composition, Distribution,
Relationship) Creating effective visualizations Choosing the correct
visualization Using visualization to explore data Practical Data
Visualization Using Matplotlib to create basic charts Overview of
advanced charts with Seaborn

Time-Series Analysis Stochastic Network Traffic Modeling Beaconing
Detection with Discrete Fourier Transofmr

Graph Theory Graph Perturbation and Noise Analaysis PageRank and
targeted invesitgations

Reasoning Logic Models Probabilistic Graphical Models

Module 3 – Learn From It

Introducing the machine learning process. We will cover model
selection, feature engineering, and model evaluation.

Machine Learning Concepts

Machine learning process Machine learning problem types Supervised vs
Unsupervised machine learning Unsupervised Machine Learning in
Practice

Feature Engineering

Unsupervised Machine Learning Dimensionality Reduction PCA Cluster
Analysis Feature Extraction

Distance measures Nearest Neighbors K-Means Supervised Machine
Learning: Classification

Feature Selection Modeling with Decision Trees and Support Vector
Machines Model evaluation Case Study: Classifier to identify SQL
Injection Project: DGA Classifier~


Module 4 - Competition

Students will be challenged to compete and complete in a Cybersecurity Kaggle Competition
Imanis-MBP:NolaCon19 blackpanther$ 
