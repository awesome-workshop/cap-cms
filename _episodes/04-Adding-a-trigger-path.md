---
title: "Adding a trigger path to the CAP entry"
teaching: 10
exercises: 10
objectives:
  - See how to include some trigger to the CAP entry 
    
questions:
  - How to preserve the trigger information?
hidden: false
keypoints:
  - Triggers can be easily included in your CAP entry thanks to the dataset name suggestion system
  - The trigger paths are checked against a list containing the whole set of triggers by year of data taking
  - CAP entries can be searched (among many other options) by trigger and dataset path

---
## What is a trigger?

When CMS is performing at its peak, about one billion proton-proton interactions will take place every second inside the detector. There is no way that data from all these events could be read out, and even if they could, most would be less likely to reveal new phenomena; they might be low-energy glancing collisions for instance, rather than energetic, head-on interactions.

We therefore need a 'trigger' that can select the potentially interesting events, such as those which will produce the Higgs particle, and reduce the rate to just a few hundred “events” per second, which can be read out and stored on computer disk for subsequent analysis.

## Including a trigger path to the CAP entry

Now that we have created our first CAP entry and included some input datasets, let's also add some trigger paths. Let's see how to include this information!

1. In the menu on your left, click again on Input Data
2. Click on Primary Datasets and then on the dataset sample you added in the last lesson. 
3. Click on the + sign in the trigger section.  
4. You can now add a trigger path. Start typing to see how the autocomplete feature does its job! 

~~~
Add the following trigger path: FIXME
~~~
{: .language-yaml}



## Searching an entry by trigger

Now that you have included the trigger information, you can test the search functionalities!

Go to the `Search` area on the top of the CAP portal, and search for all the drafts containing the trigger path you just included! Among all the entries, you will see the analysis your have just created! 

~~~
Search: FIXME, hints on how to search
~~~
{: .language-yaml}


## Searching an entry by dataset and trigger
Try now to narrow down your search by looking for entries having the primary dataset AND the trigger path you have included

~~~
Search: FIXME, hints on how to search with "and"
~~~
{: .language-yaml}
