---
author: Zhiyuan
comments: true
date: 2017-05-24
layout: post
title: Jupyter Notebook Dark Themes
categories: Tech
tags:
- Environment Setup
- Windows 10
- Ubuntu
---

I am using this [this](https://github.com/dunovank/jupyter-themes). There isn't much on my part.

```
pip install --upgrade jupyterthemes
jt -t onedork -fs 13 -altp -tfs 13 -nfs 13 -cellw 88% -T -N
```

Sudo with Linux. Here is a sample screen shot.

![tex studio dark theme example]({{ site.url }}/public/img/jupyter_notebook_dark_theme.png)

----

For Windows to set up the initial directory:

```
jupyter notebook --generate-config
```

Which writes file to 

```
C:\Users\username\.jupyter\jupyter_notebook_config
```

Uncomment line 179 and set it to
```
c.NotebookApp.notebook_dir = 'desired path'
```

----
