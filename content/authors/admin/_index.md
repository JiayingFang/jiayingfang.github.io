---
# Display name
title: Jiaying Fang

# Name pronunciation (optional)
# name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Jiaying
last_name: Fang

# Status emoji
# status:
#   icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: MS EE Student

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Stanford University
    url: https://www.stanford.edu/

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'jyfang@stanford.edu'
    label: E-mail Me
  # - icon: brands/x
  #   url: https://twitter.com/GetResearchDev
  # - icon: brands/instagram
  #   url: https://www.instagram.com/
  # - icon: brands/github
  #   url: https://github.com/gcushen
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/jiaying-fang-554b691b8/
  # - icon: academicons/google-scholar
  #   url: https://scholar.google.com/
  # - icon: academicons/orcid
  #   url: https://orcid.org/

interests:
  - Robotics
  - Computer Vision
  - Haptic Sensing

education:
  - area: MSc in Electrical Engineering
    institution: Stanford University
    date_start: 2023-09-01
    date_end: 2025-06-01
    summary: |
      GPA: 4.18/4.00

      Specialization:
      - Robotics
      - Machine Learning
      - Signal Processing
    # button:
    #   text: 'Read Thesis'
    #   url: 'https://example.com'
  - area: BEng (Honours) in Electronic and Information Engineering
    institution: Hong Kong Polytechnic University
    date_start: 2019-09-01
    date_end: 2023-06-01
    summary: |
      GPA: 4.01/4.00

      Minor:
      - Applied Mathematics
  - area: Exchange Student
    institution: McGill University
    date_start: 2022-01-01
    date_end: 2022-08-01
    summary: |
      GPA: 4.00/4.00
      
work:
  - position: Research Assistant
    company_name: Interactive Perception and Robot Learning Lab, Stanford University 
    company_url: 'https://iprl.stanford.edu/'
    company_logo: ''
    date_start: 2024-02-01
    date_end: ''
    summary: |2-
      Supervisor: Prof. Jeannette Bohg
      - Designing and implementing a cross-embodiment scheme to zero-shot transfer a policy trained on videos of humans performing a task to a robot. To be submitted in January 2025, aiming for RSS 2025.
      - Evaluated Reinforcement Learning methods on robotics tasks that require fast reactive motions in Mujoco. This project is funded by Toyota Research Institute.
      - Conducted joint torque feedback analysis on a large-scale robotics dataset - DROID dataset. Presented important rules of haptic data collection in future large-scale distributed robotics dataset at Stanford cross-labs robotics meeting. 
    button:
    text: 'Slides'
    url: 'https://docs.google.com/presentation/d/1fqNfCkngdy15E_D1UGwR4o48xJiQogwx017seOpB4So/edit?usp=sharing'
  - position: Machine Learning Intern
    company_name: Intuitive Surgical
    company_url: 'https://www.intuitive.com/en-us'
    company_logo: ''
    date_start: 2024-06-17
    date_end: 2024-09-06
    summary: |
     - Designed and implemented an end-to-end deep learning-based 3D gaze estimation algorithm. The algorithm is robust to head motions, and it improves the gaze estimation performance by 84.5%.
     - Generated more than 100k synthetic images with suitable domain randomization in Blender for gaze estimation training.
     - Designed real-world gaze estimation data collection pipeline and conducted data collection. Conducted detailed analysis and visualization of the dataset.
     - Implemented a semi-auto labeling tool for pupil localization and segmentation using SAM2.
  - position: Research Assistant
    company_name: Collaborative Haptics and Robotics in Medicine Lab, Stanford University
    company_url: 'https://charm.stanford.edu/'
    company_logo: ''
    date_start: 2023-09-01
    date_end: 2024-01-01
    summary: |2-
      Supervisor: Prof. Allison Okamura
      - Designed and Implemented a force-aware autonomous tissue manipulation model using imitation learning with da-Vinci Research Kit (dVRK). The task completion rate of autonomous tissue retraction increased 50\% with haptic sensing. 
      - To be submitted to RAL around December 2024.
      - Presented force-aware autonomous surgery at Stanford Human-Centered Artificial Intelligence Conference 2024.
    button:
    text: 'Poster'
    url: 'https://hai.stanford.edu/sites/default/files/2024-06/Alaa_Eldin_and_Jiaying_Fang.pdf'
  - position: Computer Vision Algorithm Intern
    company_name: China Telecom AI
    company_url: 'https://www.chinatelecomglobal.com/'
    company_logo: ''
    date_start: 2023-06-01
    date_end: 2023-08-01
    summary: |
      - Co-led the team in the ICCV'23 Open Fine-Grained Activity Detection Challenge.
      - Won third place on the video activity recognition track and second place on the video activity detection track.
    button:
    text: 'Challenge'
    url: 'https://openfad.nist.gov/#pills-overview'
  - position: Undergraduate Research Assistant
    company_name: Prof. Mak's Lab, Hong Kong Polytechnic University
    company_url: 'https://www.eie.polyu.edu.hk/~mwmak/'
    company_logo: ''
    date_start: 2022-09-01
    date_end: 2023-03-01
    summary: |2-
      Supervisor: Prof. Man-Wai Mak
      - Implemented deep speaker embedding for speaker verification with a domain loss to alleviate the languages mismatch problem.
      - The performance of the ECAPA-TDNN (pre-trained using the English dataset) on the unlabelled Chinese dataset has improved by 10% with the MMD-based domain loss. Won the Honours Project Technical Excellence Award. 
    button:
    text: 'Report'
    url: 'https://drive.google.com/file/d/1u0oVlbbCxIFAbcdxVdU_fLN6S6T79gW6/view?usp=sharing'
    button:
    text: 'Code'
    url: 'https://github.com/JiayingFang/ECAPA-TDNN_across_lang'
  - position: Undergraduate Research Assistant
    company_name: Dynamics, Estimation, and Control in Aerospace and Robotics Lab, McGill University
    company_url: 'https://www.decar.ca/'
    company_logo: ''
    date_start: 2022-06-01
    date_end: 2022-08-01
    summary: |2-
      Supervisor: Prof. James Forbes
      - Designed a finite-horizon LQR control of UGV for path tracking.
      - Robot Operating System was used during implementation. The state of UGV was represented as an element of direct Euclidean isometries, SE(2). 
    button:
    text: 'Report'
    url: 'https://connectpolyu-my.sharepoint.com/personal/19078474d_connect_polyu_hk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2F19078474d%5Fconnect%5Fpolyu%5Fhk%2FDocuments%2FLQR%5FController%5FDesign%5FReport%5FJiayingFang%2Epdf&parent=%2Fpersonal%2F19078474d%5Fconnect%5Fpolyu%5Fhk%2FDocuments&ga=1'
  - position: Undergraduate Research Assistant
    company_name: Autonomous Systems Lab, Hong Kong Polytechnic University
    company_url: 'https://labsun.org/'
    company_logo: ''
    date_start: 2021-05-01
    date_end: 2021-10-01
    summary: |2-
      Supervisor: Prof. Yuxiang Sun
      - Developed a deep learning-based integration of monocular visual odometry and multi-object tracking.
      - Deployed deep optical-flow estimation for localization and 3D object detection models for 3D multi-object tracking.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: ""
    items:
      - name: Python, C, C++, Java, MATLAB, R
        description: ''
        percent: 100
        icon: code-bracket
      - name: Linux (Ubuntu), Raspberry Pi, STM32, Arduino
        description: ''
        percent: 100
        icon: cursor-arrow-rays
  - name: ""
    items:
      - name: PyTorch, TensorFlow, Jax, ROS, dVRK, Git, Docker, LaTeX, Blender, Mujoco, Gazebo, AutoCAD, SolidWorks
        description: ''
        percent: 100
        icon: code-bracket
      - name: 3D Printing, Circuit Design, Prototyping
        description: ''
        percent: 100
        icon: wrench

languages:
  - name: English
    percent: 100
  - name: Chinese
    percent: 75

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Honour Project - Technical Excellence Award
    url: https://drive.google.com/file/d/1HNEPbPHb3QhJPEJF25b8ufUav--McnfZ/view?usp=sharing
    date: '2023-06-01'
    awarder: Hong Kong Polytechnic University
    icon: ''
    summary: |
      - This award aims to recognize final-year students who excel in their Honours Project. 
      - Sole recipient of the award in 2022/23.
  - title: Outstanding Student Award of Faculty of Engineering
    url:  https://www.polyu.edu.hk/sao/student-resources-and-support-section/scholarships/outstanding-student-award-scheme/awardees-sharing/
    date: '2022-12-01'
    awarder: Hong Kong Polytechnic University
    icon: ''
    summary: |
      - A prestigious annual honor awarded to a \textbf{single} distinguished final-year undergraduate student within the Faculty of Engineering, Hong Kong Polytechnic University.
      - This award aims to award full-time final-year students who excel in both academic and non-academic pursuits during their studies.
      - Media coverage: 
    button:
    text: 'HK01'
    url: 'https://www.hk01.com/%E7%A4%BE%E6%9C%83%E6%96%B0%E8%81%9E/882652/%E7%90%86%E5%A4%A7%E5%8D%93%E8%B6%8A%E5%AD%B8%E7%94%9F%E7%8D%8E-%E5%8D%B0%E5%BA%A6%E5%A5%B3%E7%94%9F%E4%BF%AE%E8%AE%80%E6%9C%8D%E8%A3%9D%E5%8F%8A%E7%B4%A1%E7%B9%94-%E5%86%80%E6%96%BC%E6%99%82%E8%A3%9D%E7%95%8C%E6%8E%A8%E5%8B%95%E5%8F%AF%E6%8C%81%E7%BA%8C'
  - title: 'Scholarship on Outstanding Performance'
    url: https://www.edb.gov.hk/en/edu-system/postsecondary/local-higher-edu/publicly-funded-programmes/scholarship.html
    date: '2021-12-01'
    awarder: Hong Kong Polytechnic University
    icon: ''
    summary: |
      - This award aims to recognize outstanding local and non-local students studying Hong Kong.
      - The scholarship is \$80,000 HKD a year.
---

## About Me

I am a Master Student at Stanford University. I have worked on robot learning at the Interactive Perception and Robot Learning Lab and surgical robotics at Collaborative Haptics and Robotics in Medicine Lab at Stanford. In summer 2024, I joined Intuitive Surgical working on Human-Robot Interaction as a Machine Learning Intern. I finished my BEng degree in Electronic and Information Engineering at HK PolyU. My research interest lies in the intersection of Robotics, Computer Vision and Haptic Sensing.
