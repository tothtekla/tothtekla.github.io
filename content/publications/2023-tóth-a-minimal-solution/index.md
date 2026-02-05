---
title: A Minimal Solution for Image-Based Sphere Estimation
authors:
  - Tekla Tóth
  - Levente Hajder
date: 2023-03-02T00:00:00Z
hugoblox:
  ids:
    doi: 10.1007/s11263-023-01766-1
publication_types:
  - article-journal
publication: International Journal of Computer Vision
publication_short: IJCV
abstract: We propose a novel minimal
  solver for sphere fitting via its 2D central projection,
 i.e., a special ellipse. The input of the presented
  algorithm consists of contour points detected in a camera image. General
  ellipse fitting problems require five contour points. However, taking
  advantage of the isotropic spherical target, three points are enough to define
  the tangent cone parameters of the sphere. This yields the sought ellipse
  parameters. Similarly, the sphere center can be estimated from the cone if the
  radius is known. These proposed geometric methods are rapid, numerically
  stable, and easy to implement. Experimental results—on synthetic,
  photorealistic, and real images—showcase the superiority of the proposed
  solutions to the state-of-the-art methods. A real-world LiDAR-camera
  calibration application justifies the utility of the sphere-based approach
  resulting in an error below a few centimeters.
links:
  - type: source
    url: http://dx.doi.org/10.1007/s11263-023-01766-1
featured: false
---
