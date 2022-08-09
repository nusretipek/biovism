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
To edit or add blog posts (news), go to **content/post/** and use copy of 22-02-02-Detectron-2-Workshop** as template  <br />
To edit research page, go to **content/research/research.md**  <br />

### Build Static Website Files

```
hugo -D
```

