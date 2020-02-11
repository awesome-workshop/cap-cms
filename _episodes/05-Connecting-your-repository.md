---
title: "Connecting an external repository with CAP"
teaching: 10
exercises: 10
objectives:
  - See how to connect an external repository with CAP 
    
questions:
  - Which are the external repositories that can be connected with CAP?
hidden: false
keypoints:
  - External repositories can be connected with CAP so that code/metadata updates are automatically propagated to the CAP system
  - The external repositories can be either protected or unprotected

---


## Connecting the CAP with your favourite repository

We have already created a new CAP entry and added some dataset paths and triggers. We may want to include now some code from your favourite repository, containing the workflow of your analysis.
It is possible to connect an external account (Github, CERN Gitlab, ORCiD, Zenodo. . . ) with the CAP account, to automate tasks and content submission. One can just add the current repository content from the tarball or create a connection (webhook) so that everytime
something is changed, the CAP is automatically updated. 

Let's try it out using your CERN Gitlab account! (FIXME: or you prefer to use Github?)

For this you have to follow these steps:

1. Go to the menu on your left and click on the connection symbol ![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/signconnect.png?raw=true)
2. Right now you should see no external repository connected to your CAP entry
3. Click on the button ``Connect your repo``
![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/connected_repo.png?raw=true)
4. A prompt will appear where you will be able to select which external repo you want to link your CAP entry to and if you want to download the current snapshot of the repo or connect it. If you choose the second option, each time something will change in the external repo the information will be propagated to CAP automatically.
![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/includerepo.png?raw=true)

Now try it yourself!

Try the connection with an unprotected repository. 

~~~
For this, provide #FIXME
~~~
{: .language-yaml}

Try now the connection with a protected repository.

~~~
For this, provide #FIXME
~~~
{: .language-yaml}


 After connecting the external repository, edit your code to see that after you pushed your changes, a new snapshot is created in CAP.
 
 ~~~
For this, provide #FIXME
~~~
{: .language-yaml}





