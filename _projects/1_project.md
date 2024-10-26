---
layout: page
title: Research Project 3
description: A Study on Mappings in Vision-Language Models  
img: assets/img/Project3.png
importance: 1
category: Research
---

An ongoing undergraduate research project supervised by Dr. Siva Reddy, conducted at Mila - Quebec AI Institute.


<b>Description</b>

A VLM consists of 3 main components: 1) A vision encoder that encodes the input image/video to embeddings, 2) A large language model (LLM) that processes both the input text and the visual embeddings to generate a response, and 3) A mapping that aligns the output embedding space of the vision encoder with the input embedding space of the LLM. 
Two common approaches for the mapping component are the Multi-Layer Perceptron (MLP) and the resampler, each with its own implementation, advantages, and disadvantages. While MLPs are more commonly used in image-processing VLMs, both architectures may result in some loss of visual features during the projection between token spaces. 
This project explores whether resampler-based VLMs can better preserve the temporal and spatial structure of the input in comparison with the MLP-based VLMs. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Project3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>



