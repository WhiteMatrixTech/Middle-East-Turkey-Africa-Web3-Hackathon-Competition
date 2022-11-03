
## Hydra Developer BootCamp PR Submission Guide ##

 **PR Submission Deadline: May 15, 2022, 23:59 PST PST**

**1. [Create a Github account.](https://github.com/)**

**2. [Download Git BASH Client](https://gitforwindows.org/) and complete Github configuration in local environment.**

   Open Gitbash Terminal.

   Enter the following command line in the terminal (name and email are filled in according to the github account).

    git config --global user.name xxx
       
    git config --global user.email xxxxxx@xxx.com

 ![](https://d11chu8p22a2zy.cloudfront.net/Gitconfig.png)

   Create a local SSH —— Secure Shell.

    ssh-keygen -t rsa -C "xxxxxx@xxx.com" 
 ![](https://d11chu8p22a2zy.cloudfront.net/Gitlocalssh.png)

   Configure SSH into Github Settings.

> **Linux**: /home/username/.ssh
> 
> **Mac**:  /Users/username/.ssh
> 
> **Windows**: C:\Documents and Settings\Administrator\.ssh **OR** C:\Users\username\\.ssh


 ![](https://d11chu8p22a2zy.cloudfront.net/SSH_File.png)


Open the file **id_rsa.pub** with Notepad and copy the content.
> ssh-rsa XXXXX....XXX
>
>  xxxxxx@xxx.com

   Go to github and login your account.

   Find "SSH and GPG keys" in personal account settings.

   Click "New SSH key" and paste the content from the file "id_rsa.pub". 

   Then, click "Add SSH key". There is no any specific requirement for title.

   ![](https://d11chu8p22a2zy.cloudfront.net/GithubSettings.png)

   ![](https://d11chu8p22a2zy.cloudfront.net/SSH+and+GPG+keys.png)

Validate if the comfiguration is successful.

    ssh -T git@github.com

![](https://d11chu8p22a2zy.cloudfront.net/SSH_Validation.png)

**3.Fork the open-source codes into the personal remote repository.**

Repository URL: https://github.com/WhiteMatrixTech/Hydra-Developer-BootCamp

  ![](	
https://d3f4u6mt7x0ttm.cloudfront.net/8208.png)

**4.Clone personal github repository into local environment via SSH.**

  ![](https://d11chu8p22a2zy.cloudfront.net/Code_Clone_SSH.png)

    git clone git@github.com:XXXxx

  Enter the destination folder.

``` 
cd xxxxxxxxxxx
```

  The downloaded folder in Windows can be checked in the route below.

> C:\Users\user name\Hydra-Developer-Bootcamp\

**5.Create a folder named by your team name under projects. Generate a README.md file which contains the information of your team, your project and the link to your github repository.**

	Team Name:
	Job Allocation:
	Project Intro:
	Video Link:
	Repository Addr:

Use the command line "git push" to upload the project folder to github.

    git add .
    git commit -m 'submit'
    git push 

![](https://d11chu8p22a2zy.cloudfront.net/GitPush.png)

  Then, the README.md file can be seen on the github repository.

![](https://d11chu8p22a2zy.cloudfront.net/Github_README.png)

**6.Click "New pull request" and create a PR(Pull Request).**

![](https://d3f4u6mt7x0ttm.cloudfront.net/8213.png)

**7.Convert PR into Draft where all the match-related resources should be placed.**

![](https://d11chu8p22a2zy.cloudfront.net/ConvertPR2Draft.png)

![](	
https://d3f4u6mt7x0ttm.cloudfront.net/8237.png)

**8.Accomplish the project and submit.**

**9.Convert the status of PR into "Ready For Review" as long as the submission has been done. Bootcamp staff will merge all the PRs.**
![](https://d11chu8p22a2zy.cloudfront.net/Ready4View.png)
