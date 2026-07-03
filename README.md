# NeoMLs
A set of next-generation modeling languages built on KerML.  Its immediate purpose is to provide textual model notations for AI-driven software engineering.

一组基于 KerML 的新一代建模语言。其直接目的是为 AI 驱动的软件工程提供文本化的模型表示法。

This project reconstructs MOF, KerML, UML and other modeling languages based on KerML. Once OMG publishes official KerML-native standards, this repository will be archived.

本项目将基于 KerML 重新构建 MOF、KerML、UML 及其他建模语言。一旦 OMG 官方正式发布了基于 KerML 的原生标准，本仓库将完成历史使命 ：）。

## 问题的提出

围绕 AI 的软件工程，需要将领域模型文本化。
领域建模的标准做法是UML，因此需要将 UML 文本化。
社区早已经有这种尝试，尽管之前不是为了 AI。例如 Plant UML。
OMG官方只有XMI,难以被人直接阅读和修改。


2025年9月，OMG 正式发布了 **Kernel Modeling Language™ (KerML™) Verson 1.0** 和 **OMG Systems Modeling Language™
(SysML®) Version 2.0** (简称 SysML v2)。将文本表示法作为建模语言的首要表示法，而不像UML那样以模型图为先。这为 UML 的文本化带来一线曙光。

然而，OMG 官方并没有再接再厉，将 UML 也用 KerML 重建。因此目前 UML 并没有官方的文本表示标准。

## 现状

KerML 的产生，本来是为了解决 UML 长期依赖存在的根本问题，因此才另起炉灶。但 KerML 本身的的抽象语法仍然使用了UML。因此并未彻底斩断和 UML 的期待。这是因为，KerML 是基于 MOF (Meta Object Facility) 的，而 MOF 又是使用 UML 来描述的。

目前，MOF 和 UML 的关系如下图：

<p align="center">
  <img src="img/mof-and-uml.png" alt="MOF 和 UML 的关系" style="width:220;" />
</p>



目前 OMG 各建模语言规范的关系如下图：

<p align="center">
  <img src="img/current-ml-specs.png" alt="当前 OMG 建模语言标准" style="width:320;" />
</p>


## 远景

理想状态下，MOF 和 KerML 的关系应该如下图：

<p align="center">
  <img src="img/idea-mof-and-kerml.png" alt="MOF 和 KerML 的理想关系" style="width:220;" />
</p>



理想状态下，各建模语言规范的关系应如下图：

<p align="center">
  <img src="img/idea-ml-spec.png" alt="当前 OMG 建模语言标准" style="width:480;" />
</p>



## 路线图

bootstrapping





