# manashu

为 FIT3173 Software Security 服务。

主要是 x86 到 arm / risc-v 代码的转换。目前有三种思路

- Phase 1: 精简小巧的 hypervisor 能够在 arm 架构上模拟 x86 代码 (参考 Xen 和 高通开源的Xen启动等) 
- Phase 2: [Docker container](https://github.com/codecrafters-io/build-your-own-x), sgx-lkl, [vSGX](https://ieeexplore.ieee.org/document/9833694)
- Phase 3: Just-in Time 的 Interpreter (就是 苹果的 Rosata) 
- Phase 4: x86 asm & webasm (webasm 获得过高度赞扬)

