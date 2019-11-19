+++
date = 2019-12-01T00:00:00  # Schedule page publish date.

title = "Improved Accuracy of Watershed-Scale General Circulation Model Runoff Using Deep Neural Networks (Poster #GC43D-1361)"
time_start = 2019-12-12T13:40:00
time_end = 2019-12-12T18:00:00
abstract = ""
abstract_short = ""
event = "American Geophysical Union (AGU) Fall Meeting"
event_url = ""
location = "San Francisco, California, USA"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
# projects = ["nc-sociohydro-project"] # this isn't working...

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
#image = "headers/bubbles-wide.jpg"
#caption = "My caption :smile:"

+++

## Abstract:</br>
Projecting future climate change impacts on water resources is a vital research task and general circulation models (GCMs) help researchers achieve this goal. However, the spatial resolution of downscaled GCMs (e.g., 1.4° grid) makes them difficult to apply to non-grid conforming scales relevant to water resources management: individual watersheds. Machine learning techniques such as deep neural networks (DNNs) may address this issue by downscaling GCM data without a priori specification of complex hydrologic processes in a watershed. Here, we use a DNN to predict monthly watershed-scale runoff (i.e., stream discharge divided by watershed area) from monthly, gridded, downscaled, Coupled Model Intercomparison Project Phase 5 GCM hydrologic fluxes (i.e., precipitation, evapotranspiration, and temperature). We trained the DNN on a subset of observed hydrologic fluxes and watershed characteristics from 2,731 watersheds in the continental United States and tested its ability to predict observed runoff using the remaining data. The DNN described 94% of the variability in observed runoff and was spatially and temporally robust. DNN runoff predictions were nearly twice as accurate as raw, monthly, gridded, downscaled GCM runoff and had the lowest mean absolute error of other grid-to-watershed-scale conversion techniques, including: long-term monthly mean climatology, linear least squares, lasso, support vector machine, extreme gradient boosting, and simple artificial neural network approaches. This study serves as a guide to hydrologists interested in implementing machine learning techniques and also demonstrates how DNNs can be used to convert gridded GCM hydrologic fluxes to scales more relevant to water resources research and management.

[Click here to view my AGU abstract. ](https://agu.confex.com/agu/fm19/meetingapp.cgi/Paper/499522)