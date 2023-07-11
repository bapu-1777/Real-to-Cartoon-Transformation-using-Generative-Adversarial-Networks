# Real-to-Cartoon-Transformation-using-Generative-Adversarial-Networks

This project is part of the course CSE 6367: Computer Vision (Section 001).

**Contributors:**
- Nitya Parikh
- Mayank Vekariya

## Problem Description

The project aims to design an automated system capable of converting real-world images and videos into their cartoon equivalents. Currently, this process requires complex computer graphics skills and substantial labor. To simplify the process, this project will utilize Generative Adversarial Networks (GANs), particularly CartoonGAN, to perform the transformation. CartoonGAN leverages both content and adversarial loss functions to produce high-quality, sharp, and clear cartoonized images. The intent is to extend this functionality to process not only still images but also videos and live video feeds.

## Related Work

The cartoonization of images and videos is a dynamic research field with various techniques proposed over the years. Traditional methods relied heavily on intricate computer graphics, which were labor-intensive and required specialized skills. However, with the advent of deep learning, Generative Adversarial Networks (GANs) emerged as efficient tools for image-to-image translations. Noteworthy models in this domain include CycleGAN, CartoonGAN, White-box Cartoonize, and AnimeGAN. However, many of these models lack the flexibility to adapt to different cartoon styles without specific training. This project aims to address these limitations by offering a more adaptable solution.

## Datasets (not sure)

For training the GAN, we will utilize the Cartoon Set, which includes 100,000 randomly generated 2D cartoon avatar images. The dataset spans ten artwork categories, four color categories, and four proportion categories. Images will be read, converted to JPG format, resized, normalized, and stored as binary files to enhance efficiency. TensorFlow's `tf.data.Dataset` will be used for in-memory handling of images.

## Timeline

The project will span approximately 1.5 months, with the following tentative milestones:

- Week 1-2: Understanding and reading relevant research papers.
- Week 3-4: Experimenting with different methods for image, video, and live video conversion into cartoons.
- Week 5: Deployment of the application on Amazon Web Services with a web-based UI.
- Week 6: Testing, debugging, and final refinements.

## Final Deliverables

The primary objective is to deliver a web-based application where users can upload images or videos, or use their live camera feed, and convert the input into cartoon-style images or videos. However, due to the complexity of the task and the project's limited timeline, the complete conversion of live videos might not be fully realized. Hence, the primary deliverable at the end of the project will be a Python-based application capable of converting images and pre-recorded videos into cartoons.

## References

The project will reference a diverse range of resources, including research papers, GitHub repositories, and online articles. Here are some of the important and relevant links:

- Research paper links
  - [Paper 1](https://www.irjet.net/archives/V7/i1/IRJET-V7I1376.pdf)
  - [Paper 2](https://www.irjet.net/archives/V8/i4/PIT/ICIETET-45.pdf)
  - [Paper 3](https://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_CartoonGAN_Generative_Adversarial_CVPR_2018_paper.pdf)
  - [Paper 4](https://www.academia.edu/44055638/IRJET_Transformation_of_Realistic_Images_and_Videos_into_Cartoon_Images_and_Video_using_GAN)
  - [Paper 5](https://www.sciencedirect.com/science/article/pii/S004579062200790X)
  - [Paper 6](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/GAN-based_Multi-Style_Photo_Cartoonization.pdf)
  - [Paper 7](https://arxiv.org/abs/1811.00222)

- GitHub page links
  - [Cartoonify](https://github.com/ahmedbesbes/cartoonify)
  - [Cartoon-GAN](https://github.com/FilipAndersson245/cartoon-gan)

- YouTube and some Google links
  - [YouTube Video 1](https://www.youtube.com/watch?v=R86zP6Hf4Hk)
  - [Article 1](https://towardsdatascience.com/how-to-build-and-deploy-a-serverless-machine-learning-app-on-aws-1468cf7ef5cb)
  - [Article 2](https://www.techrxiv.org/articles/preprint/IMAGE-TO-IMAGE_TRANSLATION_FOR_ANIMATION_USING_OPENCV_AND_GAN/21770039/1)
  - [Article 3](https://medium.com/what-is-artificial-intelligence/this-ai-can-cartoonize-any-picture-or-video-you-feed-it-paper-introduction-results-examples-d7e400d8c3e8)
  - [Article 4](https://www.andrew.cmu.edu/course/16-726/projects/cliveg/project/)

Please refer to these resources for more detailed information on implementing GANs and related technologies.

---

This `README.md` file provides a brief overview of the project, its objectives, milestones, and references to important resources. It serves as a central document for anyone interested in understanding the project and its development process.
