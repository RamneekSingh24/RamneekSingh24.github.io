---
layout: page
title: CheaterStrike
description: A prototype FPS game secure against wall and aim hacks using Intel SGX.
img: assets/img/cheaterstrike.png
importance: 2
category: work
---

[Project Repo](https://github.com/RamneekSingh24/CheaterStrike)

- Done as a project for the course [IIT-D SIL765](https://www.cse.iitd.ac.in/~viresh/teaching/sil765/).
- A simple First Person Shooter game built using OpenGL.
- Uses Intel SGX to securely store the server data to prevent use of wall-hacks even in presence of a kernel level adversary.
- Customized network layer to use UDP with AES-GCM encryption with keys stored in a secure enclave.
- Sensitive data is filtered before being passed to the graphics pipeline.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cheater-strike-arch.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
