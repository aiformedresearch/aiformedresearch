---
title: Home
---

# AI for Medicine Research Group

Welcome to the AI for Medicine Research Group! We are a team of researchers dedicated to advancing the field of precision medicine through the use of artificial intelligence. At the heart of our work is a commitment to open science and collaboration. We believe in sharing all of our source code to accelerate research in this field, and we're excited to work with others who share our passion for using AI to improve patient outcomes.

{%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%}
{%
  include button.html
  type="github"
  text="See our Lab on GitHub"
  link="[greenelab/lab-website-template](https://github.com/aiformedresearch)"
%}



{% 
  include button.html
  background="images/Research_img.png"
  dark=true
  size=full
%}

## Our Research

{:.center}
Our research mainly focuses in Neurological Disorders, such as Dementia, Autism and Schizophrenia. 
At the heart of our research efforts lies a singular goal: leveraging technology to drive advancements in healthcare. Our focus is on designing and developing specialized frameworks that address healthcare challenges, assist clinicians, uncover valuable biomarkers, and bridge the gap between computer science research and practical clinical applications. With a particular emphasis on the power of AI, we aim to optimize the medical domain by effectively utilizing technologies like images, clinical data, and genomics. By applying our expertise in these areas, we strive to improve medical practices and outcomes, making a tangible impact on the field of healthcare.
{:.center}

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}

{% include section.html %}

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

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
