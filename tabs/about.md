---
layout: about
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_about

# image for page specific usage
img: "/assets/img/default/bioe.jpg"
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

page_data:
  main:
    header: "Course Staff"
    info: "BIOE 488"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Professor"
      type: id_professor
      color: "gray"
    - title: "Teaching Assistants"
      type: id_teaching_assistants
      color: "#F4A273"
    # - title: "Programming"
    #   type: id_programming
    #   color: "#62b462"

  list:
    -
    # Professor info is hard-coded in _layouts/about.md
    # - type: id_professor
    #   title: "Yogatheesan Varatharajah"
    #   url: "https://bioengineering.illinois.edu/people/varatha2"
    #   info: ""

    # jekyiiliquid
    - type: id_teaching_assistants
      title: "Name of TA"
      url: "about:blank"
      info: "Your Teaching Assistant"
      img_url: "https://i0.wp.com/bdn-data.s3.amazonaws.com/uploads/2021/04/US-April-the-Giraffe-1.jpg"



---

# Course Staff
## [Professor Yogatheesan Varatharajah](https://bioengineering.illinois.edu/people/varatha2)
![Professor](https://ws.engr.illinois.edu/directory/viewphoto.aspx?id=109962&s=300&type=portrait)