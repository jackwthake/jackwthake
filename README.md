# Hi, I'm Jack

## Systems Engineer & Low-Level Software Developer.
I build high-performance software from first principles, spanning compilers, embedded graphics, networking infrastructure, and simulations. I enjoy understanding the layers beneath modern abstractions and designing systems that are efficient, reliable, and maintainable.

## Core Systems Portfolio

### [C02](https://github.com/jackwthake/C02) (Haskell, OCaml, C, Rust, Python)
**A modular compiler toolchain for a custom C-like systems language targeting the 65C02 processor and Ben Eater breadboard computer.**
- Implements a complete compilation pipeline including a Haskell frontend (lexing, parsing, semantic analysis), CFG-based three-address-code IR, C backend/code generation, and OCaml linker.
- Features separate compilation with custom object files, symbol resolution, relocation handling, and ROM image generation for bare-metal execution.
- Designed around a custom ABI, memory model, and calling convention with explicit zero-page allocation and software stack management for constrained 8-bit hardware.

### [shader-works](https://github.com/jackwthake/shader-works) (C)
**A zero-dependency software 3D rendering engine for bare-metal embedded hardware.**
- Implements a fully programmable graphics pipeline from scratch, featuring software-defined vertex and fragment shader emulation.
- Handles raw matrix math, coordinate space transformations, clipping, and rasterization entirely on the CPU without native GPU acceleration.

### [secure-serve](https://github.com/jackwthake/secure-serve) (C++)
**A custom, high-concurrency, multithreaded HTTPS server built from the socket level.**
- Implemented entirely with raw POSIX threads (`pthreads`) and native sockets, utilizing a custom-built manual thread-pool architecture.
- Features low-level OpenSSL bindings to handle cryptographic TLS handshakes and packet processing directly at the bytecode level without web frameworks.

### [ai-survival](https://github.com/jackwthake/ai-survival) (JavaScript)
**A multi-agent, in-browser simulation tracking emergent social and survival dynamics.**
- Models autonomous AI agents dynamically interacting within a shared, high-stakes ecosystem.
- Explores finite state machines, multi-variable feedback loops, and unscripted emergent behaviors in real-time environments.

---

### Technical Competencies
- **Languages:** C, C++, Rust, Haskell, Java, JavaScript, Python, ARM Assembly, 6502 Assembly
- **Low-Level Dev:** Systems Programming, Memory Management, Compiler Design, Embedded Rendering Pipelines
- **Networking:** POSIX Sockets, Concurrency (`pthreads`), TLS/SSL Cryptography

**Contact:** jackwtdev@gmail.com
