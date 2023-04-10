# Audio programming basis

## Engineering, Physics fundamentals

- Audio concepts

- Sound waves

- Analog and digital audio

- Multi-channel audio

- File formats

## Audio Programming

### What can you program?

**Virtual instruments**: One can program digital instruments that mimic the sounds of real-world instruments such as pianos, guitars, drums, and brass instruments. These virtual instruments can be played using a MIDI controller or programmed into a sequencer.

**Synthesizers**: Synthesizers allow you to create new sounds by manipulating oscillators, filters, and envelopes. There are many types of synthesizers, such as subtractive, additive, FM, and granular synthesizers, each with their unique sound.

**Effects**: Audio effects can be used to modify the sound of a track or an instrument. Some common effects include reverb, delay, chorus, and distortion. One can program custom effects or use pre-existing ones.

**Sample libraries**: Sample libraries contain recordings of real-world instruments or sounds. One can program instruments using these samples, allowing them to create realistic sounding instruments.

The concept of loops is an important part of audio programming, especially in electronic music production. A loop is a short section of audio that can be repeated continuously, creating a rhythmic pattern. Loops can be created using digital audio workstations (DAWs) or using specialized software like Ableton Live.

Loops can be used in a variety of ways in audio programming, including:

Creating beats: Loops can be used to create the rhythm section of a track, including drums, percussion, and basslines.

Building up arrangements: Loops can be arranged and layered to create complex, evolving arrangements.

Remixing: Loops can be used as the basis for remixes, allowing you to add your own production and creative touches to existing tracks.

Live performance: Loops can be triggered and manipulated in real-time during live performances, allowing for improvisation and experimentation.


**DSL**: Many digital audio workstations (DAWs) and audio programming environments have scripting languages that allow you to program custom tools, such as automatic gain staging, randomization of parameters, and more.

### What skills do you need?

#### C


Variables and data types: integers, floating-point numbers, and characters, as well as how to declare and initialize variables.

Control structures: control structures such as if/else statements, for and while loops, and switch/case statements.

Functions: how to define and call functions in C, as well as how to pass arguments and return values.

Pointers and memory management: good understanding of how pointers work in C, and how to use them to manipulate data structures in memory.

File I/O: how to read and write files in C, as this is often an essential part of audio programming.

Libraries and APIs: how to use external libraries and APIs in C, as this can save you a lot of time and effort in your programming.


#### C++

- OOP:  create classes and objects, encapsulate data and functionality, and use inheritance and polymorphism to create flexible and reusable code.

- Templates: write generic code that can be used with different data types and algorithms.

- STL: data structures and algorithms in the STL, including containers such as vectors, lists, and maps, as well as algorithms such as sorting and searching.

- Memory management: low-level memory management features such as pointers and references, as well as higher-level features such as smart pointers and memory pools, which can help managing memory efficiently in audio applications.

- Exception handling: ways to handle errors

- Multi-threading: features that allow one to write parallel code that can take advantage of multi-core CPU/processors and improve the performance of audio applications.

#### Rust

Ownership and borrowing: Rust's ownership and borrowing system is a unique feature of the language that helps prevent common errors such as null pointer references and data races. You should be familiar with how to declare and use variables and structures in Rust, as well as how to manage ownership and borrowing.

Structs and enums: define custom data types using structs and enums, which can be used to represent complex data structures in audio applications.

Traits: Rust's trait system is like C++'s Polymprphism, it allows us to define behavior that can be shared across different types, providing a flexible and composable way to define functionality in audio applications.

Concurrency: Rust provides powerful concurrency features, including lightweight threads (known as "tasks") and message passing between tasks, which can be used to write highly concurrent and scalable audio applications.

Memory safety: memory safety guarantees without requiring a garbage collector, which can be useful in real-time audio applications where low latency is critical.

Package management: Rust has a built-in package manager called Cargo, which can be used to manage dependencies and build and distribute Rust projects.

Whichever language you work primarily with, keep in mind, knowledge of digital signal processing (DSP) concepts such as Fourier analysis, filtering, and modulation can be helpful in audio programming. Rust also has several libraries and frameworks for audio programming, such as RustPortAudio, RustFFT, and rust-vst, that can help you get started with audio programming in Rust.

## Audio API, Interfaces

Standard stuff: 

- CLI, File system, 

- Processes and services
a good understanding of how processes and services work in Linux, including how to start and stop them, view their status, and manage their resources.

- Package management on your distros

- Know how to interact with shells

- Network configuration: know how to configure network settings on Linux, including setting up network interfaces, configuring IP addresses, and setting up firewall rules.

- Audio subsystems: Linux has several audio subsystems, such as ALSA and JACK, that are used for audio input/output and processing.


## Starter projects

* Basic Polyphonic synthesizer with presets, save/load, filters, oscillators, mixers and envelopes

* A basic EQ plugin with by-passable filters and EQ curve visualization.

* Plugins: VST, VST3, AU, AXX, Effects.

Personally, I worked with Scaler 2, which is available as a plugin in several different formats, including VST, AU, and AAX. This means that it can be used in a variety of different DAWs, including Logic Pro, Ableton Live, Pro Tools, and others, depending on the specific format that is installed.

When Scaler 2 is installed, it should automatically detect the plugin formats that are available on the system and install the appropriate versions of the plugin. This allows Scaler 2 to be used in different DAWs and on different operating systems, making it a versatile tool for music composition and production.

## Knowledge

* Concurrence and thread safety

* UI, UX and GUI development

* Optimizations including SIMD
Design patterns

* Lock-free data structures vs not lock-free data structures
Algorithm development and memory management

* Digital Signal Processing (DSP).


## Reference

* The audioprogramming youtube

* [JUCE](https://docs.juce.com/develop/index.html)




