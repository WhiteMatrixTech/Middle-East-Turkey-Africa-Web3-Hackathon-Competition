# Middle East Turkey Africa Web3 Hackathon Competition PR Submission Guide

!!!  **PR Submission Deadline: 2022 Dec 15th 23:59 GMT+4**

**1. [Create a Github account.](https://github.com/)**

**2. [Download Git BASH Client](https://gitforwindows.org/) and complete Github configuration in local environment.**

   Open Gitbash Terminal.

   Enter the following command line in the terminal (name and email are filled in according to the github account).

    git config --global user.name xxx
       
    git config --global user.email xxxxxx@xxx.com

![Gitconfig.png (490×107) (d11chu8p22a2zy.cloudfront.net)](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/Gitconfig.png)

   Create a local SSH —— Secure Shell.

    ssh-keygen -t ed25519 -C "xxxxxx@xxx.com"
![image-20221103145616848](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103145616848.png)

   Configure SSH into Github Settings.

> **Linux**: /home/username/.ssh
>
> **Mac**:  /Users/username/.ssh
>
> **Windows**: C:\Documents and Settings\Administrator\.ssh **OR** C:\Users\username\\.ssh


![image-20221103145835072](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103145835072.png)


Open the file **id_rsa.pub** with Notepad and copy the content.
> ssh-ed25519 XXXXX....XXX
>
> xxxxxx@xxx.com

   Go to github and login your account.

   Find "SSH and GPG keys" in personal account settings.

![image-20221103164814883](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103164814883.png)

   Click "New SSH key" and paste the content from the file "id_rsa.pub". 

   Then, click "Add SSH key". There is no any specific requirement for title.![](https://d11chu8p22a2zy.cloudfront.net/SSH+and+GPG+keys.png)

Validate if the comfiguration is successful.

    ssh -T git@github.com

**Remember to type YES, not the Enter key.**

![image-20221103153636292](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103153636292.png)

**3.Fork the open-source codes into the personal remote repository.**

Repository URL: [WhiteMatrixTech/Middle-East-Turkey-Africa-Web3-Hackathon-Competition (github.com)](https://github.com/WhiteMatrixTech/Middle-East-Turkey-Africa-Web3-Hackathon-Competition)

![image-20221103155309653](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103155309653.png)

**4.Clone personal github repository into local environment via SSH.**

![image-20221103155527274](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103155527274.png)

    git clone git@github.com:XXXxx

  Enter the destination folder.

``` 
cd Middle-East-Turkey-Africa-Web3-Hackathon-Competition
```

  The downloaded folder in Windows can be checked in the route below.

> C:\Users\user name\Middle-East-Turkey-Africa-Web3-Hackathon-Competition\

**5.Create a folder named by your team name under "projects". Generate a README.md file which contains the information of your team, your project and the link to your github repository.**

	Team Name:
	
	Job Allocation:
	
	Project Intro:
	
	Video Link:
	
	Repository Addr:
	
	Contract Addr:

Use the command line "git push" to upload the project folder to github.

    git add .
    git commit -m 'submit'
    git push 

![image-20221103165817246](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103165817246.png)

  Then, the README.md file can be seen on the github repository.

![image-20221103170349836](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103170349836.png)

**6.Click "New pull request" and create a PR(Pull Request).**

![image-20221103160133597](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103160133597.png)

![create_pr.png](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/create_pr.png)

**7.Convert PR into Draft where all the match-related resources should be placed.**

![image-20221103160557618](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103160557618.png)

![](	
https://d3f4u6mt7x0ttm.cloudfront.net/8237.png)

**8.Accomplish the project and submit.**

**9.Convert the status of PR into "Ready For Review" as long as the submission has been done. Bootcamp staff will merge all the PRs.**
![image-20221103160640477](https://d11chu8p22a2zy.cloudfront.net/Middle-East-Turkey-Africa-Web3-Hackathon-Competition/image-20221103160640477.png)
