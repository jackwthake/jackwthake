# Hi, I'm Jack

Systems Engineer & Polyglot Programmer. Passionate about building high-performance infrastructure from scratch—ranging from raw C embedded graphics engines and C++ multithreaded servers to Rust compilers and autonomous AI simulations. I don't use frameworks; I write them.

---

## Core Systems Portfolio

### [C02](https://github.com/jackwthake/C02) (C, Rust)
**A C-like compiler and toolchain targeting the 65C02, built for the Ben Eater breadboard kit computer**
- Implements a custom virtual register machine mapping variables to Zero Page memory locations for ultra-low latency execution.
- Features a full custom semantic analyzer, scoping engine (`analyzer_t`), and an explicit down-growing software stack pointer in main RAM.
- Most of it was built one-handed, left hand only, during recovery from wrist surgery on the other.

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
- **Languages:** C, C++, Rust, Java, JavaScript, ARM Assembly, 6502 Assembly
- **Low-Level Dev:** Systems Programming, Memory Management, Compiler Design, Embedded Rendering Pipelines
- **Networking:** POSIX Sockets, Concurrency (`pthreads`), TLS/SSL Cryptography

**Contact:** jackwtdev@gmail.com
