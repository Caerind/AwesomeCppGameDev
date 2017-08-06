# Awesome list of C++ GameDev project

This list is a work in progress.    
I have to filter it now, cause a lot of libraries here does the same things.  
I want to store here only good quality libraries. If you want to add projects here, do not push a request, open an issue and I'll check.  
C++, C, Lua, and only few exceptions for other languages. 

- [C++](#C++)
- [Libraries](#Libraries)
- [Engines](#Engines)
- [Maths](#Maths)
- [Graphics](#Graphics)
- [Audio](#Audio)
- [Physics](#Physics)
- [Networking](#Networking)
- [AI](#AI)
- [Scripting](#Scripting)
- [GameProgramming](#GameProgramming)
- [Tools](#Tools)
- [GameDesign](#GameDesign)
- [Awesome](#Awesome)
- [GameProgrammerPath](#GameProgrammerPath)
- [Tutorials](#Tutorials)


# List of projects : 

## C++
- Bits
  - [tinybits](https://github.com/r-lyeh/tinybits) : Tiny bits and useful snippets that I keep using everywhere (C, C++)
- MultiThreading
  - [dwThreadPool](https://github.com/diharaw/dwThreadPool) : A simple C++ 11 based Thread Pool implementation with no external dependencies
  - [Scheduler](https://github.com/Bosma/Scheduler) : Modern C++ Scheduling Library
  - [ThreadPool](https://github.com/nbsdx/ThreadPool) : Lightweight, Generic, Pure C++11 ThreadPool
  - [ThreadPool](https://github.com/progschj/ThreadPool) : A simple C++11 Thread Pool implementation
  - [CTPL](https://github.com/vit-vit/CTPL) : Modern and efficient C++ Thread Pool Library
  - [thread-pool-cpp](https://github.com/inkooboo/thread-pool-cpp) : High performance C++11 thread pool
  - [jobxx](https://github.com/seanmiddleditch/jobxx) : Lightweight C++ task system
  - [delegates](https://github.com/mamedev/delegates) : Fast delegates implementation
  - [Awl](https://github.com/Yalir/Awl) : Awl (Asynchronous Work Library) is a C++ library that aims at making parallel programming as easy as possible.
  - [FastDelegate](https://github.com/kaidokert/FastDelegate) : C++11 version of Don Clugston's FastDelegate library, by Ceniza.
  - [termite-jobs](https://github.com/septag/termite-jobs) : Fast, multiplatform fiber based job dispatcher based on Naughty Dogs' GDC2015 talk.
- Memory
  - [jemalloc](https://github.com/jemalloc/jemalloc) : jemalloc is a general purpose malloc(3) implementation that emphasizes fragmentation avoidance and scalable concurrency support.
  - [rpmalloc](https://github.com/rampantpixels/rpmalloc) : Public domain cross platform lock free thread caching 16-byte aligned memory allocator implemented in C
  - [flatbuffers](https://github.com/google/flatbuffers) : Memory Efficient Serialization Library
- Parsers
  - [pugixml](https://github.com/zeux/pugixml) : Light-weight, simple and fast XML parser for C++ with XPath support
  - [json](https://github.com/nlohmann/json) : JSON for Modern C++
  - [simpleini](https://github.com/brofield/simpleini) : Cross-platform C++ library providing a simple API to read and write INI-style configuration files
  - [ini](https://github.com/rxi/ini) : A tiny ANSI C library for loading .ini config files
  - [yaml-cpp](https://github.com/jbeder/yaml-cpp) : A YAML parser and emitter in C++
  - [pureconfig](https://github.com/pureconfig/pureconfig) : A boilerplate-free library for loading configuration files
  - [SimpleJSON](https://github.com/nbsdx/SimpleJSON) : Simple C++ JSON library
  - [ViliData](https://github.com/Sygmei/ViliData) : A nice and readable data format !
  - [juson](https://github.com/wgtdkp/juson) : lightweight json parser in c
  - [jsonpack](https://github.com/ymglez/jsonpack) : JsonPack is a high-performance and extremely easy-to-use JSON serialization library
- FileSystem
  - [dirent](https://github.com/tronkko/dirent) : C/C++ library for retrieving information on files and directories
  - [tinydir](https://github.com/cxong/tinydir) : Lightweight, portable and easy to integrate C directory and file reader
  - [cfgpath](https://github.com/Malvineous/cfgpath) : Cross platform C header for obtaining paths to user configuration files and directories
  - [filesystem](https://github.com/wjakob/filesystem) : A tiny self-contained path manipulation library for C++
  - [apathy](https://github.com/dlecocq/apathy) : C++ Path Manipulation
- Reflection & Serialization
  - [MetaStuff](https://github.com/eliasdaler/MetaStuff) : Code I use in my game for all serialization/deserialization/introspection stuff
  - [cpgf](https://github.com/cpgf/cpgf) : cpgf library is a cross platform C++ library for callback, reflection, serialization and script binding.
  - [iguana](https://github.com/qicosmos/iguana) : universal serialization engine
  - [cpp-generic-serialize](https://github.com/xdbr/cpp-generic-serialize) : C++11 Header-only generic binary-serialization for arbitrary types (and nested containers)
  - [reflect](https://github.com/xyzdev/reflect) : Reflection and serialization in C++
  - [CPP-Reflection](https://github.com/AustinBrunkhorst/CPP-Reflection) : C++ Reflection Parser / Runtime Skeleton
  - [rpoco](https://github.com/whizzter/rpoco) : (R)eflect (P)lain (O)ld (C)++ (O)bjects, is a small header based reflection system that supports JSON serialization,etc
  - [cereal](https://github.com/USCiLab/cereal) : A C++11 library for serialization
- Metaprogramming
  - [STT-C-Compile-Time-Snake](https://github.com/mattbierner/STT-C-Compile-Time-Snake) : Snake/Nibbler implementation using C++ template metaprogamming
  - [brigand](https://github.com/edouarda/brigand) : Instant compile time C++ 11 metaprogramming library
- Functionnal Programming
  - [Fit](https://github.com/pfultz2/Fit) : C++ function utility library
  - [fixed_size_function](https://github.com/pmed/fixed_size_function) : Fixed size function wrapper like std::function
  - [Function](https://github.com/rigtorp/Function) : Heap allocation free version of C++11 std::function
  - [any_function](https://github.com/sgorsten/any_function) : any_function is a functional counterpart to std::any
  - [functionIdentifier](https://github.com/Asphox/functionIdentifier) : functionIdentifier
  - [reactive](https://github.com/tower120/reactive) : Simple, non intrusive reactive programming library for C++. (Events + Observable Properties + Reactive Properties)
- Patterns
  - [patterns](https://github.com/mpark/patterns) : Pattern Matching in C++
- Containers
  - [EASTL](https://github.com/electronicarts/EASTL) : EASTL stands for Electronic Arts Standard Template Library
  - [flat_hash_map](https://github.com/skarupke/flat_hash_map) : A very fast hashtable
  - [hashMap](https://github.com/kshk123/hashMap) : A concurrent thread-safe hash map implemented in C++
  - [hopscotch-map](https://github.com/Tessil/hopscotch-map) : C++ implementation of a fast hash map using hopscotch hashing
  - [devector](https://github.com/orlp/devector) : Resizable contiguous sequence container with fast appends on either end.
  - [MPMCQueue](https://github.com/rigtorp/MPMCQueue) : A bounded multi-producer multi-consumer lock-free queue written in C++11
- Logging
  - [loguru](https://github.com/emilk/loguru) : A lightweight C++ logging library
  - [Frlog](https://github.com/Cloaked9000/Frlog) : A tiny, fast, thread safe, easy to use logging class.
- Signals and Slots
  - [SISL](https://github.com/Asphox/SISL) : a user-friendly , light, and fast library for the signal/slot pattern in standard C++11
  - [nano-signal-slot](https://github.com/NoAvailableAlias/nano-signal-slot) : Pure C++11 Signals and Slots
  - [signal11](https://github.com/amc522/signal11) : C++11 signal slot implementation
- Profilers
  - [brofiler](https://github.com/bombomby/brofiler) : C++ Profiler For Games
  - [profi](https://github.com/stoyannk/profi) : A light-weight C++ profiling library
  - [easy_profiler](https://github.com/yse/easy_profiler) : Lightweight profiler library for c++
  - [yardstick](https://github.com/seanmiddleditch/yardstick) : C++ Instrumented Profiling
- Cryptography and Hashing and Compression
  - [miniz](https://github.com/richgel999/miniz) : Single C source file zlib-replacement library
  - [cocoa](https://github.com/r-lyeh/cocoa) : Cocoa is an uniform hashing library with no dependencies that provides interface for CRC32, CRC64, GCRC, RS, JS, PJW, ELF, BKDR, SBDM, DJB, DJB2, BP, FNV, FNV1a, AP, BJ1, MH2, SHA1, SFH (C++11)
  - [bundle](https://github.com/r-lyeh/bundle) : Bundle, an embeddable compression library: DEFLATE, LZMA, LZIP, BZIP2, ZPAQ, LZ4, ZSTD, BROTLI, BSC, CSC, BCM, MCM, ZMOLLY, ZLING, TANGELO, SHRINKER, CRUSH, LZJB and SHOCO streams in a ZIP file (C++03)(C++11)
  - [lz4](https://github.com/lz4/lz4) : Extremely Fast Compression algorithm
  - [andyzip](https://github.com/andy-thomason/andyzip) : A fast and compact modern C++ (header only) zip, bzip2 and brotli library
  - [luazen](https://github.com/philanc/luazen) : simple compression, encoding and cryptographic functions
  - [lizard](https://github.com/inikep/lizard) : Lizard (formerly LZ5) is an efficient compressor with very fast decompression
  - [cryptopp](https://github.com/weidai11/cryptopp) : free C++ class library of cryptographic schemes
- Testing
  - [Catch](https://github.com/philsquared/Catch) : A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD - using C++98, C++03, C++11, C++14 and later
  - [benchmark](https://github.com/google/benchmark) : A microbenchmark support library
  - [mettle](https://github.com/jimporter/mettle) : A C++14 unit test framework
- SystemAPI
  - [sfd](https://github.com/rxi/sfd) : A small C library for opening a file dialog
  - [Boxer](https://github.com/aaronmjacobs/Boxer) : Boxer is a simple library that allows for easy cross-platform creation of message boxes / alerts / what have you.
- C++ Extensions
  - [any](https://github.com/PaulHowes/any) : A simple variant type for C++
  - [0xABAD1DEA](https://github.com/graphitemaster/0xABAD1DEA) : Static global objects with constructors and destructors made useful in C++
  - [modern-cpp-features](https://github.com/AnthonyCalandra/modern-cpp-features) : A cheatsheet of modern C++ language and library features.
  - [better-enums](https://github.com/aantron/better-enums) : Compile-time enum to string, iteration, in a single header file
  - [smartenum](https://github.com/therocode/smartenum) : Macros for declaring enums in C++ that include to_string conversion and looping through all enum values
  - [immutable-cpp](https://github.com/rsms/immutable-cpp) : Persistent immutable data structures for C++
  - [liberasure](https://github.com/atomgalaxy/liberasure) : A no-dependencies C++ extensible type erasure library
  - [atria](https://github.com/Ableton/atria) : A toolkit for modern C++ development
  - [cpp-defer](https://github.com/xdbr/cpp-defer) : defer action to end of scope (C++11 only / header-only)
  - [FastDynamicCast](https://github.com/tobspr/FastDynamicCast) : Fast dynamic cast in C++ for MSVC, outperforming the regular dynamic cast by up to 25 times
- Command Line Arguments
  - [cxxopts](https://github.com/jarro2783/cxxopts) : Lightweight C++ command line option parser
  - [gflags](https://github.com/gflags/gflags) : The gflags package contains a C++ library that implements commandline flags processing
  - [SLACC](https://github.com/RippeR37/SLACC) : Simple Lightweight Adaptable Command Console
  - [Arguments](https://github.com/dabbertorres/Arguments) : Command line argument handling for C++
- Regex
  - [CppVerbalExpressions](https://github.com/VerbalExpressions/CppVerbalExpressions) : C++ regular expressions made easy
- Date
  - [date](https://github.com/HowardHinnant/date) : A date and time library based on the C++11/14/17 'chrono' header
- [PubBus](https://github.com/eXpl0it3r/PubBus) : A simple implementation of a MessageBus.
- [yauid](https://github.com/lexborisov/yauid) : A decentralized unique ID generator (int64)
- [nakama](https://github.com/heroiclabs/nakama) : Distributed server for social and realtime games and apps.
- [cppast](https://github.com/foonathan/cppast) : Library to parse and work with the C++ AST
- [unify](https://github.com/r-lyeh/unify) : A C++11 function to normalize resource identificators
- [cxx-eventemitter](https://github.com/0x00A/cxx-eventemitter) : A minimalist event emitter for C++[1z].
- [unicode](https://github.com/dabbertorres/unicode) : C++ UTF-8 Strings and Utilities
- [Nimble](https://github.com/dmsovetov/Nimble) : Nimble is a header-only utility library.
- [turf](https://github.com/preshing/turf) : Configurable C++ platform adapter
- [forvor](https://github.com/stolk/forvor) : Fortune's Voronoi Generator


## Libraries
- [libdhcore](https://github.com/septag/libdhcore) : Lightweight, performance oriented, Core library for 'C' programmers
- [tacent](https://github.com/bluescan/tacent) : A collection of C++ source files designed to be the basis for a game engine or other interactive project.
- [tinyheaders](https://github.com/RandyGaul/tinyheaders) : Collection of one-file C/C++ libraries with no dependencies, primarily used for games
- [foundation_lib](https://github.com/rampantpixels/foundation_lib) : Cross-platform public domain foundation library in C
- [ZeroTolerance](https://github.com/jharler/ZeroTolerance) : Collection of single header file libraries for C/C++ development, with a focus on games.
- [chobo-shl](https://github.com/Chobolabs/chobo-shl) : A collection of single-header C++11 libraries by Chobolabs
- [ClanLib](https://github.com/sphair/ClanLib) : ClanLib is a cross platform C++ toolkit library
- [kit](https://github.com/flipcoder/kit) : C++11 libs: coroutines, channels, reactive/signals, timelines, alarms, logging, args, etc.
- [TrinityCore](https://github.com/TrinityCore/TrinityCore) : TrinityCore Open Source MMO Framework
- [stb](https://github.com/nothings/stb) : stb single-file public domain libraries for C/C++
- [single_file_libs](https://github.com/nothings/single_file_libs) : List of single-file C/C++ libraries.
- [folly](https://github.com/facebook/folly) : An open-source C++ library developed and used at Facebook.
- [fatal](https://github.com/facebook/fatal) : Fatal is a library for fast prototyping software in modern C++. 
- [kit](https://github.com/haikarainen/kit) : C++ framework for game development
- [slibs](https://github.com/yui0/slibs) : Single file libraries for C/C++
- [CSteamworks](https://github.com/rlabrecque/CSteamworks) : C bindings for Steamworks
- [cartographer](https://github.com/googlecartographer/cartographer) : Cartographer is a system that provides real-time simultaneous localization and mapping (SLAM) in 2D and 3D across multiple platforms.
- [game-jolt-api-cpp-library](https://github.com/MausGames/game-jolt-api-cpp-library) : C++ Library to connect games with Game Jolt


## Engines
- [Urho3D](https://github.com/urho3d/Urho3D) : Cross-platform 2D and 3D game engine.
- [BansheeEngine](https://github.com/BearishSun/BansheeEngine) : Modern C++14 game engine with Vulkan support, fully featured editor and C# scripting
- [Serious-Engine](https://github.com/Croteam-official/Serious-Engine) : An open source version of a game engine developed by Croteam for the classic Serious Sam games
- [NazaraEngine](https://github.com/DigitalPulseSoftware/NazaraEngine) : Nazara Engine is a fast, complete, cross-platform, object-oriented API
- [Lugdunum](https://github.com/Lugdunum3D/Lugdunum) : A modern cross-platform 3D engine built with Vulkan, glTF 2.0 and modern C++14
- [darkhammer](https://github.com/septag/darkhammer) : darkHAMMER is a lightweight, open-source, multiplatform game engine
- [FishEngine](https://github.com/yushroom/FishEngine) : Simple, Unity-like Game Engine.
- [Intrinsic](https://github.com/begla/Intrinsic) : Intrinsic is a Vulkan based cross-platform game and rendering engine. 
- [LumixEngine](https://github.com/nem0/LumixEngine) : 3D Game Engine
- [AVA](https://github.com/r-lyeh/AVA) : A tiny 3D game engine in C; with C++ and Lua interfaces. Written in 32 random ̷d̷a̷y̷s̷ m̷o̷n̷t̷h̷s̷ years.
- [haxe](https://github.com/HaxeFoundation/haxe) : Haxe - The Cross-Platform Toolkit
- SFML based engines
  - [Swift2](https://github.com/dabbertorres/Swift2) : A SFML-backed game framework.
  - [SchiffbruchEngine](https://github.com/Lirrec/SchiffbruchEngine) : SchiffbruchEngine
  - [SFBL](https://github.com/Made4Dev/SFBL) : SFML Box2D Light
  - [ObEngine](https://github.com/Sygmei/ObEngine) : 2D Game Engine with Lua Scripting made on top of SFML !


## Maths
- [vectorial](https://github.com/scoopr/vectorial) : Vector math library with NEON/SSE support
- [mathfu](https://github.com/google/mathfu) : C++ math library developed primarily for games focused on simplicity and efficiency.
- [xsimd](https://github.com/QuantStack/xsimd) : C++ wrappers for SIMD intrinsics
- [hlml](https://github.com/fmutant/hlml) : vectorized high-level math library
- [cmath3d](https://github.com/jpreiss/cmath3d) : 3d math library for C. Vectors, 3x3 matrices, quaternions.
- [eigen](https://github.com/RLovelett/eigen) : Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
- [xo-math](https://github.com/xoorath/xo-math) : xo-math is an open source single header file module for optimized game math. C++11 or newer required.
- Noise
  - [FastNoiseSIMD](https://github.com/Auburns/FastNoiseSIMD) : C++ SIMD Noise Library
  - [FastNoise](https://github.com/Auburns/FastNoise) : Fast C++ Noise Library
  - [SimplexNoise](https://github.com/simongeilfus/SimplexNoise) : Collection of Simplex Noise functions
  - [SimplexNoise](https://github.com/PawelWorwa/SimplexNoise) : Cpp port for Simplex Noise library

## Graphics
- SFML
  - [SFML](https://github.com/SFML/SFML) : Simple and Fast Multimedia Library
  - [SFML-GameDev](https://github.com/SFML/SFML-Game-Development-Book) : Full and up-to-date source code of the chapters of the "SFML Game Development" book
  - [Thor](https://github.com/Bromeon/Thor) : SFML Extension with various game programming features, like particles, animations, vector operations
  - [SFML-Book](https://github.com/Krozark/SFML-book) : SFML Blueprint book, source code
  - [LTBL2](https://github.com/222464/LTBL2) : A 2D dynamic lighting system with accurate soft shadows.
  - [light_ungod](https://github.com/Ung0d/light_ungod) : A reimplementation of the LTBL2-framwork.
  - [RichText](https://github.com/skyrpex/RichText) : Rich text class for SFML2
  - [QSFML](https://github.com/KoczurekK/QSFML) : Library that integrates SFML 2.x.x and Qt 5.x.x, includes event handling etc.
  - [SFGUI](https://github.com/TankOs/SFGUI) : Simple and Fast Graphical User Interface
  - [imgui-sfml](https://github.com/eliasdaler/imgui-sfml) : ImGui binding for use with SFML
  - [TGUI](https://github.com/texus/TGUI) : An easy to use cross-platform c++ GUI for SFML
  - [SimplGUI](https://github.com/victorlevasseur/SimplGUI) : SimplGUI is simple GUI library for SFML. It provides simple widgets that can be used independently.
  - [Motion](https://github.com/zsbzsb/Motion) : Complete video and audio player for SFML
  - [sfeMovie](https://github.com/Yalir/sfeMovie) : sfeMovie is a simple C++ library that lets you play movies in SFML based applications.
- OpenGL
  - [magnum](https://github.com/mosra/magnum) : C++14 and OpenGL graphics engine http://magnum.graphics/
  - [LLGL](https://github.com/LukasBanana/LLGL) : Low Level Graphics Library (LLGL) is a thin abstraction layer for modern graphics APIs such as OpenGL, Direct3D, and Vulkan
  - [TinyWindow](https://github.com/ziacko/TinyWindow) : a cross platform (Linux and Windows) OpenGL window library in a single header
  - [GLUL](https://github.com/RippeR37/GLUL) : OpenGL Utility Library.
  - [glgen](https://github.com/MetricPanda/glgen) : Minimal OpenGL extension loader
  - [ToGL](https://github.com/ValveSoftware/ToGL) : Direct3D to OpenGL abstraction layer
  - [glslang](https://github.com/KhronosGroup/glslang) : Khronos reference front-end for GLSL and ESSL, and sample SPIR-V generator
  - [glbinding](https://github.com/cginternals/glbinding) : A C++ binding for the OpenGL API, generated using the gl.xml specification.
  - [thebookofshaders](https://github.com/patriciogonzalezvivo/thebookofshaders) : Step-by-step guide through the abstract and complex universe of Fragment Shaders.
  - [glsl-optimizer](https://github.com/aras-p/glsl-optimizer) : GLSL optimizer based on Mesa's GLSL compiler. Used in Unity for mobile shader optimization.
  - [oglplus](https://github.com/matus-chochlik/oglplus) : OGLplus is a collection of open-source, cross-platform libraries which implement an object-oriented facade over the OpenGL
- Vulkan
  - [Vookoo](https://github.com/andy-thomason/Vookoo) : A set of utilities for taking the pain out of Vulkan in header only modern C++
  - [vulkan_minimal_compute](https://github.com/Erkaman/vulkan_minimal_compute) : Minimal Example of Using Vulkan for Compute Operations.
  - [VulkanSponza](https://github.com/SaschaWillems/VulkanSponza) : Deferred Vulkan rendering playground using Crytek's Sponza scene
  - [Vulkan](https://github.com/SaschaWillems/Vulkan) : Examples and demos for the new Vulkan API
  - [Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) : Open-Source Vulkan C++ API
  - [VulkanTutorial](https://github.com/Overv/VulkanTutorial) : Tutorial for the Vulkan graphics and compute API
  - [laugh_engine](https://github.com/jian-ru/laugh_engine) : A Vulkan implementation of real-time PBR renderer
  - [VulkanResources](https://github.com/jcoder58/VulkanResources) : A list of resources for learning Vulkan
  - [Vulkan-Docs](https://github.com/KhronosGroup/Vulkan-Docs) : The Vulkan API Specification and related tools
- GUI
  - [imgui](https://github.com/ocornut/imgui) : Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies
  - [nuklear](https://github.com/vurtun/nuklear) : A single-header ANSI C gui library
- Animation
  - [acl](https://github.com/nfrechette/acl) : Animation Compression Library
  - [ozz-animation](https://github.com/guillaumeblanc/ozz-animation) : Open source c++ skeletal animation library and toolset
- [ogre](https://github.com/OGRECave/ogre) : scene-oriented, flexible 3D engine written in C++
- [tinygizmo](https://github.com/ddiakopoulos/tinygizmo) : An immediate-mode 3D gimzo (translation, rotation, scale) in ~1200 LoC
- [fplbase](https://github.com/google/fplbase) : Cross platform low level rendering and I/O library
- [real-time-pbr](https://github.com/brkho/real-time-pbr) : This is a physically based real-time renderer made for learning purposes.
- [draco](https://github.com/google/draco) : Draco is a library for compressing and decompressing 3D geometric meshes and point clouds
- [Shadows](https://github.com/TheRealMJP/Shadows) : A sample app that demonstrates several techniques for rendering real-time shadow maps
- [moderngpu](https://github.com/moderngpu/moderngpu) : Patterns and behaviors for GPU computing
- [bgfx](https://github.com/bkaradzic/bgfx) : Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library
- [Simd](https://github.com/ermig1979/Simd) : C++ image processing library with using of SIMD: SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, AVX, AVX2, VMX(Altivec) and VSX(Power7), NEON for ARM
- [reshade](https://github.com/crosire/reshade) : An advanced, generic post-processing injector for games and video software.


## Audio
- [steam-audio](https://github.com/ValveSoftware/steam-audio) : Steam Audio
- [soloud](https://github.com/jarikomppa/soloud) : Free, easy, portable audio engine for games
- [kfr](https://github.com/kfrlib/kfr) : Fast, modern C++ DSP framework, FFT, Audio Sample Rate Conversion, FIR/IIR/Biquad Filters (SSE, AVX, ARM NEON)
- Audio Synthesis and Speech recognition
  - [pocketsphinx](https://github.com/cmusphinx/pocketsphinx) : PocketSphinx is a lightweight speech recognition engine
  - [stk](https://github.com/thestk/stk) : The Synthesis ToolKit in C++ (STK) is a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language
  - [Tonic](https://github.com/TonicAudio/Tonic) : Easy and efficient audio synthesis in C++


## Physics
- 2D Physics
  - [Box2d](https://github.com/erincatto/Box2D) : Box2D is a 2D physics engine for games
  - [Box2D](https://github.com/eXpl0it3r/Box2D) : C++ port of Box2D
  - [b2dJson](https://github.com/iforce2d/b2dJson) : Utilities to load scenes created by the R.U.B.E Box2D editor
  - [liquidfun](https://github.com/google/liquidfun) : 2D physics engine for games
- 3D Physics
  - [nudge](https://github.com/rasmusbarr/nudge) : A small data-oriented and SIMD-optimized 3D rigid body physics library.
  - [GridFluidSim3D](https://github.com/rlguy/GridFluidSim3D) : A PIC/FLIP fluid simulation based on the methods found in "Fluid Simulation for Computer Graphics"
  - [RealtimeWater](https://github.com/hpatjens/RealtimeWater) : The water simulation is based on the method that Fischer proposes for 2D heightfields


## Networking
- TCP/UPD/HTTP
  - [SFNUL](https://github.com/binary1248/SFNUL) : Simple and Fast Network Utility Library
  - [asio](https://github.com/chriskohlhoff/asio) : Asio C++ Library
  - [tacopie](https://github.com/Cylix/tacopie) : C++ TCP Library
  - [cxxhttp](https://github.com/ef-gy/cxxhttp) : Asynchronous, Header-only C++ HTTP-over-(TCP|UNIX Socket|STDIO) Library
  - [libclub](https://github.com/inetic/libclub) : Lightweight Peer-to-Peer networking engine for real time applications
  - [net11](https://github.com/whizzter/net11) : Simple embeddable C++11 async tcp,http and websocket serving.
  - [uWebSockets](https://github.com/uNetworking/uWebSockets) : Tiny WebSockets
  - [webby](https://github.com/deplinenoise/webby) : A tiny webserver for game development
  - [minihttp](https://github.com/fgenesis/minihttp) : A minimal 2-file (cpp+h) TCP & HTTP client implementation. Supports GET & simple POST. Optional SSL via PolarSSL/mbedTLS.
- SQL
  - [SQLiteCpp](https://github.com/SRombauts/SQLiteCpp) : SQLiteC++ (SQLiteCpp) is a smart and easy to use C++ SQLite3 wrapper.
  - [NLDatabase](https://github.com/catnapgames/NLDatabase) : Lightweight C++ wrapper for SQLite
  - [sqlpp11](https://github.com/rbock/sqlpp11) : A type safe SQL template library for C++
- RPC
  - [Game-Net](https://github.com/sp4cerat/Game-NET) : RPC Network Library for Multiplayer Games
  - [rpclib](https://github.com/rpclib/rpclib) : rpclib is a modern C++ msgpack-RPC server and client library
  - [libjson-rpc-cpp](https://github.com/cinemast/libjson-rpc-cpp) : C++ framework for json-rpc (json remote procedure call)
  - [cpp-ORM](https://github.com/Krozark/cpp-ORM) : A project to create a simple ORM


## AI
- Neural Network & Deep Learning
  - [darknet](https://github.com/pjreddie/darknet) : Convolutional Neural Networks
  - [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) : header only, dependency-free deep learning framework in C++14
- Path
  - [MicroPather](https://github.com/leethomason/MicroPather) : MicroPather is a path finder and A* solver 
  - [lib_2d](https://github.com/I3ck/lib_2d) : A c++ library for paths defined by points within the 2d space


## Scripting
- [scriptorium](https://github.com/r-lyeh/scriptorium) : Game Scripting Languages benchmarked
- Lua
  - [sol2](https://github.com/ThePhD/sol2) : Sol v2.0 - a C++ <-> Lua API wrapper with advanced features and top notch performance - is here, and it's great! 
  - [lualite](https://github.com/user1095108/lualite) : a one header library for creating Lua bindings to C++
  - [lua-intf](https://github.com/SteveKChiu/lua-intf) : A binding between C++11 and Lua language
  - [Selene](https://github.com/jeremyong/Selene) : Simple C++11 friendly header-only bindings to Lua
  - [LuaInPractice2SourceCode](https://github.com/eliasdaler/LuaInPractice2SourceCode) : Using Lua with C++ in Practice part 2 source code
- [duktape](https://github.com/svaarala/duktape) : Duktape - embeddable Javascript engine with a focus on portability and compact footprint
- [ChaiScript](https://github.com/ChaiScript/ChaiScript) : Embedded Scripting Language Designed for C++
- [zippypy](https://github.com/shooshx/zippypy) : A simple, lightweight Python 2.7 interpreter, with predictable memory management and without global locks.
- [protobuf](https://github.com/google/protobuf) : Protocol Buffers - Google's data interchange format
- [breadboard](https://github.com/google/breadboard) : C++ graph based event system


## GameProgramming
- EntityComponentSystem
  - [corgi](https://github.com/google/corgi) : C++ entity-component system
  - [ECS](https://github.com/redxdev/ECS) : C++ single-header entity component system
  - [EntityPlus](https://github.com/Yelnats321/EntityPlus) : A C++14 Entity Component System
  - [ecst](https://github.com/SuperV1234/ecst) : Experimental C++14 multithreaded compile-time entity-component-system library
  - [entityx](https://github.com/alecthomas/entityx) : EntityX - A fast, type-safe C++ Entity-Component system
- Inputs
  - [gainput](https://github.com/jkuhlmann/gainput) : Awesome C++ input library for games
  - [libgamepad](https://github.com/mtwilliams/libgamepad) : Cross-platform library for gamepad input. MIT licensed.
- Maps
  - [voxels](https://github.com/stoyannk/voxels) : Voxels Library - C++ library for voxel manipulation and polygonization
  - [tmxlite](https://github.com/fallahn/tmxlite) : lightweight C++14 parser for Tiled tmx files
- [Achieve](https://github.com/Dovyski/Achieve) : Library to manage and implement achievements in a game.
- [GA-SDK-UNREAL](https://github.com/GameAnalytics/GA-SDK-UNREAL) : A repository containing the GameAnalytics Unreal4 Plugin including documentation.


## Tools
- [NormalMap-Online](https://github.com/cpetry/NormalMap-Online) : NormalMap Generator Online
- [TextureGenerator-Online](https://github.com/cpetry/TextureGenerator-Online) : Procedural texture creator Online
- [unosolo](https://github.com/SuperV1234/unosolo) : Work-in-progress Rust application that converts C++ libraries to single self-contained headers.
- [incbin](https://github.com/rmitton/incbin) : Tiny cross-platform utility for including binaries into C source.


## GameDesign
- [gamebook](https://github.com/r-lyeh/gamebook) : An unified game design document convention (CC0, Markdown)


## Awesome
- [awesome-cpp](https://github.com/fffaraz/awesome-cpp) : A curated list of awesome C/C++ frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff
- [awesome-c](https://github.com/uhub/awesome-c) : A curated list of awesome C frameworks, libraries and software.
- [awesome](https://github.com/sindresorhus/awesome) : Curated list of awesome lists
- [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) : Awesome Vulkan ecosystem
- [awesome-bits](https://github.com/keon/awesome-bits) : A curated list of awesome bitwise operations and tricks
- [awesome-gamedev](https://github.com/Calinou/awesome-gamedev) : A collection of free software and free culture resources for making amazing games
- [awesome-gametalks](https://github.com/ellisonleao/awesome-gametalks) : A curated list of gaming talks (development, design, etc)
- [awesome-design](https://github.com/Calinou/awesome-design) : Best UI/UX Design Sources For Developer & Designer Ever :)
- [magictools](https://github.com/ellisonleao/magictools) : A list of Game Development resources to make magic happen.
- [cpplinks](https://github.com/MattPD/cpplinks) : A categorized list of C++ resources.

## GameProgrammerPath
- [game-programmer](https://github.com/miloyip/game-programmer) : A Study Path for Game Programmer
- [coding-interview-university](https://github.com/jwasham/coding-interview-university) : A complete computer science study plan to become a software engineer.
- [interview](https://github.com/andreis/interview) : Everything you need to prepare for your technical interview

## Tutorials
- [travis_cpp_tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial) : Tutorial how to use Travis CI with C++
- [GamePhysicsCookbook](https://github.com/gszauer/GamePhysicsCookbook) : Source code for GamePhysicsCookbook
- [craftinginterpreters](https://github.com/munificent/craftinginterpreters) : Repository for the book "Crafting Interpreters"
- [game-programming-patterns](https://github.com/munificent/game-programming-patterns) : Source repo for the book
- [r4cppp](https://github.com/nrc/r4cppp) : Rust for C++ programmers
- [color-theory](http://tallys.github.io/color-theory/) : Tutorial on the color theory
- [LearnOpenGL](https://github.com/JoeyDeVries/LearnOpenGL) : http://learnopengl.com
- [ogl](https://github.com/opengl-tutorials/ogl) : http://www.opengl-tutorial.org/
- [EpicSurvivalGameSeries](https://github.com/tomlooman/EpicSurvivalGameSeries) : Third person survival game tutorial for Unreal Engine 4.
- [UE4-Cpp-Tutorials](https://github.com/orfeasel/UE4-Cpp-Tutorials) : Tutorials of Game Systems inside UE4
- [android-ndk](https://github.com/googlesamples/android-ndk) : Android NDK samples with Android Studio