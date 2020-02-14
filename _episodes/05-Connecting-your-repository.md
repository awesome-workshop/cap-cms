---
title: "Connecting with your repositories"
teaching: 10
exercises: 10
objectives:
  - Learn how to connect a repository with your analysis
  - How to connect your Github/Gitlab account with CAP

questions:
  - Which are the repositories that can be connected with CAP?
hidden: false
keypoints:
  - Github and Gitlab repositories can be connected with CAP so that code/metadata updates are automatically propagated to the CAP system
  - CAP provides a way to connect with both, public and private repositories
---


## Connecting CAP with git repositories

We have already created a new CAP entry, added some metadata (datasets, triggers information) and uploaded files. Now it's time to tell us, where is the code that you used in your analysis.

It is possible to connect an external account (Github, CERN Gitlab, ORCiD, Zenodo. . . ) with the CAP account, to automate tasks and content submission. One can just add the current repository content from the tarball or create a connection (webhook) so that everytime
something is changed, the CAP is automatically updated. Let's try it out using your CERN Gitlab account!

In general, if you want to connect a public repository, you don't need to connect your account. CERN Gitlab is an exception, as
 even public repositories require a CERN authentication. So let's first connect your account.

1. Open CAP in a new tab
2. Click on your account icon and go to `settings`
3. Choose `+ connect` next to `Gilab CERN` and connect your account

Now let's go back to your open analysis in the previous tab:
1. Go to the menu on your left and click on the connection symbol ![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/signconnect.png?raw=true)
2. Right now you should see no repositories connected with your analysis
3. Click on the button ``Connect your repo``

![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/connected_repo.png?raw=true)

4. A prompt will appear where you will be able to select which external repo you want to link your CAP entry to and if you want to download the current snapshot of the repo or connect it. If you choose the second option, each time something will change in the external repo the information will be propagated to CAP automatically.

![prueba](https://github.com/awesome-workshop/cap-cms/blob/gh-pages/fig/includerepo.png?raw=true)

FIXME updated ui pics

Try the connection with a public repository.

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
