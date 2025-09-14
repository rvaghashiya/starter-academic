<!-- ---
# An instance of the Featurette widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featurette

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: Skills
subtitle:

# Showcase personal skills or business features.
# - Add/remove as many `feature` blocks below as you like.
# - For available icons, see: https://wowchemy.com/docs/page-builder/#icons

# - description: 
#   icon: opencv
#   icon_pack: custom
#   name: OpenCV

# - description: 
#   icon: flask
#   icon_pack: custom
#   name: Flask

# - description: Digital Inline Holography
#   icon: microscope
#   icon_pack: fas
#   name: Medical Imaging

feature:

- description: 
  icon: tensorflow
  icon_pack: custom
  name: TensorFlow-Keras

- description: 
  icon: python
  icon_pack: fab
  name: Python

- description: PyTorch, Qiskit, OpenVINO
  icon: laptop-code
  icon_pack: fas
  name: Frameworks

# - description: 
#   icon: latex
#   icon_pack: custom
#   name: LaTex

# - description: English, Gujarati, Hindi (C1) ; German (A2)
#   icon: globe
#   icon_pack: fas
#   name: Languages

# - description: 90%
#   icon: r-project
#   icon_pack: fab
#   name: R
# - description: 100%
#   icon: chart-line
#   icon_pack: fas
#   name: Statistics
# - description: 10%
#   icon: camera-retro
#   icon_pack: fas
#   name: Photography

# Uncomment to use emoji icons.
#- icon: ":smile:"
#  icon_pack: "emoji"
#  name: "Emojiness"
#  description: "100%"  

# Uncomment to use custom SVG icons.
# Place your custom SVG icon in `assets/media/icons/`.
# Reference the SVG icon name (without `.svg` extension) in the `icon` field.
# For example, reference `assets/media/icons/xyz.svg` as `icon: 'xyz'`
#- icon: "your-custom-icon-name"
#  icon_pack: "custom"
#  name: "Surfing"
#  description: "90%"
--- -->

---
widget: skills
headless: true
weight: 30
title: "Skills & Tools"
<!-- # Define your grouped skills here:
# Define grouped skills with built-in icons: -->
skills:
  - group: "Programming"
    items:
      - name: "Python"
        icon: "python"
        icon_pack: "fab"
      - name: "C++"
        icon: "code"
        icon_pack: "fas"

  - group: "Deep Learning & AI"
    items:
      - name: "PyTorch"
        icon: "pytorch"
        icon_pack: "fab"
      - name: "TensorFlow"
        icon: "tensorflow"
        icon_pack: "fab"
      - name: "Keras"
        icon: "brain"
        icon_pack: "fas"
      <!-- - name: "Hugging Face"
        icon: "huggingface"
        icon_pack: "custom"    # only if you have your own SVG in assets/media/icons/ -->
      - name: "Hugging Face"
        icon: "hf"
        icon_pack: "fab"
        

  - group: "Computer Vision"
    items:
      - name: "OpenCV"
        icon: "opencv"
        icon_pack: "custom"  
      - name: "scikit-image"
        icon: "images"
        icon_pack: "fas"      # fallback icon
      - name: "OpenVINO"
        icon: "openvino"
        icon_pack: "custom"   # provide your SVG in assets/media/icons/openvino.svg

  - group: "MLOps & Deployment"
    items:
      - name: "Docker"
        icon: "docker"
        icon_pack: "fab"
      - name: "Kubernetes"
        icon: "kubernetes"
        icon_pack: "fab"
      <!-- - name: "MLflow"
        icon: "flask"
        icon_pack: "fas"      # fallback or custom -->
      - name: "Flask"
        icon: "flask"
        icon_pack: "fas"
      - name: "Git"
        icon: "git-alt"
        icon_pack: "fab"

  - group: "Cloud & Infrastructure"
    items:
      - name: "AWS SageMaker"
        icon: "aws"
        icon_pack: "fab"
      - name: "GCP Vertex AI"
        icon: "google-cloud"
        icon_pack: "fab"

  - group: "Data Science & Visualization"
    items:
      - name: "NumPy"
        icon: "square-root-alt"
        icon_pack: "fas"
      - name: "Pandas"
        icon: "pandas"
        icon_pack: "custom" 
      - name: "Scikit-learn"
        icon: "scikitlearn"
        icon_pack: "custom"
      - name: "Matplotlib"
        icon: "chart-bar"
        icon_pack: "fas"
      - name: "Seaborn"
        icon: "seedling"
        icon_pack: "fas"
      - name: "Plotly"
        icon: "plotly"
        icon_pack: "custom"
      
  - group: "Environment & Design"
    items:
      - name: "Linux"
        icon: "linux"
        icon_pack: "fab"
      - name: "Figma"
        icon: "figma"
        icon_pack: "fab"

  - group: "Languages"
    items:
      - name: "English"
        icon: "flag-usa"
        icon_pack: "fas"
      - name: "German"
        icon: "flag-de"
        icon_pack: "custom"
      - name: "Gujarati"
        icon: "flag-in"
        icon_pack: "custom"
      - name: "Hindi"
        icon: "flag-in"
        icon_pack: "custom"
---