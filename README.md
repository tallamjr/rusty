# Learning Rust 🦀

<img src="https://rustacean.net/assets/rustacean-flat-happy.png" alt="drawing" width="250"/>

### My Learning Rust Roadmap 🗺️

_key_: 🚧 In Progress, ✅ Done

%% 0. 🚧 Setup dev system for rust:
%%     - [Vimspector](https://puremourning.github.io/vimspector-web/#ui-overview)
%%     - [Rust and Neovim - A Thorough Guide and Walkthrough](https://rsdlt.github.io/posts/rust-nvim-ide-guide-walkthrough-development-debug/)
%% 1. ✅ Watch [@zubiarfan's - Learn Rust Programming - Complete Course](https://www.youtube.com/watch?v=BpPEoZW5IiY&t=41523s&ab_channel=freeCodeCamp.org)
%% 2. Go through exercises in [Rust By Practice](https://practice.course.rs/why-exercise.html)
%% 3. Go through [Brown university's interactive version of Rust book](https://rust-book.cs.brown.edu/title-page.html) and complete all quizzes
%% 4. Go through Zero2Production book
%% 5. Go through [Cargo book](https://doc.rust-lang.org/cargo/index.html)
%% 6. Complete [Google's Comprehensive Rust course](https://google.github.io/comprehensive-rust/)
%% 7. Complete embedded rust course
%% 8. Build tinyML demo

| Status | Description                                                                                                                                       | When             |
| ------ | -----------                                                                                                                                       | ----             |
| 🚧     | Setup dev system for rust:                                                                                                                        | w/c 22nd Jan     |
|        | - [Vimspector](https://puremourning.github.io/vimspector-web/#ui-overview)                                                                        |                  |
|        | - [Rust and Neovim - A Thorough Guide and Walkthrough](https://rsdlt.github.io/posts/rust-nvim-ide-guide-walkthrough-development-debug/)          |                  |
| ✅     | Watch [@zubiarfan's - Learn Rust Programming - Complete Course](https://www.youtube.com/watch?v=BpPEoZW5IiY&t=41523s&ab_channel=freeCodeCamp.org) | 22nd - 26th Jan  |
|        | Go through exercises in [Rust By Practice](https://practice.course.rs/why-exercise.html)                                                          | 29th - 31st Jan  |
|        | Go through [Brown university's interactive version of Rust book](https://rust-book.cs.brown.edu/title-page.html) and complete all quizzes         | 1st - 6th Feb    |
|        | Go through Zero2Production book                                                                                                                   | 12th - 16th Feb  |
|        | Go through [Cargo book](https://doc.rust-lang.org/cargo/index.html)                                                                               | 19th - 23rd Feb  |
|        | Complete [Google's Comprehensive Rust course](https://google.github.io/comprehensive-rust/)                                                       | 19th - 23rd Feb  |
|        | Complete embedded rust course                                                                                                                     | w/c 4th Mar      |
|        | Build demo of running tinyML on an embedded device                                                                                                | w/c 11th Mar     |


## Learning the Rust Language 💻

* [ONLINE-BOOK: The Rust Programming Language](https://doc.rust-lang.org/book/title-page.html)
* [ONLINE-BOOK: Rust by Example](https://doc.rust-lang.org/rust-by-example/index.html)
* [ONLINE-EXERCISES: Rustlings](https://github.com/rust-lang/rustlings)

## Embedded Rust 📟

* [Embedded Rust Homepage](https://docs.rust-embedded.org/)
* [ONLINE-BOOK: Embedded Rust Discovery](https://docs.rust-embedded.org/discovery/index.html)
* [ONLINE-BOOK: knurling-rs-book](https://knurling-books.ferrous-systems.com/introduction.html)
* [ONLINE-BOOK: `microrust`](https://droogmic.github.io/microrust/)
* [ONLINE-BOOK: The Embedded Rust Book](https://docs.rust-embedded.org/book/index.html)
* [ONLINE-BOOK: Embedded Rust Workshop 2020 - ferrous-systems](https://embedded-trainings.ferrous-systems.com/)
* [ONLINE-BOOK: Rust-Raspberry-Pi-OS tutorial](https://github.com/rust-embedded/rust-raspberrypi-OS-tutorials)

### Useful Tools and Projects 🧰

* https://github.com/rust-embedded/cargo-binutils : Cargo subcommands to invoke the LLVM tools shipped with the Rust toolchain
* https://github.com/probe-rs/probe-rs : A debugging toolset and library for debugging embedded ARM and RISC-V targets on a separate host
* https://github.com/embassy-rs/embassy : Modern embedded framework, using Rust and async.

#### Cool Projects Written in Rust

* Polars
* Candle

## General Resources 📚

* https://github.com/rust-embedded/awesome-embedded-rust
* https://os.phil-opp.com/ : Writing an OS in Rust Philipp Oppermann's blog
* https://rustbeginners.github.io/awesome-rust-mentors/
* https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg
* https://www.youtube.com/watch?v=bR4nGWmfzTk&list=PLVhhUNGAUIQScqB26DdUq4n1Y2n3auM7X&index=2&t=0s
* Rust, or: how to run a community: https://spacekookie.de/blog/rust-or-how-to-run-a-community/
* Rust 2020: the RFC process and distributions:
  - https://spacekookie.de/blog/rust-2020-the-rfc-process-and-distributions/

### YouTube Gold 📺

* [David Pedersen YT Channel](https://www.youtube.com/channel/UCDmSWx6SK0zCU2NqPJ0VmDQ/videos)
* [Brian Myers AOC 2019 in rust](https://www.youtube.com/playlist?list=PLQXBtq4j4Ozkx3r4eoMstdkkOG98qpBfg)
    - [Github repo](https://github.com/bcmyers/aoc2019)
* [James Munns, from Ferrous Systems, Internet of Streams - IoT with Embedded Rustlang](https://www.youtube.com/playlist?list=PLX44HkctSkTewrL9frlUz0yeKLKecebT1)
    - [Github repo](https://github.com/ferrous-systems/internet-of-streams)
* [Jon Gjengset YT Channel](https://www.youtube.com/channel/UC_iD0xppBwwsrM9DegC5cQQ)
* [Ryan Levik YT Channel](https://www.youtube.com/channel/UCpeX4D-ArTrsqvhLapAHprQ)

### Project Ideas 💭

* Run deep learning model developed in Candle and flash to embedded device using
    the tools above, embassy, or probe-rs etc. Set up toolchain for model
    deployment pipeline on embedded devices using rust.
* Re-implement code in rust for https://github.com/tallamjr/mbms
* [Learning Embedded Rust with Knurling-rs](https://ferrous-systems.com/blog/knurling-sessions-introduction/)
* [Learning Rust: OMG WTF RS – resources to help you get started with Rust](https://ferrous-systems.com/blog/omg-wtf-rs-resources-to-help-you-get-started-with-rust/)
- [How to run Rust on Arduino Uno](https://dev.to/creativcoder/how-to-run-rust-on-arduino-uno-40c0?signin=true)
* Implement Database Internals Algorithms in Rust - Akin to:
    - https://github.com/robertDurst/database-internals
    - https://fasterthanli.me/blog/2020/a-half-hour-to-learn-rust/
    - https://github.com/pingcap/talent-plan/
    - https://university.pingcap.com/talent-plan/
    - https://db.cs.washington.edu/courses.html
* Fundamentals of Operating Systems -->
    - https://www.youtube.com/playlist?list=PLW1yb8L3S1ngGmtKlI5XYcTNQQ1r3xZvq
