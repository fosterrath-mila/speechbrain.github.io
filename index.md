---
layout: default
---


# The project

**SpeechBrain** is an **open-source** and **all-in-one** speech toolkit
relying on [PyTorch](https://pytorch.org).

The goal is to create a *single*, *flexible*, and *user-friendly* toolkit that can be used to easily develop state-of-the-art speech technologies, including systems for **speech recognition** (both end-to-end and HMM-DNN), **speaker recognition**, **speech separation**, **multi-microphone signal processing** (e.g, beamforming), **self-supervised and unsupervised learning**, **speech contamination / augmentation**,  and many others. The toolkit will be designed to be a **stand-alone framework**, but simple interfaces with well-known toolkits, such as [Kaldi](http://kaldi-asr.org) will also be implemented.

**SpeechBrain** is currently **under development** and has been announced in September 2019. A first alpha version will be available in the first semester of 2021.

[See a short introductory video on the SpeechBrain project](https://youtu.be/XETiKbN9ojE)

The code for this project can be found at https://github.com/speechbrain .


# Why SpeechBrain?
Speech processing toolkits have gained popularity in the last years. For automatic speech recognition (ASR) purposes, for instance, [Kaldi](http://kaldi-asr.org) is an established framework. Some other ASR toolkits have been recently developed using the Python language such as [PyTorch-Kaldi](https://github.com/mravanelli/pytorch-kaldi), [PyKaldi](https://github.com/pykaldi/pykaldi), and [ESPnet](https://github.com/espnet/espnet). Beyond speech recognition, a variety of other solutions have been developed for speech-related applications, such as speech separation, speech enhancement, speaker recognition, and language model training.

Even though many of these frameworks could be very helpful for the specific task for which they are designed, our experience in the field suggests that having a *single*, *efficient*, and *flexible* toolkit can significantly **speed up research and development** of speech and audio processing techniques. Indeed, it is significantly easier to familiarize oneself with a single toolkit than to learn several different frameworks. Moreover, the use of a **single platform** for different speech and audio applications makes it more natural to develop **multi-task systems** that jointly solve different problems. It is also easier to build a strong and fruitful community when considering a unique and self-contained framework.

# Why PyTorch?
To ensure the needed *flexibility* and the *user-friendliness* of our system, we think that our platform must be built on the top of PyTorch for the following reasons:  
- PyTorch is a well-designed, flexible, popular, and well-documented toolkit with a very large community.
- Most speech applications rely on deep learning and signal processing techniques, that can be naturally implemented in PyTorch.
- Processing steps are performed either on GPUs or CPUs.
- It is feasible to design end-to-end differentiable systems, where the gradient can potentially flow through all the different parts of the architecture, including parts solving different audio and speech tasks (*e.g. joint training, multi-task learning, cooperative learning).

# Toolkits
During the project, we plan to collaborate with the PyTorch Audio team of Facebook and with NVIDIA, that has recently developed the Neural Modules toolkit (Nemo), which provides flexibility and modularity to accelerate speech applications.

# How to collaborate
A strong toolkit needs a strong community. While a core team will be dedicated to develop and maintain the core functionalities of SpeechBrain, we need the help of the entire community to extend this ambitious project to numerous and various applications. Feel free to contact us, if you are interested to contribute.

# Join us!
Thanks to our [sponsors](#Sponsors), we are hiring talented interns (3-6 months internships) that will work at Mila (Montréal) with the core development team. The ideal candidate is a PhD student with a strong experience in both PyTorch and speech technologies. Send us your CV if you are interested in this opportunity!

# Contact us
If you are interested to collaborate or sponsor us, or if you simply want to hear more about this project, please **contact us at *speechbrainproject@gmail.com***.

# SpeechBrain and Social Good
The development and use of SpeechBrain technologies are parts of a policy of concern for AI for the “social good”. Therefore, all partners, collaborators and participants declare having read the [Montreal Declaration for a responsible development of AI](https://www.montrealdeclaration-responsibleai.com), adhere to these principles and implement them as part of the SpeechBrain project. Unfortunately, and as SpeechBrain is a completely open source project, users of the toolkit do not have any legal obligation to respect this declaration. However, the initial SpeechBrain team started this project with the goal of impacting positively the civil society.


# Sponsors

<div class="row">

<div class="column3">
<div class="card">
<img src="https://speechbrain.github.io/assets/logo_mila_small.png" style="width:200px;" class="team_pic" />
<div class="container">
</div>
</div>
</div>

<div class="column3">
<div class="card">
<img src="https://speechbrain.github.io/assets/logo_nvidia.png" style="width:250px" class="team_pic" />
<div class="container">
</div>
</div>
</div>


<div class="column3">
<div class="card">
<img src="https://speechbrain.github.io/assets/logo_dolby.png" style="width:250px;" class="team_pic" />
<div class="container">
</div>
</div>
</div>
</div>

<div class="row">

<div class="column2">
<div class="card">
<img src="https://speechbrain.github.io/assets/samsung_official.png" style="width:300px; " class="team_pic"  />
<div class="container">
</div>
</div>
</div>

<div class="column2">
<div class="card">
<img src="https://speechbrain.github.io/assets/logo_nuance.png" style="width:300px" class="team_pic" />
<div class="container">
</div>
</div>
</div>

</div>



# Partner Institutions

Partner Institutions are organizations that have accepted to collaborate within SpeechBrain by dedicating important human or hardware resources. They are involved in the decision process by participating in weekly organized meetings. If interested in becoming the next official partner, please **contact us at *speechbrainproject@gmail.com***.

<div class="row">

<div class="column2">
<div class="card">
<div class="container">
<img src="https://speechbrain.github.io/assets/logo_lia2.png" style="width:200px" class="team_pic" />
</div>
</div>
</div>

<div class="column2">
<div class="card">
<div class="container">
<img src="https://speechbrain.github.io/assets/logo_sherbrooke.jpg" style="width:300px" class="team_pic" />
</div>
</div>
</div>

<div class="column2">
<div class="card">
<div class="container">
<img src="https://speechbrain.github.io/assets/logo_bioASP.jpg" style="width:300px" class="team_pic" />
</div>
</div>
</div>

</div>

# Collaborators
Collaborators are actors interested in contributing to the project. It could be individual or small groups of researchers, companies, or anyone interested to develop an important module of SpeechBrain. Active collaborators are invited to the meetings to better synchronize their contributions.

- University of Cambridge (UK)
- LIUM - Le Mans University (FR)
- Institut de Recherche en Informatique de Toulouse (IRIT, FR)
- LINAGORA (FR)
- PyTorch Team
- IBM Research
- Fluent.ai
- Avignon University (FR)
- Aalto University (FI)
- Indian Institute of Technology Madras (IN)
- The Ohio State University (USA)
<!-- <img src="../assets/logo_oxford.png" alt="OX" style="width:125px" />
<img src="https://speechbrain.github.io/assets/logo_lia2.png" style="width:200px" />
<img src="https://speechbrain.github.io/assets/lium_logo_official.png" style="width:250px" />
<img src="https://speechbrain.github.io/assets/logo_pytorch.png" style="width:250px; margin-right:25px;" />
<img src="https://speechbrain.github.io/assets/logo_ibm.png" style="width:300px; margin-right:25px;" />
<img src="https://speechbrain.github.io/assets/logo_fluent.png" style="width:200px" /> -->
