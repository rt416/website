+++
abstract = "The performance of multi-task learning in Convolutional Neural Networks (CNNs) hinges on the design of feature sharing between tasks within the architecture. The number of possible sharing patterns are combinatorial in the depth of the network and the number of tasks, and thus hand-crafting an architecture, purely based on the human intuitions of task relationships can be time-consuming and suboptimal. In this paper, we present a probabilistic approach to learning task-specific and shared representations in CNNs for multi-task learning. Specifically, we propose “stochastic filter groups” (SFG), a mechanism to assign convolution kernels in each layer to “specialist” or “generalist” groups, which are specific to or shared across different tasks, respectively. The SFG modules determine the connectivity between layers and the structures of task-specific and shared representations in the network. We employ variational inference to learn the posterior distribution over the possible grouping of kernels and network parameters. Experiments demonstrate that the proposed method generalises across multiple tasks and shows improved performance over baseline methods." 
abstract_short = " "
authors = ["Felix J.S. Bragman&ast;", "Ryutaro Tanno&ast;", "Sebastien Ourselin", "Daniel C. Alexander", "M. Jorge Cardoso"]
date = "2019-07-22"
image = "./../images/sfg.png"
image_preview = "./../images/sfg.png"
math = false
publication = "*Preprint*: accepted at ICCV as Oral (top ~4%), &ast; equal contributions"
selected = true
title = "Stochastic Filter Groups for Multi-Task CNNs: Learning Specialist and Generalist Convolution Kernels"
publication_types = ["1"]
url_dataset = ""
url_pdf = "pdf/iccv_camera_ready.pdf"

#[[url_custom]]
#name = "Poster"
#url = "pdf/tanno_miccai_2016_poster.pdf"
#url_project = ""

#[[url_custom]]
#name = "Link"
#url="https://arxiv.org/abs/1902.03680"

#[[url_custom]]
#name = "Video"
#url = "https://youtu.be/fyKoxmy2ouA"

+++
