<img align="left" width="150px" src="assets/media/logo.png">

# BIOVISM (Research Group Website) 

This website uses [Wowchemy's Research Group Template](https://wowchemy.com/tags/research-group/) for [Hugo](https://gohugo.io) which is a static website generator.

## Downloading Website Template (Local)

```
git clone https://github.com/nusretipek/biovism.git
```

## Building Website

### Install Hugo

Follow instructions here for [Windows](https://gohugo.io/getting-started/installing/#chocolatey-windows) <br />
Follow instructions here for [Linux](https://gohugo.io/getting-started/installing/#linux) <br />
Follow instructions here for [MacOS](https://gohugo.io/getting-started/installing/#macos) <br /> <br />

### Locally Hosting Website

**Step 1.** Change current directory to website template directory <br />
**Step 2.** Run terminal in the website template directory <br />
**Step 3.** Use ```hugo server``` command to build live website. <br />
**Step 4.** Go to http://localhost:1313/ to view the website. <br />

### Edit Content

Most important components are located within the **/content** directory.  <br /> <br />

To edit your personal information, go to **content/authors/(YOUR NAME)/** <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; CV files are stored in **/static/files/(YOUR NAME)**  <br />
To edit your publications, go to **content/publication/(YOUR PUBLICATION)/**  <br />
To add a new publication, go to **content/publication/** and use copy of **journal-article** directory as template <br />
To edit or add demonstration, go to **content/demos/demos.md**  <br />
To edit or add blog posts (news), go to **content/post/** and use copy of **22-02-02-Detectron-2-Workshop** as template  <br />
To edit research page, go to **content/research/research.md**  <br />

### Build Static Website Files

```
hugo -D
```

## Working with Git and GitHub

### Git

If have no working knowledge of Git at commandline, then I suggest you to go over [Git in 2 Minutes](https://www.garyrobinson.net/2014/10/git-in-two-minutes-for-a-solo-developer.html) and [Git in 5 Minutes](https://classic.scottr.org/presentations/git-in-5-minutes/). Note that you migt need to still search [Git Documentation](https://git-scm.com/doc) for specific tasks.

**Step 1.** Fork this repository (via web browser or Github CLI) / clone using the above command (Git Bash)
**Step 2.** Make changes locally and push to your origin (Git Bash or Github CLI)
**Step 3.** Create a pull request to merge with the main project repository (via Git Bash, Github CLI or web broweser)

**Note:** *The network drives are only accesible by Jan Verwaeren; all pull requests need to be pushed by moderators*
