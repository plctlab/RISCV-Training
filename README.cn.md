# RISC-V 培训项目

目前 PLCT 实验室主要提供编译器课程的培训。目前只有中文。欢迎通过实习形式加入到具体的项目开发中，或参与旁听PLCT编译技术讨论班（见下方）。
同时，英文版课程以及模拟器相关课程也在准备中，敬请期待。


## 手搓 RISC-V 高性能模拟器 · 2023 年 4 月

在本课程中，我们将使用 C 语言从零开始实现一个高性能 RISC-V 64 位模拟器。在课程的最后，我们会得到一个代码量 4000 行左右的，零依赖的用户态程序模拟器，可以运行一些真实世界的程序，比如 Lua 4.0。如果读者好奇 JIT 模拟器的工作原理，那么本课程正是为你准备的。

视频地址：

https://space.bilibili.com/296494084/channel/collectiondetail?sid=1245472

仓库地址：

https://github.com/ksco/rvemu

课程网站：

https://ksco.cc/rvemu/

## 从零开始实现链接器 · 2022 年秋季

在本课程中，我们会从零开始使用 Go 语言实现一个 RV64GC（RISC-V 64 位）架构的链接器，可以正确地链接相对简单的 C 程序。通过学习本课程，我们可以掌握链接器最核心部分的工作原理。

视频地址：

https://space.bilibili.com/296494084/channel/collectiondetail?sid=857032

仓库地址：

https://github.com/ksco/rvld

课程网站：

https://ksco.cc/rvld/

## 徒手写一个 RISC-V 编译器 · 2022 年 7 月

本课程基于 rui314 的 chibicc，由原来的 X86 架构改写为 RISC-V 64 架构，同时加入了大量的中文注释，并且配有 316 节对应于每一个 commit 的课程，帮助读者可以层层推进、逐步深入地学习编译器的构造。

视频地址：

https://space.bilibili.com/296494084/channel/collectiondetail?sid=571708

仓库地址：

https://github.com/sunshaoce/rvcc


## 编译技术入门与实战·第三季·2021年4月

本期将在前两期的基础上，结合LLVM源代码，讲解10个常用算法。最后实现一个RISC-V优化的大作业。

视频地址：

https://www.bilibili.com/video/BV14b4y1X7uX/

仓库地址：

https://github.com/lazyparser/becoming-a-compiler-engineer

## PLCT编译器设计讨论班（2020秋）aka 编译技术入门与实战·第二季

每周五、周六的下午3点到4点之间进行讨论课，线上腾讯会议的形式，欢迎加入讨论。进入方式是添加我（lazyparser）的微信 fangzhang1024 （备注编译课程）进入微信学习群，每次会议的通知会在群里发出来。以及一些资源也会在群里贴出。

- 第16次讨论：RISC-V ABI 介绍 by 林思南 [video](https://www.bilibili.com/video/BV1bz4y1S71o)
- 第15次讨论：GCC入门（二）RTL by 陈嘉炜 [video](https://www.bilibili.com/video/BV1gy4y1H7bg)
- 第14次讨论：上手开发GCC-陈嘉炜 [video](https://www.bilibili.com/video/BV1Nf4y1y7Bz)
- 第13次讨论：RVV-LLVM设计、shecc代码、RISCV反汇编器、EEMBC [video](https://www.bilibili.com/video/BV1Uz4y1r7sq)
- 第13次讨论：RVV-LLVM设计、shecc代码、RISCV反汇编器、EEMBC [video](https://www.bilibili.com/video/BV1Uz4y1r7sq)
- 第12次讨论：LLVM栈对齐、shecc libc、zfinx gdb反汇编支持 [video](https://www.bilibili.com/video/BV1AT4y1u7ys)
- 第11次讨论：LLVM寄存器表示、RISC-V指令集学习方法 [video](https://www.bilibili.com/video/BV1kp4y1z7JU)
- 第10次讨论：RV32Emu-Next [video](https://www.bilibili.com/video/BV1nv411r7yf)
- 第09次讨论：LLVM GlobalISel、RISC-V Zfinx GNU Impl [video](https://www.bilibili.com/video/BV1iz4y1y7Xe)
- 第08次讨论：OpenJ9、LLVM、RISC-V、Zfinx [video](https://www.bilibili.com/video/BV1hv411r7ns)
- 第07次讨论：为 rvv-llvm 添加一个 intrinsic (廖春玉) [video](https://www.bilibili.com/video/bv1PA411j79G)
- 第06次讨论：指令选择、Zfinx、MIT作业 [video](https://www.bilibili.com/video/BV1Tz4y1y7Ng)
- 第05次讨论：Tiger编译器RISC-V后端、MLIR运行GEMM在蜂鸟FPGA评估版上 [video](https://www.bilibili.com/video/BV14t4y1e7nJ)
- 第04次讨论：Register Scavenger、编译优化简介 [video](https://www.bilibili.com/video/BV1Qt4y1Y7yc)
- 第03次讨论：LLVM、SDT、作业 [video](https://www.bilibili.com/video/bv1Ky4y1879o)
- 第02次讨论：EaC ch4、LLVM IR、shecc 教学编译器 [video](https://www.bilibili.com/video/BV1zA41177SH)
- 第01次讨论：《编译器设计》前三章回顾 [video](https://www.bilibili.com/video/BV1454y1m7EF)

## 编译技术入门与实战·第一季·2019秋

所有的课程视频可以通过以下入口访问，后续课程会通过增加分p的方式陆续上传：

https://www.bilibili.com/video/av78503049

本仓库地址是

https://github.com/lazyparser/becoming-a-compiler-engineer

计划更新至2020年8月(收到COVID-19影响延长2个月)。

https://github.com/lazyparser/becoming-a-compiler-engineer-codes

可以参考的学生作业

https://github.com/wenwensong114/scanner

可以参考的教材：

https://pandolia.net/tinyc/index.html

偏实战，用简单和易于实现的实例来描述基本的编译原理及过程


