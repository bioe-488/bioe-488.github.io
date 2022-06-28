---
layout: schedule
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_schedule

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
image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


page_data:
  main:
    header: "Course Schedule"
    info: "BIOE 488"

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:

    - title: "Week 1"
      type: id_week1
    - title: "Week 2"
      type: id_week2
    - title: "Week 3"
      type: id_week3
    - title: "Week 4"
      type: id_week4
    - title: "Week 5"
      type: id_week5
    - title: "Week 6"
      type: id_week6
    - title: "Week 7"
      type: id_week7
    - title: "Week 8"
      type: id_week8
    - title: "Week 9"
      type: id_week9
    - title: "Week 10"
      type: id_week10
    - title: "Week 11"
      type: id_week11
    - title: "Week 12"
      type: id_week12
    - title: "Week 13"
      type: id_week13
    - title: "Week 14"
      type: id_week14
    - title: "Week 15"
      type: id_week15
  list:
    -
    # Professor info is hard-coded in _layouts/about.md
    # - type: id_professor
    #   title: "Yogatheesan Varatharajah"
    #   url: "https://bioengineering.illinois.edu/people/varatha2"
    #   info: ""
    - title: "Week 1"
      type: id_week1
      lecture: "Intro to BIOE 488"
      lab: "HAL Tutorial; GIT for Labs and MPs; Python basic tutorial"
      mp: ""
    - title: "Week 2"
      type: id_week2
      lecture: "Python functions, optional arguments, lists and tuples; Numpy functions"
      lab: "Medical image formats; Loading and visualizing images"
      mp: ""
    - title: "Week 3"
      type: id_week3
      lecture: "Elements of a CPU, basic computation, Pipelining"
      lab: "Vectorization; Vectorized operations in Numpy"
      mp: ""
    - title: "Week 4"
      type: id_week4
      lecture: "Memory hierarchies; Caches"
      lab: "Convolutions (1-D, 2-D)"
      mp: "MP1 release - 1D, 2D convolutions and edge detection"
    - title: "Week 5"
      type: id_week5
      lecture: "Week 5	Modern multicore processors and architectures"
      lab: "Image deconvolution intro"
      mp: ""
    - title: "Week 6"
      type: id_week6
      lecture: "Threads and processes"
      lab: "3D Convolution & Richardson Lucy Algorithm"
      mp: "MP2 release - 3D conv and RL for a medical image"
    - title: "Week 7"
      type: id_week7
      lecture: "Integer and floating-point representations"
      lab: "Numerical representation errors; Algorithm speedup"
      mp: ""
    - title: "Week 8"
      type: id_week8
      lecture: "Parallel programming concepts; Functional vs data parallelism"
      lab: "Python multiprocessing module"
      mp: "MP3 release - parallel RL algorithm on multiple images"
    - title: "Week 9"
      type: id_week9
      lecture: "GPU introduction"
      lab: "Numba decorators for parallel and GPU computing"
      mp: ""
    - title: "Week 10"
      type: id_week10
      lecture: "Implementing parallel algorithms in a GPU"
      lab: "3D conv in GPU"
      mp: "MP4 release - 3D conv in GPU"
    - title: "Week 11"
      type: id_week11
      lecture: "Intro to Tensorflow"
      lab: "TF tutorial; How convolutions work in TF"
      mp: ""
    - title: "Week 12"
      type: id_week12
      lecture: "Intro to linear regressionML workflow"
      lab: "Training, testing ML models, metrics, visualizing loss"
      mp: "MP5 release - linear regression in TF"
    - title: "Week 13"
      type: id_week13
      lecture: "Fall Break"
      lab: "Take a break"
      mp: "Sleep"
    - title: "Week 14"
      type: id_week14
      lecture: "Convolutional Neural Net Intro"
      lab: "CNN example in TF, tensorboard"
      mp: ""
    - title: "Week 15"
      type: id_week15
      lecture: "Final Quiz"
      lab: "Final Quiz"
      mp: ""
    # jekyiiliquid
    - type: id_teaching_assistants
      title: "Name of TA"
      url: "about:blank"
      info: "Your Teaching Assistant"
      img_url: "https://i0.wp.com/bdn-data.s3.amazonaws.com/uploads/2021/04/US-April-the-Giraffe-1.jpg"


---

