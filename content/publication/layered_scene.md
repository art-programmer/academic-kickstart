+++
title = "Layered Scene Decomposition via the Occlusion-CRF"
# date = "2013-07-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["[Chen Liu](http://www.chenliunet.com), [Pushmeet Kohli](https://sites.google.com/site/pushmeet/)", "[Yasutaka Furukawa](http://www.cs.sfu.ca/~furukawa)"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Publication name and optional abbreviated version.

publication = "In *Computer Vision and Pattern Recognition*."
publication_short = "In *CVPR*"

# Abstract and optional shortened version.
abstract = "This paper addresses the challenging problem of perceiving the hidden or occluded geometry of the scene depicted in any given RGBD image. Unlike other image labeling problems such as image segmentation where each pixel needs to be assigned a single label, layered decomposition requires us to assign multiple labels to pixels. We propose a novel 'Occlusion-CRF' model that allows for the integration of sophisticated priors to regularize the solution space and enables the automatic inference of the layer decomposition. We use a generalization of the Fusion Move algorithm to perform Maximum a Posterior (MAP) inference on the model that can handle the large label sets needed to represent multiple surface assignments to each pixel. We have evaluated the proposed model and the inference algorithm on many RGBD images of cluttered indoor scenes. Our experiments show that not only is our model able to explain occlusions but it also enables automatic inpainting of occluded/invisible surfaces."

# # abstract_short = "A mobile visual clothing search system is presented whereby a smart phone user can either choose a social networking image or capture a new photo of a person wearing clothing of interest and search for similar clothing in a large cloud-based ecommerce database. The phone's GPS location is used to re-rank results by retail store location, to inform the user of local stores where similar clothing items can be tried on."

# Featured image thumbnail (optional)
image_preview = "img/layered_scene.png"

# Is this a selected publication? (true/false)
selected = false

# # Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# #projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://openaccess.thecvf.com/content_cvpr_2016/papers/Liu_Layered_Scene_Decomposition_CVPR_2016_paper.pdf"
#url_preprint = ""
url_code = "https://github.com/art-programmer/LayeredSceneDecomposition"
#url_dataset = "#"
#url_video = "#"
#url_poster = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = false

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = "layered_scene/teaser.png"
caption = "Our Occlusion-CRF model decompose a scene into layers of segmented depthmaps."

+++

# More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code.+++

