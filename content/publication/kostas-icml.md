+++

abstract = " We present a novel cost function for semi-supervised learning of neural networks that encourages compact clustering of the latent space to facilitate separation. The key idea is to dynamically create a graph over embeddings of labeled and unlabeled samples of a training batch to capture underlying structure in feature space, and use label propagation to estimate its high and low density regions. We then devise a cost function based on Markov chains on the graph that regularizes the latent space to form a single compact cluster per class, while avoiding to disturb existing clusters during optimization. We evaluate our approach on three benchmarks and compare to state-of-the art with promising results. Our approach combines the benefits of graph-based regularization with efficient, inductive inference, does not require modifications to a network architecture, and can thus be easily applied to existing networks to enable an effective use of unlabeled data."
abstract_short = " "
authors = ["Konstantinos Kamnitsas", "Daniel C. Castro", "Loic Le Folgoc", "Ian Walker", "Ryutaro Tanno", "Daniel Rueckert", "Ben Glocker", "Antonio Criminisi",  "Aditya Nori"]
date = "2018-06-07"
image = "images/biqt_cnn.jpg"
image_preview = ""
math = false
publication = "In *ICML*, Long Oral "
selected = true
title = " Semi-Supervised Learning via Compact Latent Space Clustering"
publication_types = ["1"]
url_dataset = ""
url_pdf = "pdf/kostas_icml_2018.pdf"

[[url_custom]]
name = "Link"
url = "https://arxiv.org/abs/1806.02679"
+++
