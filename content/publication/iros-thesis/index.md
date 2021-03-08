---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Map to Map: From SLAM to CAD Maps and
Back Using Generative Models"
authors: [Rema Daher, Theodor Chakhachio, Daniel Asmar]
date: 2020-12-31T12:41:31+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-31T12:41:31+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""
abstract: "Simultaneous Localization and Mapping (SLAM) has been mostly used for the purpose of localization. Recently, more research has been focused on the quality of generated SLAM maps and their uses. Robotic maps can be utilized in various applications such as intelligent transportation systems, Augmented and Virtual Reality (AR/VR), and search and rescue. In these applications, the accuracy and precision of the map can be very important. Today robotic maps have several sources of errors and deformations. To resolve these anomalies, a necessary analysis and modeling of these maps is in order. In this work, a parametric model is first formulated that represents the local deformations in the map. In addition to that, a generative adversarial network (GAN) is also used to learn these deformations through training the dataset generated in this thesis. Both methods generated promising results. The parametric approach offered multiple possible outputs with user defined trajectories, didn't remove important structural elements, didn't exaggerate the SLAM errors, and deformed the unoccupied cells in a more geometric manner as opposed to the performance of the machine learning method. However, the machine learning approach modeled the simulated SLAM map's sudden brokenness, large room shifts, removal of walls, and the shrinkage and expansion of rooms better than the parametric approach did. On a more general note, both methods act as a more efficient alternative to real time simulations, which are used for tasks such as navigation experiments, employee field training, and video-gaming. Finally, more interesting is the inverse problem, where the network is trained to generate correct CAD maps from SLAM maps. This can be utilized to automatically enhance SLAM maps in real time and pave the way to the improvement of localization by it's reliance on a more accurate map. As for the results, the qualitative results showed improvement in aspects such as straightening walls, removal of noise, addition of missed walls/objects, and correction of wall positions of the SLAM maps to resemble CAD maps. Quantitatively, 75% of the test map structures were improved and the other 25% did not portray or learn the shrinkage and expansion of maps perfectly. Finally, the machine learning models, whether in generating SLAM maps or CAD maps, offer more promise in the future with the expansion of the dataset, addition of new features, use of feature analysis tools, and use of different architectures, which might induce a deeper learning; specifically in the task of generating SLAM maps, where there are possibly missing features in the parametric model approach."

# Summary. An optional shortened abstract.
summary: ""

tags: [SLAM,Machine Learning]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://theodorchakhachiro.files.wordpress.com/2021/03/iros_2021_thesis_paper-2.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: https://scholarworks.aub.edu.lb/handle/10938/22162
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
