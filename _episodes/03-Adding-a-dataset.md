---
title: "Adding a dataset to the CAP entry"
teaching: 10
exercises: 10
objectives:
  - See how to include some dataset to the CAP entry 
  - Export the dataset information as a latex table
  
questions:
  - How to preserve the dataset information?
hidden: false
keypoints:
  - Datasets can be easily included in your CAP entry thanks to the dataset name suggestion system
  - The dataset names are checked against the Data Aggregation System (DAS)

---


## Including a dataset to the CAP entry

Now that we have created our first CAP entry in the previous lesson, let's add some useful information to it. One of the first things someone accessing your preserved analysis will want to know, is which dataset you used when perfoming your analysis.
For this, we are going to learn how to append this information!

So we will now need to perfom some actions:

1. In the menu on your left, click on Input Data
2. Click on Primary Datasets to include some real data dataset. Start typing the name of the dataset to see how it autocompletes to avoid typos.
~~~
Add the following dataset: FIXME
~~~
{: .language-yaml}

3. Click on Monte Carlo Signal Datasets to include some dataset simulation on the signal model your are using in your analysis. Start typing the name of the dataset to see how it autocompletes to avoid typos.
~~~
Add the following dataset: FIXME
~~~
{: .language-yaml}

4. Click on Monte Carlo Background Datasts to include some dataset simulation on the background you are using in your analysis. Start typing the name of the dataset to see how it autocompletes to avoid typos.
~~~
Add the following dataset: FIXME
~~~
{: .language-yaml}






## Exporting the datasets as a Latex file

Now that you have your dataset paths stored, you may need to export them to include them in a paper or just to share it with some collaborators. For doing so, the CAP system has a Latex exporter that will generate an exportable LaTeX dataset table with headers, etc…

Try it out yourself!

FIXME: Instruction on how to export the dataset files as a latex table
