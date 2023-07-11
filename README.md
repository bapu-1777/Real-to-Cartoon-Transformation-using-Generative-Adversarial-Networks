# Real-to-Cartoon-Transformation-using-Generative-Adversarial-Networks

Project name/title - “Real-to-Cartoon Transformation using Generative Adversarial Networks”
Course/Subject - CSE 6367: Computer Vision
Section - 001
—--------------------------------------------------------------------------------------------------------------------
NAME - Nitya Parikh
UTA ID - 1002053645
NET ID - nxp3645
—---------------------------------------------------------------------------------------------------------------------
NAME - Mayank Vekariya
UTA ID - 1002078999
NET ID - mxv8999
—---------------------------------------------------------------------------------------------------------------------
Problem Description:
The project aims to design an automated system capable of converting real-world
images and videos into their cartoon equivalents. Currently, this process requires
complex computer graphics skills and substantial labor. To simplify the process, this
project will utilize Generative Adversarial Networks (GANs), particularly CartoonGAN, to
perform the transformation. CartoonGAN leverages both content and adversarial loss
functions to produce high-quality, sharp, and clear cartoonized images. The intent is to
extend this functionality to process not only still images but also videos and live video
feeds.
Related Work:
The cartoonization of images and videos is a dynamic research field with various
techniques proposed over the years. Traditional methods relied heavily on intricate
computer graphics, which were labor-intensive and required specialized skills. However,
with the advent of deep learning, Generative Adversarial Networks (GANs) emerged as
efficient tools for image-to-image translations. Noteworthy models in this domain include
CycleGAN, CartoonGAN, White-box Cartoonize, and AnimeGAN. However, many of
these models lack the flexibility to adapt to different cartoon styles without specific
training. This project aims to address these limitations by offering a more adaptable
solution.
Datasets(not sure):
The Cartoon Set will be used to train the GAN. The Cartoon Set includes 100,000
randomly generated 2D cartoon avatar images. The dataset spans ten artwork
categories, four color categories, and four proportion categories. Images will be read,
converted to JPG format, resized, normalized, and stored as binary files to enhance
efficiency. TensorFlow's tf.data.Dataset will be used for in-memory handling of images.
Timeline:
The project will span across approximately 1.5 months, with the following tentative milestones:
Week 1-2: Understanding and reading relevant research papers.
Week 3-4: Experimenting with different methods for image, video, and live video
conversion into cartoons.
Week 5: Deployment of the application on Amazon Web Services with a web-based UI.
Week 6: Testing, debugging, and final refinements.
Final Deliverables:
The primary objective is to deliver a web-based application where users can upload
images or videos, or use their live camera feed, and convert the input into cartoon-style
images or videos. However, due to the complexity of the task and the project's limited
timeline, the complete conversion of live videos might not be fully realized. Hence, the
primary deliverable at the end of the project will be a Python-based application capable
of converting images and pre-recorded videos into cartoons.
References:
The project will reference a diverse range of resources. These include Github
repositories that provide relevant code examples, academic papers discussing the
details of implementing GANs and related technologies, and blog posts offering practical
insights into the development process. These resources will serve as a valuable guide
throughout the project and contribute significantly to its successful completion.
Important and most relevant links
Research paper links
https://www.irjet.net/archives/V7/i1/IRJET-V7I1376.pdf
https://www.irjet.net/archives/V8/i4/PIT/ICIETET-45.pdf
https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_G
enerative_Adversarial_CVPR_2018_paper.pdf
https://www.academia.edu/44055638/IRJET_Transformation_of_Realistic_Image
s_and_Videos_into_Cartoon_Images_and_Video_using_GAN
https://www.sciencedirect.com/science/article/pii/S004579062200790X
https://cg.cs.tsinghua.edu.cn/people/~Yongjin/GAN-based_Multi-Style_Photo_Ca
rtoonization.pdf
https://arxiv.org/abs/1811.00222
GitHub page link
https://github.com/ahmedbesbes/cartoonify
https://github.com/FilipAndersson245/cartoon-gan
YouTube and some Google links
https://www.youtube.com/watch?v=R86zP6Hf4Hk
https://towardsdatascience.com/how-to-build-and-deploy-a-serverless-machine-le
arning-app-on-aws-1468cf7ef5cb
https://www.techrxiv.org/articles/preprint/IMAGE-TO-IMAGE_TRANSLATION_FO
R_ANIMATION_USING_OPENCV_AND_GAN/21770039/1
https://medium.com/what-is-artificial-intelligence/this-ai-can-cartoonize-any-pictur
e-or-video-you-feed-it-paper-introduction-results-examples-d7e400d8c3e8
https://www.andrew.cmu.edu/course/16-726/projects/cliveg/project/
Not that much important links
Research paper links
GitHub page link
https://github.com/nashory/gans-awesome-applications
https://github.com/ashishpatel26/500-AI-Machine-learning-Deep-learning-Comput
er-vision-NLP-Projects-with-code
https://machinelearningprojects.net/opencv-projects/
https://github.com/eladrich/pixel2style2pixel
https://github.com/FilipAndersson245/cartoon-gan
https://github.com/NVlabs/instant-ngp
https://github.com/filipecalegario/awesome-generative-ai
YouTube and some Google links
https://towardsdatascience.com/avatargan-generate-cartoon-images-using-gan-1
ffe7d33cfbb
https://www.geeksforgeeks.org/generative-adversarial-network-gan/
https://aihalapathirana.medium.com/generative-adversarial-networks-for-anime-f
ace-generation-pytorch-1b4037930e21
