---
title: "Identifying Structure in Data"
subtitle: "All you need to know about Dimensionality Reduction, Clustering and more"
type: tutorial
date: 2025-06-12
time: "1:00PM"
venue: "CVPR 2025"
location: "In-Person, Room 106 B, Music City Center, Nashville TN"
format: "Half-Day Tutorial"

banner: /assets/images/banners/cvpr2025-banner.jpg
conference_logo: /assets/images/logos/cvpr-navbar-logo.svg
calendar_file: /calendar/cvpr2025.ics

floorplan:
  image: /assets/images/floorplans/cvpr2025-floorplan.png
  rotation: 270

external_links:
  - label: "[CVPR Tutorial Page]"
    url: "https://cvpr.thecvf.com/virtual/2025/tutorial/35919"
  - label: "[Floor Plan]"
    url: "https://www.nashvillemusiccitycenter.com/sites/default/files/media/Floorplans/mcc_floorplans.pdf"

excerpt_text: "An in-depth exploration of dimensionality reduction and clustering techniques with applications in computer vision."

overview: |
  As large-scale models and datasets grow, techniques for data curation, training objective definition, and quality monitoring are essential. Mastering them ensures efficient dataset exploration, robust model development, and impactful decision-making in AI and computer vision workflows.

  In today's AI landscape, these techniques are crucial. Dimensionality reduction tools like t-SNE, UMAP and h-NNE pose a possibility to highlight meaningful structures in visualizations and draw insights. Clustering, on the other hand, organizes unstructured data into meaningful groups, aiding knowledge discovery, feature analysis, and retrieval-augmented generation.

  These methods also address learned feature biases, errors, and redundancies affecting model performance. Dimensionality reduction, when done right, can help identify outliers and irregular patterns within the data. Robust clustering supports scalable embedding pipelines, enabling efficient data curation and querying. From k-means to DBSCAN and hierarchical approaches like FINCH, selecting the right method is key: including balancing scalability, managing noise sensitivity, and fitting computational demands.

  This tutorial provides an in-depth exploration of the current state-of-the-art of data exploration techniques such as dimensionality reduction for data visualization and clustering methods, with a strong focus on their applications within computer vision. Attendees will gain a comprehensive understanding of both foundational and advanced techniques beyond classic methods like t-SNE and k-means. Through a blend of theoretical insights and hands-on applications, participants will learn how to effectively apply these methods to tasks such as big data analysis, representation learning, model development, pseudo-labeling, and data annotation.

learning_outcomes:
  - "Grasp the core principles and techniques in dimensionality reduction and clustering."
  - "Analyze and evaluate algorithmic trade-offs and explore alternatives to popular methods."
  - "Learn practical strategies to apply these techniques for optimized results in computer vision."
  - "Apply these methods in real-world computer vision applications."

schedule:
  - time: "13:00 - 13:15"
    speaker: "Constantin Seibold"
    talk: "Welcome and Opening Remarks"
    slides: /assets/slides/cvpr25/Constantin_Seibold.pdf
  - time: "13:15 - 14:15"
    speaker: "M. Saquib Sarfraz, Marios Koulakis"
    talk: "Clustering and its applications in modern computer vision"
    slides: /assets/slides/cvpr25/Saquib_Marios_Slides.pdf
  - time: "14:15 - 15:15"
    speaker: "Laurens van der Maaten"
    talk: "How to use and not use modern dimension reduction techniques for data visualization"
  - time: "15:15 - 15:30"
    talk: "Coffee Break ☕"
    break: true
  - time: "15:30 - 16:30"
    speaker: "Brandon Duderstadt"
    talk: "Scaling dimensionality reduction with NOMAD projection"
    slides: /assets/slides/cvpr25/Brandon_Slides.pdf
  - time: "16:30 - 17:00"
    speaker: "All Speakers"
    talk: "Q&A and Panel Discussion"

materials: |
  We're excited to offer you a wealth of materials and interactive resources to enhance your experience during our tutorial. In addition to hands-on exercises and interactive Jupyter notebooks demonstrating cutting-edge techniques in dimensionality reduction and clustering for computer vision, we've prepared a variety of supportive resources to inspire and engage you.

  We warmly invite you to explore the following resources, which have been thoughtfully curated to spark your curiosity and support your learning journey:

  - **Questionnaire:** [Share your insights and questions](https://docs.google.com/forms/d/e/1FAIpQLSdj5Bh_EEmkBh62T0YgfRU6nNYgY6ZgVgSD19loTHQRLC8bbA/viewform?usp=sharing)
    <br>Your responses will help us understand your background, interests, and specific challenges related to dimensionality reduction, clustering, and data curation in computer vision. This will allow us to tailor the tutorial and round table discussion to meet your needs.

  - **Awesome GitHub Repositories:**
    - **Dimensionality Reduction:** [Explore the repository](https://github.com/koulakis/awesome-dimensionality-reduction)
      <br>This repository is a curated collection of resources, libraries, and research papers on various dimensionality reduction techniques. Whether you're looking for methods to improve data visualization or seeking practical implementations, you'll find a wealth of information to guide your projects.
    - **Clustering:** [Explore the repository](https://github.com/koulakis/awesome-clustering)
      <br>Dive into an extensive collection of clustering techniques ranging from classic algorithms like k-means to advanced modern approaches. This repository offers detailed insights, implementation examples, and case studies to help you apply clustering effectively in computer vision and beyond.

  We are thrilled to welcome researchers, practitioners, and students to this half-day in-person tutorial. We hope these resources will spark new ideas and enhance your exploration of the exciting world of computer vision and data analysis.

speakers:
  - name: "M. Saquib Sarfraz"
    photo: /assets/images/speakers/saquib.png
    role: "Principal Lead AI & Deep Learning"
    affiliation: "Mercedes Benz Tech Innovation"
    col: 4
    linkedin: "https://www.linkedin.com/in/saquib-sarfraz-6395783a/"
    scholar: "https://scholar.google.com/citations?user=4YLsmYIAAAAJ"
    website: "https://ssarfraz.github.io/"
  - name: "Laurens van der Maaten"
    photo: "https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=6GDfcqEAAAAJ&citpid=4"
    role: "Distinguished Research Scientist"
    affiliation: "Meta AI"
    col: 4
    linkedin: "https://www.linkedin.com/in/laurens-van-der-maaten-1255811/"
    scholar: "https://scholar.google.com/citations?hl=de&user=6GDfcqEAAAAJ"
    website: "http://lvdmaaten.github.io/"
  - name: "Brandon Duderstadt"
    photo: "https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=TIapXZQAAAAJ&citpid=3"
    role: "Founder & CEO @ Nomic AI"
    affiliation: "Nomic AI"
    col: 4
    linkedin: "https://www.linkedin.com/in/bstadt/"
    scholar: "https://scholar.google.com/citations?hl=de&user=TIapXZQAAAAJ"
    website: "https://www.nomad.garden/"
  - name: "Marios Koulakis"
    photo: "https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=2k0YV9cAAAAJ&citpid=2"
    role: "Machine Learning Scientist & Researcher"
    affiliation: "DeepHealth"
    col: 6
    linkedin: "https://www.linkedin.com/in/marioskoulakis/"
    scholar: "https://scholar.google.com/citations?hl=de&user=2k0YV9cAAAAJ"
  - name: "Constantin Seibold"
    photo: "https://constantinseibold.github.io/assets/img/profile/linkedin.jpg"
    role: "Research Group Lead"
    affiliation: "University Clinic Heidelberg"
    col: 6
    linkedin: "https://www.linkedin.com/in/constantin-seibold-7669ba250/"
    scholar: "https://scholar.google.com/citations?user=rSuG-f4AAAAJ&hl=de"
    website: "https://constantinseibold.github.io/"

publications:
  - 'Sarfraz, M. Saquib, Sharma V., Stiefelhagen R. "Efficient parameter-free clustering using first neighbor relations". IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2019.'
  - 'Sarfraz, M. Saquib, Murray, N., Sharma, V., Diba, A., Van Gool, L., Stiefelhagen, R. "Temporally-weighted hierarchical clustering for unsupervised action segmentation". IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2021.'
  - 'Sarfraz, M. Saquib, Koulakis, M., Seibold, C., Stiefelhagen, R. (2022). "Hierarchical nearest neighbor graph embedding for efficient dimensionality reduction". IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2022.'
  - 'Van der Maaten, L. and Hinton, G. "Visualizing data using t-SNE". Journal of Machine Learning Research (JMLR) 2008.'
  - 'Van der Maaten, L. "Barnes-Hut-SNE". International Conference on Learning Representations (ICLR) 2013.'
  - 'Van der Maaten, L. "Accelerating t-SNE using Tree-Based Algorithms". Journal of Machine Learning Research (JMLR) 2014.'
  - 'Anand, Y., Nussbaum, Z., Duderstadt, B., Schmidt, B., Mulya, A. "Gpt4all: Training an assistant-style chatbot with large scale data distillation from gpt-3.5-turbo". GitHub 2023.'
  - 'Nussbaum, Z., Morris, J.X., Duderstadt, B., Mulyar, A. "Nomic embed: Training a reproducible long context text embedder". arXiv preprint 2024.'
  - 'Helm, H., Duderstadt, B., Park, Y., Priebe, C. "Tracking the perspectives of interacting language models". Empirical Methods in Natural Language Processing (EMNLP) 2024.'

impressions:
  - image: /assets/images/impressions/cvpr2025/brandon-duderstadt.jpeg
    caption: "Brandon Duderstadt presenting on scaling dimensionality reduction with NOMAD projection"
  - image: /assets/images/impressions/cvpr2025/laurens-van-der-maaten.jpeg
    caption: "Laurens van der Maaten on how to use and not use modern dimension reduction techniques"
  - image: /assets/images/impressions/cvpr2025/saquib-sarfraz.jpeg
    caption: "M. Saquib Sarfraz on clustering and representation learning"

contact: "For further information or inquiries, please contact the organizers via the social links provided in the speakers' section."
---
