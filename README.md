# resume
resume
![resume](https://github.com/charudatta10/resume/blob/main/ModernMinimalistCVResume.png)
## Overview

**tccv** (two columns curriculum vitae) is a LaTeX class inspired by the
template found at
[latextemplates](http://www.latextemplates.com/template/two-column-one-page-cv)
by Alessandro Plasmati.

From a TeXnical point of view this is a complete rewrite. From the user
perspective, the most relevant differences from the original template are:

* this is a class, not a template document;
* more than one page are handled properly;
* the fonts are selected from the
  [psnfss](http://www.ctan.org/pkg/psnfss) collection, so no
  custom font installation should be required;
* it is plain LaTeX/Koma-script, so the CV can be compiled
  with the usual tools, latex and pdflatex included;
* the implementation is heavily based on custom environments
  and macros, so the document should be much easier to read
  (and customize);
* tccv is based on scrartcl (from Koma-script), not on article.

## How to use

You can download the [zipped
tarball](http://dev.entidi.com/p/tccv/source/download/master/) that includes a
couple of examples or pick only the relevant [LaTeX
class](http://dev.entidi.com/p/tccv/source/file/master/tccv.cls).

The code is maintained in a [git](http://git-scm.com/) repository [browsable
online](http://dev.entidi.com/p/tccv/source/tree/master/). A clone of that
repository can be found on [github](https://github.com/ntd/tccv): fill free to
fork it and extends in any way you like.

A sample PDF generated by the above class is [available
online](http://www.entidi.com/assets/pdf/nicola.en.pdf).

## Howto

### Personal box on top

The `\personal` box by default follows the text flow. If you want to
affix it on the top (or on the bottom) you can make it a float, e.g.:

    \begin{figure}[b] % Push the figure at the bottom; use t for top
    \personal[url]
             {address}
             {phone}
             {email}
    \end{figure}

Alternatively you can use the myfloat package:

    % In the preamble
    \usepackage{float}
    \newfloat{myfloat}{t}{} % 'myfloat' is arbitrary, 't' stands for 'top'

    % Then wrap your personal data using the newly created custom float
    \begin{myfloat}
    \personal[url]
             {address}
             {phone}
             {email}
    \end{myfloat}

### Personal box broken in LyX

For some reason LyX (at least up to 2.1.3) escapes the brackets of the
`\personal` optional argument, scattering the URL letters all around.
If this is the case if you look at the source window you should see
something like `{[}www.myweb.site{]}` instead of `[www.myweb.site]`.

To solve this problem just readd the argument as *TeX code* by
eventually using the `CTRL-l` shortcut.
<!--
---
title: 'readme.md'
authour: 'charudatta korde'
date: '27-july-2023 16:54:00'
---
-->
# Portfolio
<h1 align="center">Hi 👋, I'm Charudatta Gurudas Korde</h1>
<h3 align="center">A passionate AI-ML-EDGE developer from Multiverse 1729</h3>

<p align="center"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=charudatta10&row=2&column=3" alt="charudatta10" /></a> </p>

- 🔭 I’m currently working on [Privacy and Data security with GAN's](https://github.com/charudatta10)

- 🌱 I’m currently learning **HLS4ML**

- 👯 I’m looking to collaborate on [AI ML EDGE devices](https://github.com/charudatta10)

- 🤝 I’m looking for help with [Python to edge flow](https://github.com/charudatta10/Vitis-AI)

- 👨‍💻 All of my projects are available at [https://github.com/charudatta10](https://github.com/charudatta10)

- 💬 Ask me about **Genetic Algorithm, GANs, FPGAs**

- 📫 How to reach me **10682378+charudatta10@users.noreply.github.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.gnu.org/software/bash/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gnu_bash/gnu_bash-icon.svg" alt="bash" width="40" height="40"/> </a> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-original.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.mathworks.com/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/2/21/Matlab_Logo.png" alt="matlab" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://pytorch.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" alt="pytorch" width="40" height="40"/> </a> <a href="https://redis.io" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original-wordmark.svg" alt="redis" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=charudatta10&show_icons=true&locale=en&layout=compact" alt="charudatta10" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=charudatta10&show_icons=true&locale=en" alt="charudatta10" /></p>

<embed src="resume.pdf" type="application/pdf">



