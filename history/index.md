title: History
slug: history
date: 2022-08-26 12:02:45 UTC+12:00
tags: 
category: 
link: 
description: 
type: text
hidetitle: true
<!---
Draft completed: 2022-08-28 Ian Stewart
2023-08-15 - Ian - Edit links to point to wlug
-->

# History and General Information

## Wiki

In 2002 WLUG became an incorporated society and at the same time a [Wiki](https://en.wikipedia.org/wiki/Wiki) was set up to aid Linux and Open Source enthusiasts. At the time Daniel Lawson was the president of WLUG. Daniel continues to keep the *WLUG wiki* running on his servers.

Feel free to take a walk back in time and browse the [WLUG wiki](http://wiki.wlug.org.nz/)


## Creation of this WLUG Website

This website has been created using the Python based [Nikola](https://getnikola.com/) *Static Site Generator*. This is open source software and you may view the GitHub repository for the [source code](https://github.com/getnikola/nikola).

The source files used for *Nikola* to build this website reside at the WLUG repository wlug.github.io [src branch](https://github.com/wlug/wlug.github.io/tree/src), while the website html files reside in the [main branch](https://github.com/wlug/wlug.github.io)

Those with access to the WLUG repository wlug.github.io may have a local [Git](https://en.wikipedia.org/wiki/Git) folder that holds a copy of the source and main website files. These files may then be edited to enhance the website and using the *nokola github_deploy* bash command the files on GitHub are updated. 

GitHub also provide web-hosting service and this WLUG website is accessed via [https://wlug.github.io](https://wlug.github.io).

Using a [CNAME record](https://en.wikipedia.org/wiki/CNAME_record) the DNS is able to map **www.wlug.org.nz** to **wlug.github.io**. Users connecting to [https://www.wlug.org.nz](https://www.wlug.org.nz) will be unaware that they are connected to a GitHub hosted website.

Another feature of GitHub is that using a browser a change may be made to the website source code. For example a change of phone number. Upon committing the change, GitHub will run the Nikola updating process. After a few minutes the web-site will be updated. This is done by the [workflow yaml code](https://getnikola.com/blog/automating-nikola-rebuilds-with-github-actions.html) in the src branch file .github/workflows/main.yml. x
 
            







