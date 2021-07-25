# Neural Projection Mapping of Textures

This repository contains LaTeX source files as well as the final PDF of my Master's thesis written in 2021 at Aalto University, Finland, under the supervision of Prof. Jaakko Lehtinen.

<img src="https://github.com/honzukka/Masters-Thesis/blob/main/images/01-results_teaser-target.jpg" width="250" alt="teaser - target texture"> <img src="https://github.com/honzukka/Masters-Thesis/blob/main/images/01-results_teaser-bg.jpg" width="250" alt="teaser - background"> <img src="https://github.com/honzukka/Masters-Thesis/blob/main/images/01-results_teaser-stats_proj.jpg" width="250" alt="teaser - compensated texture projected onto background">

## Abstract

Projection mapping is a widespread reality augmentation technique used by artists all over the world. It can be done automatically using a projector and a camera which captures the appearance of a projection in a scene. This appearance is then matched with a desired appearance pixel by pixel. However, this approach is limited by projector brightness when some pixels cannot be made as bright (or dark) as would be required to match the two appearances.

In this thesis, we propose a method which focuses on projecting textures and overcomes this problem to a certain extent. Simply put, textures are images with repetitive structure such as pebble beach, tree bark or brick wall. Nowadays, it is possible to automatically generate new examples of a given texture which look the same but their pixel values may be radically different. This problem is called texture synthesis. Instead of per-pixel matching, we thus use an existing synthesis technique based on a neural network to ensure that the actual appearance of a projection is a realization of the same texture as the desired appearance. As a result, our method is more flexible and thus able to reproduce a larger variety of appearances for a given scene.

We guide the reader through three experiments in which we evaluate our method in a software simulation, both on simple flat surfaces and arbitrary 3D scenes. We highlight cases where our method outperforms conventional projection mapping techniques, discuss its limitations and outline steps which are needed to achieve real world deployment.

## Full Text

You can find the full text of the thesis in PDF under [Releases](https://github.com/honzukka/Masters-Thesis/releases).

## Procam

There is a software project associated with the thesis called Procam. You can find it here: [https://github.com/honzukka/procam](https://github.com/honzukka/procam)
