---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
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


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Helpful Links"
    info: "BIOE 488"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Programming"
      type: id_programming
      color: "blue"
    - title: "Python"
      type: id_python
      color: "gray"
    - title: "GPU Computing"
      type: id_gpu_computing
      color: "#F4A273"
    - title: "Git"
      type: id_git
      color: "#62b462"
    - title: "HAL"
      type: id_hal
      color: "orange"

  list:
    -
    # programming
    - type: id_programming
      title: "Stack OverFlow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow is a question and answer website for professional and enthusiastic programmers."

    - type: id_git
      title: "Git and Version Control"
      url: "https://www.atlassian.com/git/tutorials/what-is-version-control"
      info: "An in-depth tutorial on Git and version control."
      
    - type: id_python
      title: "Python Tutorial"
      url: "https://docs.python.org/3/tutorial/"
      info: "Official Python documentation."
      
    - type: id_hal
      title: "HAL Tutorial"
      url: "https://bioe-488.github.io/posts/2022-07-04-HAL_tutorial"
      info: "HAL setup tutorial"
      
      - type: id_gpu_computing
      title: "GPU Computing in Python"
      url: "https://thedatafrog.com/en/articles/boost-python-gpu/"
      info: "Using GPUs within Python"
---
