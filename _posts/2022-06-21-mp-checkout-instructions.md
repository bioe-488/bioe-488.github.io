---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)

lng_pair: mp_checkout_instructions
title: MP Checkout & Submit Instructions

# post specific
# if not specified, .name will be used from _data/owner.yml
author: CY Huang
# multiple category is not supported
category: Announcements
# multiple tag entries are possible
tags: [announcement, info]
# thumbnail image for post
img: "/assets/img/default/bioe.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2022-06-21 15:00:00 -0600

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

First: Git clone your repo.
```git clone https://github.com/illinois-bioe/fa22_bioe488_NETID.git bioe488git```

Here you can use any other name instead of `bioe488git`.

Second. Checkout the MP release branch
``` git fetch ```
``` git checkout [MP release branch] ```

Third. Work on your MP. You can check-point your progress using git by commiting your code and pushing it to the remote repo.

Fourth. With your final submission version of code, merge your "work branch" to the main branch for submission. This is very important: we will only consider the last commit before the each MP deadline on the __main__ branch for valid submissions. The "work branch" could be the MP release branch, if you never changed branch after MP release; a separate branch, or main. We recommend you use the MP release branch to keep your work progress and merge it to main once you are done.
Give yourself enough time before each deadline to prepare your submission with git. __Practice__ basic git operations, including merge, if you are not sure.

Since we are dealing with simple situation, merging two branches with no overlapping files, there are two simple ways. Do it in Git CLI (in your terminal, by typing git commands), or on Github website.

[A tutorial on ```git merge```](https://www.varonis.com/blog/git-branching#:~:text=To%20merge%20branches%20locally,%20use,to%20bring%20into%20this%20branch.)

Notice that all the branches needed (main and individual MP release branches) are created for you, and you don't have to create any new branch.

Before attempting to merge, make sure you have all your progress pushed to the remote repository no the current branch.

1. Go to the root directory in your local repository in your terminal.
2. Switch to the main branch where we will receive the change from your work branch
``` git checkout main```
    if you see error "Deletion of directory 'MP#' failed. Should I try again? (y/n)", it is most likely that you tried to switch branch while you are in a directory which doesn't exist in the branch you are switching to. Use ```cd ../ `` to go back to the parent directory.
3. List all branches in the current repository. This step is not required.
``` git branch ```
4. Initiate a merge
``` git merge [source branch] --allow-unrelated-histories ```
Where [source branch] is the name of your "work branch" as seen in step 3.
e.g. ``` git merge MP1-release --allow-unrelated-histories```
Git will merge the specified branch in to the currently active branch. Since we have selected the ```main``` branch in step 2, the example will merge ```MP1-release``` in to ```main``` branch.
5. Once the operation is complete, make sure to push the merge result to your remote git repository, __on the ```main``` branch__
``` git push origin main```
