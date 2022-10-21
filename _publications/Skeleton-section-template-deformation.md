---
title: "A RBF-based Deformation Method for Fast Adaptation of Finite Element Analysis Models for Structural Design"
collection: publications
permalink: /publication/Skeleton-section-template-deformation
excerpt: 'A collection of works that I did during my PhD study at Dalian University of Technology'
date: 2018-11-01
# venue: 'Computer-Aided Design'
# paperurl: 'https://www.sciencedirect.com/science/article/abs/pii/S0010448515001621'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Finite element mesh deformation with the skeleton-section template

Lei Yang, Baojun Li, Zhangquan Lv, Wenbin Hou, PingHu

### This project aims to provide an intuitive deformation metaphor for slender structures like beams that are widely seen in automobile structure design.

**Abstract:** To develop fast finite element (FE) adaptation methods for simulation-driven design optimization, we propose a radial basis functions (RBF) method with a skeleton-section template to globally and locally deform FE meshes of thin-walled beam structures.
The skeleton-section template is automatically formulated from the input mesh and serves as a hierarchical parameterization for the FE meshes. With this hierarchical parameterization, both the global and the local geometries of a thin-walled beam can be processed in the same framework, which is of importance for designing engineering components. The curve skeleton of the mesh is constructed with Voronoi decomposition, while the cross-sections are extracted from the mesh based on the curve skeleton.
The RBF method is employed to locally and globally deform the mesh model with the cross-sections and the skeleton, respectively. The RBF method solves the spatial deformation field given prescribed deformations at the cross-sections. At the local scale, the user modifies the cross-sections to deform a region of the surface mesh. At the global level, the skeleton is manipulated and its deformation is transferred to all cross-sections to induce the mesh deformation.
In order to handle curved mesh models and attain flexible local deformations, the input mesh is embedded into its skeleton frame field using an anisotropic distance metric. In this way, even strip-like features along arbitrary directions can be created on the mesh model using only a few cross-sections as the deformation handles. In addition, form features can be rigidly preserved at both deformation levels.
Numerical examples demonstrate that intuitive and qualified FE mesh deformations can be obtained with manipulation of the skeleton-section template.

[Project page and codes](https://github.com/LeiYangJustin/LibSST)

[Link to the publisher's version](https://www.sciencedirect.com/science/article/abs/pii/S0010448515001621)


## Skeleton-Section Template Parameterization for Shape Optimization

Ping Hu, Lei Yang, Baojun Li

### This project showcases that it is promising to use the previous work for sampling the design space for crashworthiness design of a structure.

**Abstract:** A technique based on a skeleton-section template for parameterizing finite element (FE) models is reported and applied to shape optimization of thin-walled beam components. The template consists of a skeletal curve and a set of cross-sectional profiles. The skeletal curve can be used to derive global model variations, while the cross section is designed to obtain local deformations of the given shape. A mesh deformation method based on the radial basis functions (RBF) interpolation is employed to derive the shape variations. Specifically, the skeleton-embedding space and an anisotropic distance metric are introduced to improve the RBF deformation method. To validate the applicability of the proposed template-based parameterization technique to general shape optimization frameworks, two proof-of-concept numerical studies pertaining to crashworthiness design of an S-shaped frame were implemented. The first case study focused on global deformations with the skeletal curve, and the second treated the cross-sectional profiles as design parameters to derive local reinforcements on the model. Both studies showed the efficiency of the proposed method in generation of quality shape variants for optimization. From the numerical results, considerable amount of improvements in crashworthiness performances of the S-shaped frame were observed as measured by the peak crushing force (PCF) and the energy absorption. We conclude that the proposed template-based parameterization technique is suitable for shape optimization tasks.

[Link to the publisher's version](https://doi.org/10.1115/1.4040487)

## Concurrent editing of automotive styling and structure with wireframe-pair

Baojun Li, Lei Yang, Hui Jiang, Weixue Sun, Ping Hu

### This project aims to provide an intuitive deformation metaphor for the body-in-white of an automobile.

**Abstract:** A constant demand in engineering design is to couple aesthetics and functionality of design. In this paper, a method is proposed to rapidly update the structural analysis models given the modifications made in the styling/packaging designs, forming a concurrent mechanism for developing the automotive styling and body structure. The seemingly disparate domains are represented by and thus coupled through a pair of wireframes. A joint mapping based on the hard points in packaging and a part mapping encoding local influences between wireframes are established. The deformation transfer from one of the wireframes to the other is solved as an optimization with constraints obtained from the two mappings. Finally, the finite element mesh model is adapted in accordance with the deformed structural wireframe, using a mesh morphing method based on the free-form deformation technique. Numerical results validate the proposed method and demonstrate its effectiveness.

[Link to the publisher's version](https://journals.sagepub.com/doi/abs/10.1177/0954407016669274)


