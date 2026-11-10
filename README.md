# Hi, I'm Grant

I'm a senior CS student at UIC (graduating December 2026). This summer I worked
as a research intern in UIC's SySec lab on automated vulnerability repair,
building pipelines that use LLM agents to patch real-world security
bugs in open source software.

I'm into systems programming, performance-focused code, and lately, applying that 
systems mindset to AI agent infrastructure.

---

## Skills
![My Skills](https://skillicons.dev/icons?i=cpp,c,python,docker,linux,cmake,java,git)

---

## Currently Working On
- **[Real-Time Audio Visualizer](https://github.com/grantjlk/grantAudioVisualizer)** – Multithreaded
C++ audio visualizer (OpenGL, PortAudio, FFTW) with a lock-free audio pipeline built on my own SPSC
ring buffer, benchmarked against PortAudio's. 0 audio dropouts and ~0.3% of the frame budget used.
- **[Distributed Shortest Paths](https://github.com/grantjlk/distributed-sssp-mpi)** – Delta-stepping
in C++ and OpenMPI on million-node graphs, measuring where communication limits scaling.
- **Job Hunt** – Looking for full-time systems/backend C++ roles starting
December 2026 or later. Say hi.

## Previously
- **Automated Vulnerability Repair** – Summer research at UIC's SySec lab: evaluation harnesses
and LLM agent pipelines that automatically patch OSS-Fuzz vulnerabilities (Claude, OSS-CRS, Docker).

---

## Project Showcase

### Real-Time Audio Visualizer
> Low-latency audio visualization in C++ with lock-free threading, FFT analysis,
> and OpenGL rendering. Audio moves between threads through a custom SPSC ring buffer,
> about 10x faster than its first version and clean under ThreadSanitizer.

<img src="https://raw.githubusercontent.com/grantjlk/grantAudioVisualizer/main/assets/demo.gif" width="300"/>

[🔗 View Repository](https://github.com/grantjlk/grantAudioVisualizer) · [📄 Ring buffer write-up](https://github.com/grantjlk/grantAudioVisualizer/blob/main/docs/ring-buffer.md)

---

### Distributed Shortest Paths with MPI
> Delta-stepping shortest paths in C++ and OpenMPI, where each rank loads only its slice
> of a million-node graph. Up to 2.7x faster than sequential Dijkstra on 6 cores,
> verified exact against it.

<img src="https://raw.githubusercontent.com/grantjlk/distributed-sssp-mpi/main/experiments/figures/speedup.png" width="300"/> 

[🔗 View Repository](https://github.com/grantjlk/distributed-sssp-mpi)

---

Thanks for stopping by! Feel free to connect with me:

📫 [grantjlk@gmail.com](mailto:grantjlk@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/grantlk)
