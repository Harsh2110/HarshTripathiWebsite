---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Risk Analyst
    company: Uber
    company_url: 'https://www.uber.com/'
    company_logo: uber_logo
    location: Hyderabad, India
    date_start: '2020-09-01'
    date_end: '2021-06-01'
    description: Developed strategies to mitigate payment fraud through Data Analysis and visualization.
    
        
  - title: Junior Data Scientist
    company: Cars24 India
    company_url: 'https://www.cars24.com/'
    company_logo: cars24_logo
    location: Gurgaon, India
    date_start: '2019-06-01'
    date_end: '2020-09-01'
    description: |2-
        Worked in end-to-end Data Science on -
        
        * XGBoost model for follow-up optimization
        * Regression Model to rationalize customer expectations
        * Hierarchical Clustering for cohort-based recommendation
        

  - title: Data Analyst Intern
    company: MyGov (Government of India), India
    company_url: 'https://www.mygov.in/'
    company_logo: mygov_logo
    location: Delhi, India
    date_start: '2018-06-01'
    date_end: '2018-07-01'
    description: Worked on Exploratory Data Analysis and Model building of the Twitter impact of politicians of India.

design:
  columns: '2'
  
  background:
    # Name of image in `assets/media/`.
    image: Work.jpg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.2
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true
---
