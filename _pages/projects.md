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
        <ul>
            <li> Designed an end-to-end neural network-based compression algorithm for 3D Gaussian splats during my internship at Dolby </li>
            <li> Developed techniques to compress spherical harmonic coefficients (~50% size) using inter-frame video coding tools, achieving significant storage and bandwidth efficiency </li>
            <li> Applied hybrid methods combining neural networks and conventional tools, contributing to advanced 3D content compression solutions </li>
        </ul>       
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
    <ul>
        <li> Designed a novel Neural Field architecture for joint audio-video representation using time-stamp coordinates during my summer internship at Dolby </li>
        <li> Implemented model pruning and quantization techniques to optimize the representation, moving beyond modality-specific compression </li>
        <li> Contributed to advancing multi-modal compression techniques for audio-video data </li>
    </ul>
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
        <ul>      
             <li> Designed the first ever task-specific unsupervised image quality estimator correlating image quality with face detection performance using innovative regularization techniques like Dropblocks </li>
             <li> Developed novel evaluation protocols for image quality estimators in face detection and recognition, significantly reducing computational complexity </li>
            <li> Explored masked vision trasnformers as image quality estimators in face detection and recognition </li>
             <li> This work forms an integral part of my Ph.D. thesis, advancing image quality assessment methods for robust computer vision applications </li>
        </ul>
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
        <ul>
            <li> Assessed the impact of video compression on deep learning models for tasks like pedestrian detection, face detection, and face recognition during my Ph.D., funded by Ford Motor Corp. </li>
            <li>Developed a task-aware frame partitioning algorithm for video encoders (e.g., HM and VVC) using edge-based deep learning models like MobileNets to optimize bit allocation for critical regions </li>
            <li> Achieved 6% bit-rate and 15% encoding time savings while maintaining video analytics performance under compression </li>
        </ul>
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
        <ul> 
<li>Investigated the capability of video codecs like HEVC to encode neural network intermediate features during a summer project at Purdue </li>
<li>Assessed the feasibility of splitting neural networks for efficient encoding and transmission of intermediate features </li>            
<li>Explored Autoencoder models for Video Coding for Machines and Scalable Video Coding, advancing research in machine-centric video compression </li>
</ul>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/etoe.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Dataset Curation and Systematic Evaluation of End-to-end Face Analytics</h3>
        <span class="timeline">Jan 2020 - May 2021</span>
        </div>
        <ul> 
<li> Designed an end-to-end in-vehicle face analytics system for sequential face detection and recognition during the early years of my Ph.D., funded by Ford Motor Corp </li>
<li> Developed a data collection system to capture diverse in-vehicle face data across multiple camera modalities, angles, and lighting conditions </li>
<li> Curated a balanced dataset preserving original properties and capturing task interdependence, enabling systematic evaluation of face analytics systems </li>
            <li> Performed a meaningful and interpretable evaluation of an end-to-end face analytics system using the carefully curated data to gain valubale performance insights.</li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/senegal.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Background-Foreground Segmentation for Camera-Trap Images using RobustPCA</h3>
        <span class="timeline">Aug 2019 - Dec 2019</span>
        </div>
        <ul> 
     <li> Developed an unsupervised robust saliency predictor using robust PCA to differentiate background and foreground in camera-trap images during my first research project at Purdue </li>
<li> Achieved performance comparable to learning-based models (e.g., R3-Net) without requiring training </li>
<li> Applied the system to track animal movements, calculate population densities, and analyze habitual patterns in wildlife activities </li>
        </ul>
    </div>
</div>


<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/ddos.png" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>EdgeDetect - A lightweight framework to detect DDoS attacks on Edge nodes</h3>
        <span class="timeline">July 2018 - Aug 2019</span>
        </div>
        <ul> 
  <li> Built a system for detecting DDoS attacks on edge devices using Recurrent Neural Networks (RNNs) under the supervision of Dr. Reshmi Mitra at the Indian Institute of Science </li>
<li> Achieved state-of-the-art performance on the UNSW 2015 dataset with a minimal model architecture optimized for edge devices </li>
        </ul>
    </div>
</div>

<div class="project0">
    <div class="image-container0">
        {% include figure.liquid loading="eager" path="assets/img/traffic.jpeg" style="width: 300px; height: 300px;"  %}
    </div>
    <div class="project-details0">
        <div class="heading">
        <h3>Traffic Analytics Architecture and Dataset for Indian Roads using a Monocular Surveillance Camera Network</h3>
        <span class="timeline">April 2018 - Aug 2019</span>
        </div>
        <ul>
<li> Designed a real-time front-end web server system for delivering live RTMP and HLS video streams with features like content sharing, routing, congestion management, and load balancing under the supervision of Dr. Abhay Sharma at the Indian Institute of Science </li>
<li> Collaborated on traffic analytics solutions, including vehicle counting, license plate detection, speed computation, and queue-length estimation </li>
<li> Successfully deployed the full framework in Electronic City, Bangalore, India </li>
        </ul>
    </div>
</div>


