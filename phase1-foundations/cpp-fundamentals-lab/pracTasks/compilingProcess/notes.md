# Build Process Exploration

**Goal:** Understand the C++ compilation pipeline step-by-step.

### Commands Practiced

```bash
g++ -E main.cpp -o main.i       # Preprocessing
g++ -S main.i -o main.s         # Assembly generation
g++ -c main.s -o main.o         # Object code
g++ main.o -o main.exe          # Linking to executable
```
