---
---

# QiMeng-Intelligence Computing Group's Website（QiMeng智能计算团队）

The main goal of the QiMeng-Intelligence Computing Group is to deeply integrate the knowledge of the software development field with large model technologies, explore new paradigms for software development, and achieve the automatic generation of typical basic software and application software with high performance and high quality. This is expected to significantly improve the efficiency of software development and efficiently support the construction of the software ecosystem for new processors such as RISC-V.

QiMeng智能计算团队的主要目标是深度融合软件开发领域知识与大模型技术，探索软件开发新范式，实现高性能高质量的典型基础软件和应用软件的自动生成，以期大幅度提升软件开发效率，高效支持国产处理器的软件生态构建。


{% include section.html %}

## Highlights（亮点成果）

{% capture text %}

The QiMeng-GEMM framework enables LLMs to understand the characteristics of different hardware architectures and automatically search for optimized GEMM combinations. A large number of experiments have proven that it demonstrates outstanding performance in automatically generating optimized GEMM code. It can significantly boost performance, shorten the development cycle, and reduce costs, bringing remarkable benefits to the development of related applications in the RISC-V ecosystem.

QiMeng-GEMM框架能让大语言模型理解不同硬件架构特征自动搜索GEMM优化组合，经大量实验证明其在自动生成优化GEMM代码方面性能卓越，大幅提升性能、缩短开发周期并降低成本，为RISC - V生态下相关应用开发带来显著收益。

[QiMeng-GEMM Paper Website](https://github.com/Chris-Chow/QiMeng-GEMM)

[QiMeng-TensorOp Paper Website](https://github.com/zhangxuzhi/QiMeng-TensorOp)

[QiMeng-Attention Paper Website](https://github.com/Chris-Chow/QiMeng-Attention)


{% endcapture %}

{%
  include feature.html
  image="images/qimeng-gemm.png"
  link="research"
  title="Our Research（学术成果）"
  text=text
%}

{% capture text %}

This QMD-Bench benchmark evaluates both functional correctness and performance of high-performance library migration across architectures, providing a comprehensive assessment of migration effectiveness and efficiency.

QMD-Bench 基准测试评估跨架构高性能库迁移的功能正确性与性能表现，为迁移的有效性与效率提供全面评估。

[QMD-Bench——智能体驱动的跨架构代码迁移Benchmark](https://github.com/breezejh/QMD-bench)

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/QMD-Bench.png"
  link="projects"
  title="Our Bechmark（评测集发布）"
  flip=true
  style="bare"
  text=text
%}

