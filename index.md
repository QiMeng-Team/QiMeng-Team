---
---

# QiMeng-Team's Website

The main goal of the QiMeng-Team is to deeply integrate the knowledge of the software development field with large model technologies, explore new paradigms for software development, and achieve the automatic generation of typical basic software and application software with high performance and high quality. This is expected to significantly improve the efficiency of software development and efficiently support the construction of the software ecosystem for new processors such as RISC-V.

{% include section.html %}

## Highlights

{% capture text %}

The QiMeng-GEMM framework enables large language models to understand the characteristics of different hardware architectures and automatically search for optimized GEMM combinations. A large number of experiments have proven that it demonstrates outstanding performance in automatically generating optimized GEMM code. It can significantly boost performance, shorten the development cycle, and reduce costs, bringing remarkable benefits to the development of related applications in the RISC-V ecosystem.
你好

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}
