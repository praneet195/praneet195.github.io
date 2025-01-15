---
layout: page
permalink: /projects/
title: Projects
nav: true
nav_order: 3
---

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/gaussians.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Compression of 3D/4D Gaussian Splats</h3>
        <span class="timeline">Sep 2024 - Dec 2024</span>
        </div>
        <p>This project was part of my fall internship at Dolby. During my internship, I designed an end-to-end neural network based compression algorithm for 3D gaussian splats. I also worked on compressing spherical harmonic coefficients of 3D gaussian splats (occupy ~50% size) using conventional inter-frame video coding tools.</p>
    </div>
</div>



<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/nerva.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Joint Multi-modal Neural Field Representations for Audio and Video</h3>
        <span class="timeline">May 2023 - Aug 2023</span>
        </div>
        <p> I worked on this project during my summer internship at Dolby. Here, I designed a novel Neural Field architecture for joint representation of audio + video data using time-stamp coordinates. I also worked on model pruning and quantization techniques for the novel representation, shifting focus from modality-specific (audio or video) compression.</p>
    </div>
</div>



<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/iqa.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Task Aware Image Quality Estimation for End-to-end Face Analytics</h3>
        <span class="timeline">Jan 2023 - May 2024</span>
        </div>
        <p> This project is an intergral part of my Ph.D. thesis. In this work, I designed novel task-specific Unsupervised Image Quality Estimators that correlate image quality and face detection performance through the clever utilization of regularization layers like Dropblocks to measure image robustness. I also developed new evaluation protocols for image quality estimators in face detection and recognition domains that reduced evaluation computational complexity.</p>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/taqt.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Task Aware Video Compression using Lightweight Edge-specific Neural Networks</h3>
        <span class="timeline">May 2021 - May 2022</span>
        </div>
        <p> I worked on this project during my Ph.D. while being funded by Ford Motor Corp. During this time, we first assessed the impact of video compression on the performance of deep learning models used for computer vision tasks like pedestrian detection, face detection, and face recognition. Using this knowledge, I developed a task-aware frame partitioning procedure for video encoders like HM and VVC, leveraging edge-based deep learning models like MobileNets that guide existing video encoders to intelligently allocate bits to regions important for computer vision tasks. This algorithms realized 6% bit-rate and 15% encoding time savings while maintaining video analytics performance under compression.</p>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/nncomp.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Lightweight Compression of Intermediate Neural Network Features (Video Coding for Machines)</h3>
        <span class="timeline">May 2021 - Aug 2021</span>
        </div>
        <p> This was a fun summer project that I worked on at Purdue. In this project, I investigated the capability of existing video codecs like HEVC to encode neural network intermediate features. I also assessed the feasibility of splitting neural networks for effective encoding and transmission of intermediate features. Finally, I explored the application of Autoencoder models for Video Coding for Machines and Scalable Video Coding. 
</p>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/etoe.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Dataset Curation and Systematic Evaluation of End-to-end Face Analytics</h3>
        <span class="timeline">May 2021 - Aug 2021</span>
        </div>
        <p> I worked on this research topic during the early years of my Ph.D while being funded by Ford Motor Corp. Here, I designed an end-to-end face analytics system deployed inside a vehicle that performs sequential face detection and recognition. Next, I utilized a data collection system to capture faces inside a vehicle across multiple camera modalities, camera angles, and lighting conditions in order to create a practical diverse dataset. From this large data, I curated a practically usable dataset for the systematic evaluation of the end-to-end face analytics system. The curated dataset was balanced, had all the properties of the original dataset, and captured the interdependence between tasks such as face detection and recognition which is typically ignored in face datasets. 
</p>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/senegal.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Background-Foreground Segmentation for Camera-Trap Images using RobustPCA</h3>
        <span class="timeline">May 2021 - Aug 2021</span>
        </div>
        <p> This was my first research project at Purdue. In this project, I developed an unsupervised robust saliency predictor using robust PCA, which aids in differentiating between background and foreground in camera-trap images. This method eliminates the need for training, while offering performance similar to learning models such as R3-Net. The system has been employed to and track animal movements, calculate population densities, and identify habitual patterns in animal activities.
</p>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/ddos.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>EdgeDetect - A lightweight framework to detect DDoS attacks on Edge nodes</h3>
        <span class="timeline">May 2021 - Aug 2021</span>
        </div>
        <p> I worked on this topic under the supervision of Dr. Reshmi Mitra when I was at the Indian Institute of Scince. Here, I built a unique system to detect DDoS attacks on edge devices with the application of Recurrent Neural Networks (RNNs). The system accomplished state-of-the-art performance on the UNSW 2015 dataset with the advantage of maintaining minimal model architecture suitable for edge devices.
</p>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/traffic.jpeg" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Traffic Analytics Architecture and Dataset for Indian Roads using a Monocular Surveillance Camera Network</h3>
        <span class="timeline">May 2021 - Aug 2021</span>
        </div>
        <p> This project was undertaken at the Indian Institute of Scince under the supervision of Dr. Abhay Sharma. In this project, I designed a real-time front-end Web Server System that delivers live RTMP and HLS video streams with integrated features such as content sharing, discovering, routing, congestion managing, and load balancing.. I also colloborated on solutions tackling traffic analytics such as vehicle count, detection of license-plates, speed computation, and estimation of queue-length. The full framework has been successfully installed and is operational in Electronic City, Bangalore, India.
</p>
    </div>
</div>


