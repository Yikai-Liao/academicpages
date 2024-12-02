---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

## Education

### Nanyang Technological University (NTU)

> **Ph.D.** in *College of Computing and Data Science (CCDS)*

* Aug 2024 - Present
* Singapore
* Researching **Continual Learning** under the guidance of [Prof. Ying Wei](https://wei-ying.net/).

### Beijing University of Posts and Telecommunication (BUPT)

> **Bachelor** in *Intelligence Science and Technology*

* Sep 2020 - Jun 2024
* Beijing
* GPA: 89.13/100 (Rank: 8/68)


## Work experience

### Nanjing Qiyin Technology Co. Ltd.

> Co-founder and AI Algorithm Leader

* 2021 - 2024
* Awarded the **National Gold Medal** for the **Boya AI Music Project** at the **7th China College Students "Internet+" Innovation and Entrepreneurship Competition**.
* Founded **Qiyin Technology** and secured **million-level seed round financing** from **MiraclePlus** (formerly YC China).
* Designed and trained models for **symbolic music generation**, **melody generation**, and **music segment similarity** using contrastive learning.


## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


## Projects

### [SyMusic](https://github.com/Yikai-Liao/symusic)  
> A fast note-level MIDI decoding library  
> Sep 2023  

- Developed **SyMusic**, a **cross-platform, note-level MIDI decoding library**, nearly **1000 times faster** than the widely-used **mido** library.
- Written in **C++** with a Python interface via [nanobind](https://github.com/wjakob/nanobind).
- 🎉 Now published in [ISMIR 2024 LBD](https://ismir2024program.ismir.net/lbd_426.html#lbd)

### [Efficient BPE](https://github.com/Yikai-Liao/efficient_bpe)  
> An efficient implementation of BPE training algorithm  
> Apr 2023  

- Optimized the BPE training algorithm for token pair merging.
- Implemented in **pure Python**, outperforming the **Rust implementation** in Hugging Face's tokenizers.

### [Chord Recognizer](https://github.com/Yikai-Liao/chord_recognizer)  
> A fast chord extractor for MIDI  
> Sep 2022  

- Implemented a **hidden Markov chain** model to extract chord progressions, using the **Viterbi algorithm**.
- Accelerated with **Numba** for performance.