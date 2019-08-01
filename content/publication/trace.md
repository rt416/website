+++
#abstract = "The predictive performance of supervised learning algorithms depends on the quality of labels. In a typical label collection process, multiple annotators provide subjective noisy estimates of the truth under the influence of their varying skill-levels and biases. Blindly treating these noisy labels as the ground truth limits the accuracy of learning algorithms in the presence of strong disagreement. This problem is critical for applications in domains such as medical imaging where both the annotation cost and inter-observer variability are high. In this work, we present a method for simultaneously learning the individual annotator model and the underlying true label distribution, using only noisy observations. Each annotator is modeled by a confusion matrix that is jointly estimated along with the classifier predictions. We propose to add a regularization term to the loss function that encourages convergence to the true annotator confusion matrix. We provide a theoretical argument as to how the regularization is essential to our approach both for the case of single annotator and multiple annotators. Despite the simplicity of the idea, experiments on image classification tasks with both simulated and real labels show that our method either outperforms or performs on par with the state-of-the-art methods and is capable of estimating the skills of annotators even with a single label available per image."
abstract = "" 
abstract_short = " "
authors = ["Ryutaro Tanno", "Ardavan Saeedi", "Swami Sankaranarayanan", "Daniel C. Alexander", "Nathan Silberman"]
date = "2019-02-10"
image = "./../images/trace.png"
image_preview = "./../images/trace.png"
math = false
publication = "In *CVPR* "
selected = true
title = "Learning From Noisy Labels By Regularized Estimation Of Annotator Confusion"
publication_types = ["1"]
url_code = "pdf/trace_codes.pdf"
url_dataset = ""
url_pdf = "pdf/tanno_trace_2019.pdf"

[[url_custom]]
name = "Slides"
url = "pdf/trace_slides.pdf"
#url_project = ""

[[url_custom]]
name = "Link"
url="https://arxiv.org/abs/1902.03680"

[[url_custom]]
name = "Video"
url = "https://youtu.be/fyKoxmy2ouA"

+++
