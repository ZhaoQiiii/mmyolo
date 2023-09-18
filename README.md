<div align="center">
  <img width="100%" src="https://user-images.githubusercontent.com/27466624/222385101-516e551c-49f5-480d-a135-4b24ee6dc308.png"/>
  <div>&nbsp;</div>
  <div align="center">
    <b><font size="5">OpenMMLab website</font></b>
    <sup>
      <a href="https://openmmlab.com">
        <i><font size="4">HOT</font></i>
      </a>
    </sup>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <b><font size="5">OpenMMLab platform</font></b>
    <sup>
      <a href="https://platform.openmmlab.com">
        <i><font size="4">TRY IT OUT</font></i>
      </a>
    </sup>
  </div>
  <div>&nbsp;</div>

[![PyPI](https://img.shields.io/pypi/v/mmyolo)](https://pypi.org/project/mmyolo)
[![docs](https://img.shields.io/badge/docs-latest-blue)](https://mmyolo.readthedocs.io/en/latest/)
[![deploy](https://github.com/open-mmlab/mmyolo/workflows/deploy/badge.svg)](https://github.com/open-mmlab/mmyolo/actions)
[![codecov](https://codecov.io/gh/open-mmlab/mmyolo/branch/main/graph/badge.svg)](https://codecov.io/gh/open-mmlab/mmyolo)
[![license](https://img.shields.io/github/license/open-mmlab/mmyolo.svg)](https://github.com/open-mmlab/mmyolo/blob/main/LICENSE)
[![open issues](https://isitmaintained.com/badge/open/open-mmlab/mmyolo.svg)](https://github.com/open-mmlab/mmyolo/issues)
[![issue resolution](https://isitmaintained.com/badge/resolution/open-mmlab/mmyolo.svg)](https://github.com/open-mmlab/mmyolo/issues)
[![Open in OpenXLab](https://cdn-static.openxlab.org.cn/app-center/openxlab_demo.svg)](https://openxlab.org.cn/apps?search=mmyolo)


[📘Documentation](https://mmyolo.readthedocs.io/en/latest/) |
[🛠️Installation](https://mmyolo.readthedocs.io/en/latest/get_started/installation.html) |
[👀Model Zoo](https://mmyolo.readthedocs.io/en/latest/model_zoo.html) |
[🆕Update News](https://mmyolo.readthedocs.io/en/latest/notes/changelog.html) |
[🤔Reporting Issues](https://github.com/open-mmlab/mmyolo/issues/new/choose)

</div>

<div align="center">

English | [简体中文](README_zh-CN.md)

</div>

<div align="center">
  <a href="https://openmmlab.medium.com/" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219255827-67c1a27f-f8c5-46a9-811d-5e57448c61d1.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://discord.com/channels/1037617289144569886/1046608014234370059" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218347213-c080267f-cbb6-443e-8532-8e1ed9a58ea9.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://twitter.com/OpenMMLab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346637-d30c8a0f-3eba-4699-8131-512fb06d46db.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://www.youtube.com/openmmlab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/218346691-ceb2116a-465a-40af-8424-9f30d2348ca9.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://space.bilibili.com/1293512903" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219026751-d7d14cce-a7c9-4e82-9942-8375fca65b99.png" width="3%" alt="" /></a>
  <img src="https://user-images.githubusercontent.com/25839884/218346358-56cc8e2f-a2b8-487f-9088-32480cceabcf.png" width="3%" alt="" />
  <a href="https://www.zhihu.com/people/openmmlab" style="text-decoration:none;">
    <img src="https://user-images.githubusercontent.com/25839884/219026120-ba71e48b-6e94-4bd4-b4e9-b7d175b5e362.png" width="3%" alt="" /></a>
</div>

## 📄 Table of Contents

- [🥳 🚀 What's New](#--whats-new-)
  - [✨ Highlight](#-highlight-)
- [📖 Introduction](#-introduction-)
- [🛠️ Installation](#%EF%B8%8F-installation-)
- [👨‍🏫 Tutorial](#-tutorial-)
- [📊 Overview of Benchmark and Model Zoo](#-overview-of-benchmark-and-model-zoo-)
- [🧰 Projects Based on MMYOLO](#-projects-based-on-mmyolo-)
- [❓ FAQ](#-faq-)
- [🙌 Contributing](#-contributing-)
- [🤝 Acknowledgement](#-acknowledgement-)
- [🖊️ Citation](#️-citation-)
- [🎫 License](#-license-)
- [🏗️ Projects in OpenMMLab](#%EF%B8%8F-projects-in-openmmlab-)

## 🥳 🚀 What's New [🔝](#-table-of-contents)

💎 **v0.6.0** was released on 15/8/2023:

- Support YOLOv5 instance segmentation
- Support YOLOX-Pose based on MMPose
- Add 15 minutes instance segmentation tutorial.
- YOLOv5 supports using mask annotation to optimize bbox
- Add Multi-scale training and testing docs

For release history and update details, please refer to [changelog](https://mmyolo.readthedocs.io/en/latest/notes/changelog.html).

### ✨ Highlight [🔝](#-table-of-contents)

We are excited to announce our latest work on real-time object recognition tasks, **RTMDet**, a family of fully convolutional single-stage detectors. RTMDet not only achieves the best parameter-accuracy trade-off on object detection from tiny to extra-large model sizes but also obtains new state-of-the-art performance on instance segmentation and rotated object detection tasks. Details can be found in the [technical report](https://arxiv.org/abs/2212.07784). Pre-trained models are [here](configs/rtmdet).

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/rtmdet-an-empirical-study-of-designing-real/real-time-instance-segmentation-on-mscoco)](https://paperswithcode.com/sota/real-time-instance-segmentation-on-mscoco?p=rtmdet-an-empirical-study-of-designing-real)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/rtmdet-an-empirical-study-of-designing-real/object-detection-in-aerial-images-on-dota-1)](https://paperswithcode.com/sota/object-detection-in-aerial-images-on-dota-1?p=rtmdet-an-empirical-study-of-designing-real)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/rtmdet-an-empirical-study-of-designing-real/object-detection-in-aerial-images-on-hrsc2016)](https://paperswithcode.com/sota/object-detection-in-aerial-images-on-hrsc2016?p=rtmdet-an-empirical-study-of-designing-real)

| Task                     | Dataset | AP                                   | FPS(TRT FP16 BS1 3090) |
| ------------------------ | ------- | ------------------------------------ | ---------------------- |
| Object Detection         | COCO    | 52.8                                 | 322                    |
| Instance Segmentation    | COCO    | 44.6                                 | 188                    |
| Rotated Object Detection | DOTA    | 78.9(single-scale)/81.3(multi-scale) | 121                    |

<div align=center>
<img src="https://user-images.githubusercontent.com/12907710/208044554-1e8de6b5-48d8-44e4-a7b5-75076c7ebb71.png"/>
</div>

MMYOLO currently implements the object detection and rotated object detection algorithm, but it has a significant training acceleration compared to the MMDeteciton version. The training speed is 2.6 times faster than the previous version.

## 📖 Introduction [🔝](#-table-of-contents)

MMYOLO is an open source toolbox for YOLO series algorithms based on PyTorch and [MMDetection](https://github.com/open-mmlab/mmdetection). It is a part of the [OpenMMLab](https://openmmlab.com/) project.

The master branch works with **PyTorch 1.6+**.
<img src="https://user-images.githubusercontent.com/45811724/190993591-bd3f1f11-1c30-4b93-b5f4-05c9ff64ff7f.gif"/>

<details open>
<summary>Major features</summary>

- 🕹️ **Unified and convenient benchmark**

  MMYOLO unifies the implementation of modules in various YOLO algorithms and provides a unified benchmark. Users can compare and analyze in a fair and convenient way.

- 📚 **Rich and detailed documentation**

  MMYOLO provides rich documentation for getting started, model deployment, advanced usages, and algorithm analysis, making it easy for users at different levels to get started and make extensions quickly.

- 🧩 **Modular Design**

  MMYOLO decomposes the framework into different components where users can easily customize a model by combining different modules with various training and testing strategies.

<img src="https://user-images.githubusercontent.com/27466624/199999337-0544a4cb-3cbd-4f3e-be26-bcd9e74db7ff.jpg" alt="BaseModule-P5"/>
  The figure above is contributed by RangeKing@GitHub, thank you very much!

And the figure of P6 model is in [model_design.md](docs/en/recommended_topics/model_design.md).

</details>

## 🛠️ Installation [🔝](#-table-of-contents)

MMYOLO relies on PyTorch, MMCV, MMEngine, and MMDetection. Below are quick steps for installation. Please refer to the [Install Guide](docs/en/get_started/installation.md) for more detailed instructions.

```shell
conda create -n mmyolo python=3.8 pytorch==1.10.1 torchvision==0.11.2 cudatoolkit=11.3 -c pytorch -y
conda activate mmyolo
pip install openmim
mim install "mmengine>=0.6.0"
mim install "mmcv>=2.0.0rc4,<2.1.0"
mim install "mmdet>=3.0.0,<4.0.0"
git clone https://github.com/open-mmlab/mmyolo.git
cd mmyolo
# Install albumentations
pip install -r requirements/albu.txt
# Install MMYOLO
mim install -v -e .
```

## 👨‍🏫 Tutorial [🔝](#-table-of-contents)

MMYOLO is based on MMDetection and adopts the same code structure and design approach. To get better use of this, please read [MMDetection Overview](https://mmdetection.readthedocs.io/en/latest/get_started.html) for the first understanding of MMDetection.

The usage of MMYOLO is almost identical to MMDetection and all tutorials are straightforward to use, you can also learn about [MMDetection User Guide and Advanced Guide](https://mmdetection.readthedocs.io/en/3.x/).

For different parts from MMDetection, we have also prepared user guides and advanced guides, please read our [documentation](https://mmyolo.readthedocs.io/zenh_CN/latest/).

<details>
<summary>Get Started</summary>

- [Overview](docs/en/get_started/overview.md)
- [Dependencies](docs/en/get_started/dependencies.md)
- [Installation](docs/en/get_started/installation.md)
- [15 minutes object detection](docs/en/get_started/15_minutes_object_detection.md)
- [15 minutes rotated object detection](docs/en/get_started/15_minutes_rotated_object_detection.md)
- [15 minutes instance segmentation](docs/en/get_started/15_minutes_instance_segmentation.md)
- [Resources summary](docs/en/get_started/article.md)

</details>

<details>
<summary>Recommended Topics</summary>

- [How to contribute code to MMYOLO](docs/en/recommended_topics/contributing.md)
- [Training testing tricks](docs/en/recommended_topics/training_testing_tricks.md)
- [MMYOLO model design](docs/en/recommended_topics/model_design.md)
- [Algorithm principles and implementation](docs/en/recommended_topics/algorithm_descriptions/)
- [Replace the backbone network](docs/en/recommended_topics/replace_backbone.md)
- [MMYOLO model complexity analysis](docs/en/recommended_topics/complexity_analysis.md)
- [Annotation-to-deployment workflow for custom dataset](docs/en/recommended_topics/labeling_to_deployment_tutorials.md)
- [Visualization](docs/en/recommended_topics/visualization.md)
- [Model deployment](docs/en/recommended_topics/deploy/)
- [Troubleshooting steps](docs/en/recommended_topics/troubleshooting_steps.md)
- [MMYOLO application examples](docs/en/recommended_topics/application_examples/)
- [MM series repo essential basics](docs/en/recommended_topics/mm_basics.md)
- [Dataset preparation and description](docs/en/recommended_topics/dataset_preparation.md)

</details>

<details>
<summary>Common Usage</summary>

- [Resume training](docs/en/common_usage/resume_training.md)
- [Enabling and disabling SyncBatchNorm](docs/en/common_usage/syncbn.md)
- [Enabling AMP](docs/en/common_usage/amp_training.md)
- [Multi-scale training and testing](docs/en/common_usage/ms_training_testing.md)
- [TTA Related Notes](docs/en/common_usage/tta.md)
- [Add plugins to the backbone network](docs/en/common_usage/plugins.md)
- [Freeze layers](docs/en/common_usage/freeze_layers.md)
- [Output model predictions](docs/en/common_usage/output_predictions.md)
- [Set random seed](docs/en/common_usage/set_random_seed.md)
- [Module combination](docs/en/common_usage/module_combination.md)
- [Cross-library calls using mim](docs/en/common_usage/mim_usage.md)
- [Apply multiple Necks](docs/en/common_usage/multi_necks.md)
- [Specify specific device training or inference](docs/en/common_usage/specify_device.md)
- [Single and multi-channel application examples](docs/en/common_usage/single_multi_channel_applications.md)

</details>

<details>
<summary>Useful Tools</summary>

- [Browse coco json](docs/en/useful_tools/browse_coco_json.md)
- [Browse dataset](docs/en/useful_tools/browse_dataset.md)
- [Print config](docs/en/useful_tools/print_config.md)
- [Dataset analysis](docs/en/useful_tools/dataset_analysis.md)
- [Optimize anchors](docs/en/useful_tools/optimize_anchors.md)
- [Extract subcoco](docs/en/useful_tools/extract_subcoco.md)
- [Visualization scheduler](docs/en/useful_tools/vis_scheduler.md)
- [Dataset converters](docs/en/useful_tools/dataset_converters.md)
- [Download dataset](docs/en/useful_tools/download_dataset.md)
- [Log analysis](docs/en/useful_tools/log_analysis.md)
- [Model converters](docs/en/useful_tools/model_converters.md)

</details>

<details>
<summary>Basic Tutorials</summary>

- [Learn about configs with YOLOv5](docs/en/tutorials/config.md)
- [Data flow](docs/en/tutorials/data_flow.md)
- [Rotated detection](docs/en/tutorials/rotated_detection.md)
- [Custom Installation](docs/en/tutorials/custom_installation.md)
- [Common Warning Notes](docs/zh_cn/tutorials/warning_notes.md)
- [FAQ](docs/en/tutorials/faq.md)

</details>

<details>
<summary>Advanced Tutorials</summary>

- [MMYOLO cross-library application](docs/en/advanced_guides/cross-library_application.md)

</details>

<details>
<summary>Descriptions</summary>

- [Changelog](docs/en/notes/changelog.md)
- [Compatibility](docs/en/notes/compatibility.md)
- [Conventions](docs/en/notes/conventions.md)
- [Code Style](docs/en/notes/code_style.md)

</details>

## 📊 Overview of Benchmark and Model Zoo [🔝](#-table-of-contents)

<div align=center>
<img src="https://user-images.githubusercontent.com/17425982/222087414-168175cc-dae6-4c5c-a8e3-3109a152dd19.png"/>
</div>

Results and models are available in the [model zoo](docs/en/model_zoo.md).

<details open>
<summary><b>Supported Tasks</b></summary>

- [x] Object detection
- [x] Rotated object detection

</details>

<details open>
<summary><b>Supported Algorithms</b></summary>

- [x] [YOLOv5](configs/yolov5)
- [ ] [YOLOv5u](configs/yolov5/yolov5u) (Inference only)
- [x] [YOLOX](configs/yolox)
- [x] [RTMDet](configs/rtmdet)
- [x] [RTMDet-Rotated](configs/rtmdet)
- [x] [YOLOv6](configs/yolov6)
- [x] [YOLOv7](configs/yolov7)
- [x] [PPYOLOE](configs/ppyoloe)
- [x] [YOLOv8](configs/yolov8)

</details>

<details open>
<summary><b>Supported Datasets</b></summary>

- [x] COCO Dataset
- [x] VOC Dataset
- [x] CrowdHuman Dataset
- [x] DOTA 1.0 Dataset

</details>

<details open>
<div align="center">
  <b>Module Components</b>
</div>
<table align="center">
  <tbody>
    <tr align="center" valign="bottom">
      <td>
        <b>Backbones</b>
      </td>
      <td>
        <b>Necks</b>
      </td>
      <td>
        <b>Loss</b>
      </td>
      <td>
        <b>Common</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
      <ul>
        <li>YOLOv5CSPDarknet</li>
        <li>YOLOv8CSPDarknet</li>
        <li>YOLOXCSPDarknet</li>
        <li>EfficientRep</li>
        <li>CSPNeXt</li>
        <li>YOLOv7Backbone</li>
        <li>PPYOLOECSPResNet</li>
        <li>mmdet backbone</li>
        <li>mmcls backbone</li>
        <li>timm</li>
      </ul>
      </td>
      <td>
      <ul>
        <li>YOLOv5PAFPN</li>
        <li>YOLOv8PAFPN</li>
        <li>YOLOv6RepPAFPN</li>
        <li>YOLOXPAFPN</li>
        <li>CSPNeXtPAFPN</li>
        <li>YOLOv7PAFPN</li>
        <li>PPYOLOECSPPAFPN</li>
      </ul>
      </td>
      <td>
        <ul>
          <li>IoULoss</li>
          <li>mmdet loss</li>
        </ul>
      </td>
      <td>
        <ul>
        </ul>
      </td>
    </tr>
</td>
    </tr>
  </tbody>
</table>

</details>

## 🧰 Projects Based on MMYOLO [🔝](#-table-of-contents)

### Algorithm

- [YOLO-MS](https://github.com/FishAndWasabi/YOLO-MS)
  Rethinking Multi-Scale Representation Learning for Real-Time Object Detection

- [RSPrompter](https://github.com/KyanChen/RSPrompter)
  Learning to Prompt for Remote Sensing Instance Segmentation based on Visual Foundation Model

- [EAEFNet](https://github.com/FreeformRobotics/EAEFNet)
  Explicit Attention-Enhanced Fusion for RGB-Thermal Perception Tasks

- [CVPRW2023 Track 1: Multi-Camera People Tracking](https://github.com/ipl-uw/AIC23_Track1_UWIPL_ETRI)
  Enhancing Multi-Camera People Tracking with Anchor-Guided Clustering and Spatio-Temporal Consistency ID Re-Assignment

### Deployment

- [EdgeLab](https://github.com/Seeed-Studio/EdgeLab)
  Seeed Studio EdgeLab is an open-source project focused on embedded AI. They have optimized excellent algorithms from OpenMMLab for real-world scenarios and made implementation more user-friendly, achieving faster and more accurate inference on embedded devices.

- [AX-Samples](https://github.com/AXERA-TECH/ax-samples/tree/main/examples/ax620)
  AX-Samples is developed by Axera. This project implements the sample code of common deep learning open source algorithms on Axera's AI SoC. There're some MMYOLO case examples in this project.

- [PPQ ONNX Quantization Model Zoo](https://github.com/openppl-public/ppq/blob/master/ppq/samples/QuantZoo/Readme.md#33-%E7%9B%AE%E6%A0%87%E6%A3%80%E6%B5%8B)
  OnnxQuant is the largest model quantization dataset available that contains ONNX models, dataset, and associated test scripts. They use MMYOLO to build the object detection benchmark.

## ❓ FAQ [🔝](#-table-of-contents)

Please refer to the [FAQ](docs/en/tutorials/faq.md) for frequently asked questions.

## 🙌 Contributing [🔝](#-table-of-contents)

We appreciate all contributions to improving MMYOLO. Ongoing projects can be found in our [GitHub Projects](https://github.com/open-mmlab/mmyolo/projects). Welcome community users to participate in these projects. Please refer to [CONTRIBUTING.md](.github/CONTRIBUTING.md) for the contributing guideline.

## 🤝 Acknowledgement [🔝](#-table-of-contents)

MMYOLO is an open source project that is contributed by researchers and engineers from various colleges and companies. We appreciate all the contributors who implement their methods or add new features, as well as users who give valuable feedback.
We wish that the toolbox and benchmark could serve the growing research community by providing a flexible toolkit to re-implement existing methods and develop their own new detectors.

<div align="center">
  <a href="https://github.com/open-mmlab/mmyolo/graphs/contributors"><img src="https://contrib.rocks/image?repo=open-mmlab/mmyolo"/></a>
</div>

## 🖊️ Citation [🔝](#-table-of-contents)

If you find this project useful in your research, please consider citing:

```latex
@misc{mmyolo2022,
    title={{MMYOLO: OpenMMLab YOLO} series toolbox and benchmark},
    author={MMYOLO Contributors},
    howpublished = {\url{https://github.com/open-mmlab/mmyolo}},
    year={2022}
}
```

## 🎫 License [🔝](#-table-of-contents)

This project is released under the [GPL 3.0 license](LICENSE).

## 🏗️ Projects in OpenMMLab [🔝](#-table-of-contents)

- [MMEngine](https://github.com/open-mmlab/mmengine): OpenMMLab foundational library for training deep learning models.
- [MMCV](https://github.com/open-mmlab/mmcv): OpenMMLab foundational library for computer vision.
- [MMPreTrain](https://github.com/open-mmlab/mmpretrain): OpenMMLab pre-training toolbox and benchmark.
- [MMagic](https://github.com/open-mmlab/mmagic): Open**MM**Lab **A**dvanced, **G**enerative and **I**ntelligent **C**reation toolbox.
- [MMDetection](https://github.com/open-mmlab/mmdetection): OpenMMLab detection toolbox and benchmark.
- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d): OpenMMLab's next-generation platform for general 3D object detection.
- [MMRotate](https://github.com/open-mmlab/mmrotate): OpenMMLab rotated object detection toolbox and benchmark.
- [MMYOLO](https://github.com/open-mmlab/mmyolo): OpenMMLab YOLO series toolbox and benchmark.
- [MMSegmentation](https://github.com/open-mmlab/mmsegmentation): OpenMMLab semantic segmentation toolbox and benchmark.
- [MMOCR](https://github.com/open-mmlab/mmocr): OpenMMLab text detection, recognition, and understanding toolbox.
- [MMPose](https://github.com/open-mmlab/mmpose): OpenMMLab pose estimation toolbox and benchmark.
- [MMHuman3D](https://github.com/open-mmlab/mmhuman3d): OpenMMLab 3D human parametric model toolbox and benchmark.
- [MMSelfSup](https://github.com/open-mmlab/mmselfsup): OpenMMLab self-supervised learning toolbox and benchmark.
- [MMRazor](https://github.com/open-mmlab/mmrazor): OpenMMLab model compression toolbox and benchmark.
- [MMFewShot](https://github.com/open-mmlab/mmfewshot): OpenMMLab fewshot learning toolbox and benchmark.
- [MMAction2](https://github.com/open-mmlab/mmaction2): OpenMMLab's next-generation action understanding toolbox and benchmark.
- [MMTracking](https://github.com/open-mmlab/mmtracking): OpenMMLab video perception toolbox and benchmark.
- [MMFlow](https://github.com/open-mmlab/mmflow): OpenMMLab optical flow toolbox and benchmark.
- [MMEditing](https://github.com/open-mmlab/mmediting): OpenMMLab image and video editing toolbox.
- [MMGeneration](https://github.com/open-mmlab/mmgeneration): OpenMMLab image and video generative models toolbox.
- [MMDeploy](https://github.com/open-mmlab/mmdeploy): OpenMMLab model deployment framework.
- [MIM](https://github.com/open-mmlab/mim): MIM installs OpenMMLab packages.
- [MMEval](https://github.com/open-mmlab/mmeval): OpenMMLab machine learning evaluation library.
- [Playground](https://github.com/open-mmlab/playground): A central hub for gathering and showcasing amazing projects built upon OpenMMLab.
