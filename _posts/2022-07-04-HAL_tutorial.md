---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)

lng_pair: hal_tutorial
title: HAL Tutorial

# post specific
# if not specified, .name will be used from _data/owner.yml
author: Yoga Varatharajah
# multiple category is not supported
category: Announcements
# multiple tag entries are possible
tags: [announcement, info, hal]
# thumbnail image for post
img: "/assets/img/default/bioe.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2022-07-04 15:00:00 -0600

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:10 +0900
# check the meta_common_description in _data/lang/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---

# Hal manual for BIOE 488
> "I am a HAL 9000 computer. I became operational at the H-A-L plant in Urbana Illinois on the 12th of January 1992." -- HAL 9000
## Important Links

[HAL Wiki Page](https://wiki.ncsa.illinois.edu/display/ISL20/HAL+cluster)

[HAL Ondemand](https://wiki.ncsa.illinois.edu/display/ISL20/HAL+cluster)

[HAL Ondemand Brief Guide](https://wiki.ncsa.illinois.edu/display/ISL20/Getting+started+with+HAL+OnDemand)
## Registration

1. Familiarize yourself with basic information about Hal on [HAL Wiki Page](https://wiki.ncsa.illinois.edu/display/ISL20/HAL+cluster) and [HAL New User Guide](https://wiki.ncsa.illinois.edu/display/ISL20/New+User+Guide+for+HAL+System)
2. Follow the instructions on [HAL New User Guide](https://wiki.ncsa.illinois.edu/display/ISL20/New+User+Guide+for+HAL+System). You are recommended to use your NetID as your NCSA username.
3. You might need to wait for a few days to get approved. Once you are approved, you should be able to log in on Hal's log-in nodes through ssh: `ssh <username>@hal.ncsa.illinois.edu`

4. Verify that you have access to [Hal on-demand](https://wiki.ncsa.illinois.edu/display/ISL20/HAL+cluster)

## Interactive Jupyter Notebook Sessions on Hal-on-Demand
### Jupyter Notebook
 
1. Locate "Jupyter Lab" in "Pinned Apps" or in the "Apps" dropdown menu in the banner.
2. Configure the Jupyter Lab instance as instructed by your MP document. Then click on "Launch".
3. Wait for your scheduled session to be ready. Once it's ready, click on "Connect..."
4. Be sure to choose the Python kernel/environment as instructed by the MP document. A Python virtual environment contains the Python interpreter, packages and scripts. You will be able to restart the Python kernel and change the environment later too.



### Uploading data and files
1. Open "Files" page from the "Files" dropdown menu.
2. Here you can upload or download files from/to the Hal Jupyter server. You'll have 5TB of storage space under your home directory available, which is far more space than what you need for the class.
### Python kernel and environment

### Managing Interactive Sessions

1. If you are disconnected from your interactive session such as accidentally closing the webpage, go to "My Interactive Sessions", and you will be able to connect back again.
2. Once you are done, you can delete your interactive session to release the resources.


