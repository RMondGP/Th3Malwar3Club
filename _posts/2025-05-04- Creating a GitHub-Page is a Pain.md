---
layout: post
title: Creating Github-Page is a Pain
subtitle: My method of getting this site to work.
author: RMondGP
categories: jekyll
banner:
  video: https://vjs.zencdn.net/v/oceans.mp4
  loop: true
  volume: 0.8
  start_at: 8.5
  image: "assets/images/banners/home.jpg"
  opacity: 0.618
  background: "#000"
  height: "100vh"
  min_height: "38vh"
  heading_style: "font-size: 4.25em; font-weight: bold; text-decoration: underline"
  subheading_style: "color: gold"
tags: git obsidian vault howto
top: 1
sidebar: []
---
# Getting Started

Before we begin, please be aware that you need to understand some coding concepts and a little of website coding, such as CSS, HTML, or JS to potentially get this to work the way I did. 

The first thing you may need to do is get a [GitHub](https://github.com/) account. They have a free account and the GitHub pages is free. Note: GitHub pages must be public.
## Step 1. Create a GitHub repository

1. Click on the **+** icon in the top-right corner and select **New repository**.
2. Name your repository **`username.github.io`** (replace `username` with your GitHub username).
3. Set the repository to **Public** (GitHub Pages only works for public repositories on free accounts).
4. Click **Create repository**.

>**Mind you my repository name is just the Th3Malwar3Club**
## Step 2: Download Obsidian

1. Go to the [Obsidian Website](https://obsidian.md/) 
2. Download and install the specific version for your machine
## Step 3: Setting up a Vault

Now setting up a vault is just a fancy word for creating a folder where you will place all your files. Instead of creating a folder through Obsidian, I went ahead and creating a folder in the place I wanted on my computer which was my D: drive.

1. Pick a location for your folder and name it the same as your GitHub repo
2. Open Obsidian and click open folder as vault
3.  This will open the vault up as a directory for adding notes etc...
## Step 4: Installing GIT

There is variety of ways to go about using GIT, I began with GIT for Windows which a total pain in the behind since it just opens up its own terminal and has its own environment. I had to trouble shoot a lot of things. I eventually went on to using Windows Subsystem for Linux with an Ubuntu instance.

1. Install Git for Windows from Website
### Using WSL for Git

1. Installing WSL via Powershell
```powershell
wsl --install -d Ubuntu
```
2. Reboot before installation is complete
3. Once back, type WSL in Windows search
4. A terminal with start a virtualized ubuntu session
5. In terminal window update and install git
```bash
apt install git
```

