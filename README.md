# pointer-warfare

> Compact C & Assembly notes, pointer diagrams, and tiny reproducible labs.

## Focus
- Pointer arithmetic, aliasing, and memory model experiments
- Calling conventions (SysV x86_64), stack frames, and frame-pointer analysis
- Small C/ASM examples with annotated memory maps and gdb sessions

## Repo layout
- `notes/` — concise markdown summaries and reference diagrams  
- `examples/` — minimal C/ASM programs + Makefile  
- `labs/` — small numbered labs (lab01_stack, lab02_heap, ...)  

## Getting started
```bash
# clone
git clone https://github.com/OneMartiniTuringRE/pointer-warfare.git
cd pointer-warfare/examples
make
./hello
