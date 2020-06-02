---
title: "Ultrasound Nerve Segmentation - DLMI  (Mar 2020)"
excerpt: "The goal of this project was to build an image segmentation model to identify nerve structures in the neck. <br/><img src='/images/dlmi.png'>"
collection: portfolio
---

Identifying nerve structures in the neck has various medical goals. Indeed, it is intended to imporve pain management by providing a tool to effectively insert a patient's pain management catheter. Currently, patient pain is frequently managed through the use of narcotics that brings unwanted side effects. Ultrasound nerve segmentation is here an important step to a more pain free future.

The dataset contained images where the nerves were manually annotated by humans. We developed a model based on the [U-net](https://arxiv.org/abs/1505.04597) architecture and other of its variants as well as Data augmentation. Finally, we used [Dice Coefficient](https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient) as an evaluation metric for our model. 

The details of our approach is described in the [report](https://khaoulabelahsen.github.io/files/dlmi_report.pdf).

You can find the [final report](https://khaoulabelahsen.github.io/files/dlmi_report.pdf) for this project and the Python [source code](https://github.com/khaoulabelahsen/MVA-DLMI) which provide further details about this project.
 
