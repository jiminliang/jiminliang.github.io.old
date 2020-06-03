# LiangLab@Xidian University

This website is build with [Jelyll](https://jekyllrb.com/docs/) and the template of [Project Pages](http://projectpages.github.io/project-pages/).


-------------

Fundamentals
-------------
Github provides a simple way to build and host a static website or blogs. It surports [Jelyll](https://jekyllrb.com/docs/), a simple, extendable, static site generator, and [markdown](http://www.markdown.cn/) language to wirte the website pages. 

1. Basic knowledge about [Github Pages](https://pages.github.com/). I used *homepage* in stead of *username*.github.io as the repository name of my website. In this case my website can be accessed at https://jiminliang.github.io/homepage/.

2. Knowledge about [Jekyll](https://jekyllrb.com/docs/). 

3. Our website is based on the [Project Pages](http://projectpages.github.io/project-pages/) template. I moved the blog page to an individual webpage, by adding the following line in *_config.yml*:
```
paginate_path: "/blog/page:10/"
```
4. For publication list, I used the [bibjekyll](https://github.com/pablooliveira/bibjekyll) plugin. On Windows, beside bibtex2html, you also need to install the bibtex.exe. I installed the CTEX packges to have it. 

A more detailed description on how to maintain a website with Jekyll can be found [here](https://github.com/kdsec/kdsec.github.io).


Installation
-------------
1. Install Jekyll following comments [here](https://jekyllrb.com/docs/installation/windows/).

2. Install jekyll-paginate plugin :
```
gem install jekyll-paginate
```

3. Install bibjekyll plugin following comments [here](https://github.com/pablooliveira/bibjekyll) and add the path of Bibtex2html to system path variable. 


Build
-------------
1. Preview locally ：
```
jekyll serve
```
Then visit http:localhost:4000 to preview the webpages. 

2. Build to other directory ：
```
jekyll build --destination ..\homepage
```

3. Done. Publish it with Git. 



# Reference:
1. [Maintaining the Kwiat group website with Jekyll](https://github.com/kdsec/kdsec.github.io). 
