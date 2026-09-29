# Nathan McKinney

**RTL / FPGA design and verification** · SystemVerilog · RISC-V · memory systems

I build hardware prototypes and use simulation to show what they currently do. My projects focus on processor pipelines, caches, and low-latency order-book logic.

## Featured projects

| Project | What to explore | Evidence and status |
| --- | --- | --- |
| [Hardware limit order book](https://github.com/nhmckinney/limit-order-book) | Per-price FIFO storage, bid/ask priority encoders, crossing detection, and a Basys3-facing top. | Self-checking Icarus simulation: **14 checks passed**. |
| [RV32I CPU](https://github.com/nhmckinney/riscv-cpu) | Five-stage RTL pipeline with hazard and branch control. | ADD smoke test passes (`x3 = 8`); L1 cache integration is in progress. |
| [Two-way L1 cache](https://github.com/nhmckinney/cache-project) | Tag/data arrays, replacement logic, and miss state machine. | Testbench is present; integrated FPGA validation is a next step. |

Each repository README includes the architecture, current implementation status, and verification details.
