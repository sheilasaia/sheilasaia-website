+++
title = "Improved Accuracy of Watershed-Scale General Circulation Model Runoff Using Deep Neural Networks"
date = 2019-12-31T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["JS Rice", "**SM Saia**", "RE Emanuel"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Journal of Advances in Modeling Earth Systems (in prep), EarthArXiv (preprint)*"
publication_short = "*JAMES (in prep), EarthArxiv (preprint)*"

# Abstract and optional shortened version.
abstract = "Projecting impacts of climate change on water resources is a vital research task, and general circulation models (GCMs) are important tools for this work. However, the spatial resolution of downscaled GCMs makes them difficult to apply to non-grid conforming scales relevant to water resources management: individual watersheds. Machine learning techniques like deep neural networks (DNNs) may address this issue. Here we use a DNN to predict monthly watershed-scale runoff (i.e., stream discharge divided by watershed area) from monthly gridded and downscaled Coupled Model Intercomparison Project Phase 5 (CMIP5) GCM hydroclimatic fluxes (i.e., precipitation, evapotranspiration, and temperature). We used hydroclimatic fluxes, biotic, and abiotic characteristics from 2,731 watersheds in the conterminous United States to train and test a DNN that can predict watershed-scale runoff. The DNN described 93% (Pearson’s correlation coefficient = 0.962) of the variability in observed runoff and was temporally and spatially robust. The median absolute error (MAE) of DNN predictions was approximately 25 percentage points lower than that of gridded, downscaled GCM runoff or monthly normal runoff (i.e., 30-year average of runoff observations at the watershed-outlet). DNN monthly runoff predictions had the lowest MAE of all the grid-to-watershed-scale conversion approaches we tested, including: linear ridge regression, support vector machines, extreme gradient boosting, and artificial neural networks. We demonstrated why using DNNs to convert gridded GCM hydroclimatic fluxes to watershed-scales is relevant to water resources research and management. We also provided a methods guide for hydrologists interested in implementing machine learning techniques."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
projects = ["streamflow-ml-project"]

# Links (optional).
url_pdf = ""
url_preprint = "https://eartharxiv.org/awqjg/"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++