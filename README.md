<p align="center">
  <img src="https://github.com/PaddlePaddle/PaddleMIX/assets/22989727/2cd19298-1c52-4d73-a0f7-dcdab6a8ec90" align="middle" width = "600" />
</p>

<p align="center">
    <a href="./LICENSE"><img src="https://img.shields.io/badge/license-Apache%202-dfd.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/python-3.7+-aff.svg"></a>
    <a href=""><img src="https://img.shields.io/badge/os-linux%2C%20win%2C%20mac-pink.svg"></a>
    <a href="https://github.com/PaddlePaddle/PaddleMIX/stargazers"><img src="https://img.shields.io/github/stars/PaddlePaddle/PaddleMIX?color=ccf"></a>
</p>
</div>

## 简介

PaddleMIX是基于飞桨的跨模态大模型开发套件，聚合图像、文本、视频等多种模态，覆盖视觉语言预训练，文生图，文生视频等丰富的跨模态任务。提供开箱即用的开发体验，同时满足开发者灵活定制需求，探索通用人工智能。

## 最新进展

**2023.7.31 发布 PaddleMIX v0.1**
* 首次发布PaddleMIX跨模态大模型开发套件，融合PPdiffuser多模态扩散模型工具箱能力，广泛支持PaddleNLP大语言模型
* 新增EVA-CLIP，BLIP-2，miniGPT-4，Stable Diffusion，ControlNet等xx个跨模态大模型

## 主要特性

- **丰富的多模态功能:** 覆盖图文预训练，文生图，跨模态视觉任务，实现图像编辑、数据标注、数据清理等多样功能
- **简洁的开发体验:** 模型统一开发接口，高效实现自定义模型开发和功能实现
- **高效的训推流程:** 全量模型打通训练推理一站式开发流程，BLIP-2，Stable Diffusion等重点模型训推性能达到业界领先
- **超大规模训练支持:** 可训练千亿规模图文预训练模型，百亿规模文生图底座模型

## 任务展示

1. 图像描述（Image Caption）
2. 文图生成（Text-to-Image Generation）
3. 文本引导的图像编辑（Text-Guided Image Inpainting）

## 安装

1. 环境依赖
```
pip install -r requirements.txt
```

关于PaddlePaddle安装的详细教程请查看[Installation](https://www.paddlepaddle.org.cn/install/quick?docurl=/documentation/docs/zh/develop/install/pip/linux-pip.html)。

2. 手动安装
```
git clone https://github.com/PaddlePaddle/PaddleMIX
cd PaddleMIX
pip install -e .
```

## 教程

- 快速开始
- API文档
- 训练微调
- 推理部署

## 特色应用

1. 二维码模型
2. Generative FIll
3. Mix叠图

## 模型库

<table align="center">
  <tbody>
    <tr align="center" valign="center">
      <td>
        <b>视觉语言模型（paddlevlp）</b>
      </td>
      <td>
        <b>扩散类模型（ppdiffuser）</b>
      </td>
    </tr>
    <tr valign="top">
      <td>
        <ul>
        </ul>
          <li><b>图文预训练</b></li>
        <ul>
            <li><a href="paddlevlp/examples/evaclip">EVA-CLIP</a></li>
            <li><a href="paddlevlp/examples/blip2">BLIP-2</a></li>
            <li><a href="paddlevlp/examples/minigpt4">miniGPT-4</a></li>
            <li><a href="paddlevlp/examples/visualglm">VIsualGLM</a></li>
      </ul>
      </ul>
          <li><b>开放世界视觉模型</b></li>
        <ul>
            <li><a href="paddlevlp/examples/groundingdino">Grounding DINO</a></li>
            <li><a href="paddlevlp/examples/Sam">SAM</a></li>
      </ul>
      </td>
      <td>
        <ul>
        </ul>
          <li><b>文生图</b></li>
        <ul>
           <li><a href="ppdiffusers/examples">Stable Diffusion</a></li>
            <li><a href="ppdiffusers/examples">ControlNet</a></li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

## 许可证书

本项目的发布受Apache 2.0 license许可认证。
