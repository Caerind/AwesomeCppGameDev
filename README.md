# Awesome list of C++ GameDev project

If you want to add projects here, do a push request or an issue.

C++, C, C#, Lua, and some exceptions for other languages. 

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
  - [ConcurrentQueue](https://github.com/cameron314/concurrentqueue) : A fast multi-producer, multi-consumer lock-free concurrent queue for C++11
  - [cpp-concurrency](https://github.com/revsic/cpp-concurrency) : cpp implementation of golang style concurrency 
  - [coroutine](https://github.com/tonbit/coroutine) : C++11 single .h asymmetric coroutine implementation via ucontext / fiber 
  - [MAN](https://github.com/qnope/MAN) : Man is Thread Pool in C++17 
- Memory
  - [jemalloc](https://github.com/jemalloc/jemalloc) : jemalloc is a general purpose malloc(3) implementation that emphasizes fragmentation avoidance and scalable concurrency support.
  - [rpmalloc](https://github.com/rampantpixels/rpmalloc) : Public domain cross platform lock free thread caching 16-byte aligned memory allocator implemented in C
  - [flatbuffers](https://github.com/google/flatbuffers) : Memory Efficient Serialization Library
  - [mio](https://github.com/mandreyel/mio) : Cross-platform C++11 header-only library for memory mapped file IO 
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
  - [simple-ini-reader](https://github.com/seb-jones/simple-ini-reader) : Fast, Simple, Public Domain INI Reader written in C 
  - [rapidjson](https://github.com/Tencent/rapidjson) : A fast JSON parser/generator for C++ with both SAX/DOM style API 
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
  - [tinyrelf](https://github.com/Manu343726/tinyrefl) : A work in progress minimal C++ static reflection API and codegen tool. 
- Metaprogramming
  - [STT-C-Compile-Time-Snake](https://github.com/mattbierner/STT-C-Compile-Time-Snake) : Snake/Nibbler implementation using C++ template metaprogamming
  - [brigand](https://github.com/edouarda/brigand) : Instant compile time C++ 11 metaprogramming library
  - [cxl](https://github.com/tacticalmelonfarmer/cxl) : A metaprogramming library for C++17. Strings, Parsing, Typelists... 
  - [meta](https://github.com/skypjack/meta) : Header-only, non-intrusive and macro-free runtime reflection system in C++ 
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
  - [prio_queue](https://github.com/rollbear/prio_queue) : C++14 cache friendly B-heap priority queue 
  - [dep_sort](https://github.com/graphitemaster/dep_sort) : Generic topological sorting for sorting a list of dependencies in C++17 
  - [sort](https://github.com/swenson/sort) : Sorting routine implementations in "template" C 
  - [Unity-Reorderable-List](https://github.com/cfoulston/Unity-Reorderable-List) : Extended version of the Reorderable List in Unity 
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
  - [lonesha256-ansi](https://github.com/ryancdotorg/lonesha256-ansi) : Portable, endian-proof, single-file, single-function sha256 implementation in ANSI C 
  - [meow_hash](https://github.com/cmuratori/meow_hash) : Official version of the Meow hash, an extremely fast non-cryptographic hash 
- Testing
  - [Catch](https://github.com/philsquared/Catch) : A modern, C++-native, header-only, test framework for unit-tests, TDD and BDD - using C++98, C++03, C++11, C++14 and later
  - [doctest](https://github.com/onqtam/doctest) : The fastest feature-rich C++11/14/17/20 single-header testing framework for unit tests and TDD
  - [benchmark](https://github.com/google/benchmark) : A microbenchmark support library
  - [mettle](https://github.com/jimporter/mettle) : A C++14 unit test framework
  - [portable-file-dialogs](https://github.com/samhocevar/portable-file-dialogs) : Portable dialogs library 
- SystemAPI
  - [sfd](https://github.com/rxi/sfd) : A small C library for opening a file dialog
  - [Boxer](https://github.com/aaronmjacobs/Boxer) : Boxer is a simple library that allows for easy cross-platform creation of message boxes / alerts / what have you.
- C++ Extensions
  - [any](https://github.com/PaulHowes/any) : A simple variant type for C++
  - [0xABAD1DEA](https://github.com/graphitemaster/0xABAD1DEA) : Static global objects with constructors and destructors made useful in C++
  - [modern-cpp-features](https://github.com/AnthonyCalandra/modern-cpp-features) : A cheatsheet of modern C++ language and library features.
  - [better-enums](https://github.com/aantron/better-enums) : Compile-time enum to string, iteration, in a single header file
  - [smartenum](https://github.com/therocode/smartenum) : Macros for declaring enums in C++ that include to_string conversion and looping through all enum values
  - [ArticleEnumClass-v2](https://github.com/Dalzhim/ArticleEnumClass-v2) : Bitmask operators and typesafe comparisons for enum class
  - [immutable-cpp](https://github.com/rsms/immutable-cpp) : Persistent immutable data structures for C++
  - [liberasure](https://github.com/atomgalaxy/liberasure) : A no-dependencies C++ extensible type erasure library
  - [atria](https://github.com/Ableton/atria) : A toolkit for modern C++ development
  - [cpp-defer](https://github.com/xdbr/cpp-defer) : defer action to end of scope (C++11 only / header-only)
  - [FastDynamicCast](https://github.com/tobspr/FastDynamicCast) : Fast dynamic cast in C++ for MSVC, outperforming the regular dynamic cast by up to 25 times
  - [invoke.hpp](https://github.com/BlackMATov/invoke.hpp) : std::invoke/std::apply analogs for C++14
  - [cppbackport](https://github.com/PollardBanknote/cppbackport) : A backport of C++11/14/17 features to earlier versions 
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
- [cpp-ipc](https://github.com/mutouyun/cpp-ipc) : C++ IPC Library: A high-performance inter-process communication using shared memory on Linux/Windows. 
- [cftf](https://github.com/neobrain/cftf) : Clang from the Future: A C++17 to C++11 source-to-source compiler 
- [lex](https://github.com/foonathan/lex) : C++14 fast and efficient tokenizer 
- [NativeJIT](https://github.com/BitFunnel/NativeJIT) : A C++ expression -> x64 JIT 


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
- [boden](https://github.com/AshampooSystems/boden) : Truly native C++ cross-platform framework for Android and iOS development 
- [mozjpeg](https://github.com/mozilla/mozjpeg) : Improved JPEG encoder. 
- [OpenHMD](https://github.com/OpenHMD/OpenHMD) : Free and Open Source API and drivers for immersive technology. 
- [dr_libs](https://github.com/mackron/dr_libs) : A collection of public domain single-file libraries for C/C++. 
- [acd](https://github.com/acdemiralp/acd) : Single file utilities for C++. 
- [gif_load](https://github.com/hidefromkgb/gif_load) : A slim, fast and header-only GIF loader written in C 
- [paq](https://github.com/pennie-quinn/paq) : public domain single-file C/++ libraries for game devs 
- [FFMpeg-decode-example](https://github.com/UnickSoft/FFMpeg-decode-example) : Example how to use ffmpeg to decode video file. 
- [single-file-libs](https://github.com/machinamentum/single-file-libs) : super permissive, drop-in, single file stuff  

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
- [WickedEngine](https://github.com/turanszkij/WickedEngine) : C++ game engine focusing on modern rendering techniques. 
- [MAGE](https://github.com/matt77hias/MAGE) : MAGE - Matthias Advanced Game Engine
- [shiva](https://github.com/Milerius/shiva) : Modern Cross-Platform C++ Engine with modularity (MIT) 
- [include-engine](https://github.com/sgorsten/include-engine) : #include engine 
- [GameEngine](https://github.com/qnope/GameEngine) : Little Game Engine that aims to be Physically Based for the lighting part 
- [Limon](https://github.com/enginmanap/limonengine) : 3D game engine with builtin editor, focusing ease of use and ease of study.
- SFML based engines
  - [Swift2](https://github.com/dabbertorres/Swift2) : A SFML-backed game framework.
  - [SchiffbruchEngine](https://github.com/Lirrec/SchiffbruchEngine) : SchiffbruchEngine
  - [SFBL](https://github.com/Made4Dev/SFBL) : SFML Box2D Light
  - [ObEngine](https://github.com/Sygmei/ObEngine) : 2D Game Engine with Lua Scripting made on top of SFML !
  - [nero-game-engine](https://github.com/sk-landry/nero-game-engine) : Advanced SFML Game Engine, Designed to be Simple and Intuitive 
  - [Vigilante-Game-Framework](https://github.com/gamepopper/Vigilante-Game-Framework) : 2D/3D C++ game framework written for use with SFML.

## Maths
- [vectorial](https://github.com/scoopr/vectorial) : Vector math library with NEON/SSE support
- [mathfu](https://github.com/google/mathfu) : C++ math library developed primarily for games focused on simplicity and efficiency.
- [xsimd](https://github.com/QuantStack/xsimd) : C++ wrappers for SIMD intrinsics
- [hlml](https://github.com/fmutant/hlml) : vectorized high-level math library
- [cmath3d](https://github.com/jpreiss/cmath3d) : 3d math library for C. Vectors, 3x3 matrices, quaternions.
- [eigen](https://github.com/RLovelett/eigen) : Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
- [xo-math](https://github.com/xoorath/xo-math) : xo-math is an open source single header file module for optimized game math. C++11 or newer required.
- [linalg](https://github.com/sgorsten/linalg) : linalg.h is a single header public domain linear algebra library for C++11 
- [pcg-c](https://github.com/imneme/pcg-c) : PCG Random Number Generation, C Edition
- [painless_gmm](https://github.com/alvarocollet/painless_gmm) : A real-world implementation of a Gaussian Mixture Model in C++, without the pain. 
- [vml](https://github.com/valentingalea/vml) : C++17 GLSL-like vector and matrix math lib 
- [glm](https://github.com/g-truc/glm) : OpenGL Mathematics (GLM) 
- Noise
  - [FastNoiseSIMD](https://github.com/Auburns/FastNoiseSIMD) : C++ SIMD Noise Library
  - [FastNoise](https://github.com/Auburns/FastNoise) : Fast C++ Noise Library
  - [SimplexNoise](https://github.com/simongeilfus/SimplexNoise) : Collection of Simplex Noise functions
  - [SimplexNoise](https://github.com/PawelWorwa/SimplexNoise) : Cpp port for Simplex Noise library
  - [LowDiscBlueNoise](https://github.com/dcoeurjo/LowDiscBlueNoise) : 
Low-Discrepancy Blue Noise Sampling
  - [TileableVolumeNoise](https://github.com/sebh/TileableVolumeNoise) : Collection of functions that can be used to generate tileable volume/3d noise. An exemple of volume noise functions that can be specifically used for clouds is also presented. 

## Graphics
- SFML
  - [SFML](https://github.com/SFML/SFML) : Simple and Fast Multimedia Library
  - [SFML-GameDev](https://github.com/SFML/SFML-Game-Development-Book) : Full and up-to-date source code of the chapters of the "SFML Game Development" book
  - [Thor](https://github.com/Bromeon/Thor) : SFML Extension with various game programming features, like particles, animations, vector operations
  - [SFML-Book](https://github.com/Krozark/SFML-book) : SFML Blueprint book, source code
  - [LTBL2](https://github.com/222464/LTBL2) : A 2D dynamic lighting system with accurate soft shadows.
  - [light_ungod](https://github.com/Ung0d/light_ungod) : A reimplementation of the LTBL2-framework.
  - [RichText](https://github.com/skyrpex/RichText) : Rich text class for SFML2
  - [QSFML](https://github.com/KoczurekK/QSFML) : Library that integrates SFML 2.x.x and Qt 5.x.x, includes event handling etc.
  - [SFGUI](https://github.com/TankOs/SFGUI) : Simple and Fast Graphical User Interface
  - [imgui-sfml](https://github.com/eliasdaler/imgui-sfml) : ImGui binding for use with SFML
  - [TGUI](https://github.com/texus/TGUI) : An easy to use cross-platform c++ GUI for SFML
  - [SimplGUI](https://github.com/victorlevasseur/SimplGUI) : SimplGUI is simple GUI library for SFML. It provides simple widgets that can be used independently.
  - [Motion](https://github.com/zsbzsb/Motion) : Complete video and audio player for SFML
  - [sfeMovie](https://github.com/Yalir/sfeMovie) : sfeMovie is a simple C++ library that lets you play movies in SFML based applications.
  - [Swoosh](https://github.com/TheMaverickProgrammer/Swoosh) : SFML Activity and Segue Mini Library 
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
  - [GPU-cloth](https://github.com/likangning93/GPU_cloth) : 
GPU cloth with OpenGL Compute Shaders
  - [gl_vk_meshlet_cadscene](https://github.com/nvpro-samples/gl_vk_meshlet_cadscene) : This OpenGL/Vulkan sample illustrates the use of "mesh shaders" for rendering CAD models. 
  - [surface_splatting](https://github.com/sebastianlipponer/surface_splatting) : OpenGL demo of a point rendering and texture filtering technique called Surface Splatting. 
- Vulkan
  - [Vookoo](https://github.com/andy-thomason/Vookoo) : A set of utilities for taking the pain out of Vulkan in header only modern C++
  - [vulkan_minimal_compute](https://github.com/Erkaman/vulkan_minimal_compute) : Minimal Example of Using Vulkan for Compute Operations.
  - [VulkanSponza](https://github.com/SaschaWillems/VulkanSponza) : Deferred Vulkan rendering playground using Crytek's Sponza scene
  - [Vulkan](https://github.com/SaschaWillems/Vulkan) : Examples and demos for the new Vulkan API
  - [Vulkan-Hpp](https://github.com/KhronosGroup/Vulkan-Hpp) : Open-Source Vulkan C++ API
  - [Vulkan-Example](https://github.com/qnope/Vulkan-Example) : Some example of Vulkan with C++ 
  - [VulkanTutorial](https://github.com/Overv/VulkanTutorial) : Tutorial for the Vulkan graphics and compute API
  - [laugh_engine](https://github.com/jian-ru/laugh_engine) : A Vulkan implementation of real-time PBR renderer
  - [VulkanResources](https://github.com/jcoder58/VulkanResources) : A list of resources for learning Vulkan
  - [Vulkan-Docs](https://github.com/KhronosGroup/Vulkan-Docs) : The Vulkan API Specification and related tools
  - [VulkanRTX](https://github.com/DsoTsin/VulkanRTX) : VulkanRTX
  - [vkbind](https://github.com/dr-soft/vkbind) : Single file Vulkan API loader.
  - [vulkan-base](https://github.com/kennyalive/vulkan-base) : Simple Vulkan application  
  - [VkBindingBenchmark](https://github.com/khalladay/VkBindingBenchmark) : Sponza And Bistro tests to benchmark transform data handling in Vulkan 
  - [vulkano](https://github.com/vulkano-rs/vulkano) : Safe and rich Rust wrapper around the Vulkan API 
  - [SPIRV-Cross](https://github.com/KhronosGroup/SPIRV-Cross) : SPIRV-Cross is a practical tool and library for performing reflection on SPIR-V and disassembling SPIR-V back to high level languages. 
  - [shaderc](https://github.com/google/shaderc) : A collection of tools, libraries, and tests for Vulkan shader compilation. 
  - [niagara](https://github.com/zeux/niagara) : A Vulkan renderer written from scratch on stream 
  - [vuda](https://github.com/jgbit/vuda) : VUDA is a header-only library based on Vulkan that provides a CUDA Runtime API interface for writing GPU-accelerated applications. 
- DirectX
  - [NebulaRender](https://github.com/Trylz/NebulaRender) : A powerful physically based renderer with a fully featured editor. 
  - [D3d12info](https://github.com/sawickiap/D3d12info) : Simple console tool to get all the information from DXGI and Direct3D 12 on current system 
  - [rostkatze](https://github.com/msiglreith/rostkatze) : C++ implementation of Vulkan sitting on D3D12
  - [DirectXShaderCompiler](https://github.com/Microsoft/DirectXShaderCompiler) : This repo hosts the source for the DirectX Shader Compiler which is based on LLVM/Clang. 
  - [DeferredTexturing](https://github.com/TheRealMJP/DeferredTexturing) : A rendering sample that demonstrates bindless deferred texturing using D3D12 
- GUI
  - [imgui](https://github.com/ocornut/imgui) : Bloat-free Immediate Mode Graphical User interface for C++ with minimal dependencies
  - [nuklear](https://github.com/vurtun/nuklear) : A single-header ANSI C gui library
  - [polyscope](https://github.com/nmwsharp/polyscope) : A prototyping-oriented UI for geometric algorithms
  - [Ultralight](https://github.com/ultralight-ux/ultralight) : Ultralight— a lightweight, pure-GPU, HTML UI renderer for your C++ app. 
  - [yue](https://github.com/yue/yue) : A library for creating native cross-platform GUI apps 
  - [qt3d](https://github.com/qt/qt3d) : Qt3D
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
- [Separable-sss](https://github.com/iryoku/separable-sss) : Separable Subsurface Scattering is a technique that allows to efficiently perform subsurface scattering calculations in screen space in just two passes.
- [pbrtest](https://github.com/sgorsten/pbrtest) : A small testbed for physically based rendering experiments  
- [pbrt-parser](https://github.com/ingowald/pbrt-parser) : A simple parser for the PBRT file format 
- [CIEDE2000](https://github.com/gfiumara/CIEDE2000) : C++ implementation of the CIE Delta E 2000 Color-Difference algorithm (CIEDE2000). 
- [MaskedOcclusionCulling](https://github.com/GameTechDev/MaskedOcclusionCulling) : Example code for the research paper "Masked Software Occlusion Culling"; implements an efficient alternative to the hierarchical depth buffer algorithm.
- [quickhull](https://github.com/akuukka/quickhull) : C++ implementation of the 3D QuickHull algorithm 
- [gDel3D](https://github.com/ashwin/gDel3D) : gDel3D is the fastest 3D Delaunay triangulation algorithm. It uses the GPU for massive parallelism. 
- [UnitySpriteShaders](https://github.com/traggett/UnitySpriteShaders) : An Uber Shader for rendering Sprites in Unity. 
- [aten](https://github.com/nackdai/aten) : Easy, simple path trace renderer. 
- [tinyrenderer](https://github.com/ssloy/tinyrenderer) : A brief computer graphics / rendering course
- [halfedge](https://github.com/yig/halfedge) : A C++ half-edge data structure for a triangle mesh with no external dependencies whatsoever. Public domain. 
- [GettingStartedWithRTXRayTracing](https://github.com/NVIDIAGameWorks/GettingStartedWithRTXRayTracing) : Getting Started with RTX Ray Tracing 
- [Fox2](https://github.com/FRex/Fox2) : FoxRaycaster, optimized, fixed and with a CUDA option 
- [Diligent Engine](https://github.com/DiligentGraphics/DiligentEngine) : A modern cross-platform low-level graphics library and rendering framework


## Audio
- [steam-audio](https://github.com/ValveSoftware/steam-audio) : Steam Audio
- [soloud](https://github.com/jarikomppa/soloud) : Free, easy, portable audio engine for games
- [kfr](https://github.com/kfrlib/kfr) : Fast, modern C++ DSP framework, FFT, Audio Sample Rate Conversion, FIR/IIR/Biquad Filters (SSE, AVX, ARM NEON)
- [ass](https://github.com/fungos/ass) : ASS: Audio Stupidly Simple 
- [FAudio](https://github.com/FNA-XNA/FAudio) : FAudio - Accuracy-focused XAudio reimplementation for open platforms 
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
  - [phyxed-2d](https://github.com/Srekel/phyxed-2d) : A 2d physics engine with fixed-point support. 
- 3D Physics
  - [NewtonDynamics](https://github.com/MADEAPPS/newton-dynamics) : Newton Dynamics is an integrated solution for real time simulation of physics environments.
  - [nudge](https://github.com/rasmusbarr/nudge) : A small data-oriented and SIMD-optimized 3D rigid body physics library.
  - [GridFluidSim3D](https://github.com/rlguy/GridFluidSim3D) : A PIC/FLIP fluid simulation based on the methods found in "Fluid Simulation for Computer Graphics"
  - [RealtimeWater](https://github.com/hpatjens/RealtimeWater) : The water simulation is based on the method that Fischer proposes for 2D heightfields
  - [PhysX-3.4](https://github.com/NVIDIAGameWorks/PhysX-3.4) : NVIDIA PhysX SDK 3.4 
  - [Bullet3](https://github.com/bulletphysics/bullet3) : Bullet Physics SDK: real-time collision detection and multi-physics simulation for VR, games, visual effects, robotics, machine learning etc. 
  - [Blender-FLIP-Fluids](https://github.com/rlguy/Blender-FLIP-Fluids) : FLIP Fluids is a powerful liquid simulation plugin that gives you the ability to create high quality fluid effects all within Blender, the free and open source 3D creation suite. 
  - [GPU-GEMS-3D-Fluid-Simulation](https://github.com/Scrawk/GPU-GEMS-3D-Fluid-Simulation) : 3D fluid simulation on the in Unity 
  - [physics_playground](https://github.com/avoroshilov/physics_playground) : Improved version of real-time physics engine that couples FEM-based deformables and rigid body dynamics 


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
  - [rinetd](https://github.com/samhocevar/rinetd) : TCP/UDP port redirector 
  - [swrap](https://github.com/BareRose/swrap) : Portable, single-file, protocol-agnostic TCP and UDP socket wrapper, primarily for game networking 
- SQL
  - [SQLiteCpp](https://github.com/SRombauts/SQLiteCpp) : SQLiteC++ (SQLiteCpp) is a smart and easy to use C++ SQLite3 wrapper.
  - [NLDatabase](https://github.com/catnapgames/NLDatabase) : Lightweight C++ wrapper for SQLite
  - [sqlpp11](https://github.com/rbock/sqlpp11) : A type safe SQL template library for C++
- RPC
  - [Game-Net](https://github.com/sp4cerat/Game-NET) : RPC Network Library for Multiplayer Games
  - [rpclib](https://github.com/rpclib/rpclib) : rpclib is a modern C++ msgpack-RPC server and client library
  - [libjson-rpc-cpp](https://github.com/cinemast/libjson-rpc-cpp) : C++ framework for json-rpc (json remote procedure call)
  - [cpp-ORM](https://github.com/Krozark/cpp-ORM) : A project to create a simple ORM
- [oatpp](https://github.com/oatpp/oatpp) : Light, zero-dependency framework. Create bleedingly-fast web-services. Organic. Pure C++ 
- [uvw](https://github.com/skypjack/uvw) : Header-only, event based, tiny and easy to use libuv wrapper in modern C++ 


## AI
- Neural Network & Deep Learning
  - [darknet](https://github.com/pjreddie/darknet) : Convolutional Neural Networks
  - [tiny-dnn](https://github.com/tiny-dnn/tiny-dnn) : header only, dependency-free deep learning framework in C++14
  - [TinNet](https://github.com/AcrylicShrimp/TinNet) : A C++14 based deep learning library. 
  - [CubbyDNN](https://github.com/utilForever/CubbyDNN) : Deep learning framework using C++17 in a single header file 
  - [CppDNN](https://github.com/kmc7468/CppDNN) : Machine Learning for C++11 
  - [neural](https://github.com/achpile/neural) : Some plays with neural network 
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
  - [Lua-Low-Level](https://github.com/gligneul/Lua-Low-Level) : Per function, Lua JIT using LLVM C++ toolchain 
- [duktape](https://github.com/svaarala/duktape) : Duktape - embeddable Javascript engine with a focus on portability and compact footprint
- [ChaiScript](https://github.com/ChaiScript/ChaiScript) : Embedded Scripting Language Designed for C++
- [zippypy](https://github.com/shooshx/zippypy) : A simple, lightweight Python 2.7 interpreter, with predictable memory management and without global locks.
- [protobuf](https://github.com/google/protobuf) : Protocol Buffers - Google's data interchange format
- [breadboard](https://github.com/google/breadboard) : C++ graph based event system
- [CppSharp](https://github.com/mono/CppSharp) : Tools and libraries to glue C/C++ APIs to high-level languages 
- [pybind11](https://github.com/pybind/pybind11) : Seamless operability between C++11 and Python


## GameProgramming
- EntityComponentSystem
  - [corgi](https://github.com/google/corgi) : C++ entity-component system
  - [ECS](https://github.com/redxdev/ECS) : C++ single-header entity component system
  - [EntityPlus](https://github.com/Yelnats321/EntityPlus) : A C++14 Entity Component System
  - [ecst](https://github.com/SuperV1234/ecst) : Experimental C++14 multithreaded compile-time entity-component-system library
  - [entityx](https://github.com/alecthomas/entityx) : EntityX - A fast, type-safe C++ Entity-Component system
  - [dynamix](https://github.com/iboB/dynamix) : DynaMix - DynaMix (Dynamic Mixins) is a new take on polymorphism. It lets the user compose and modify polymorphic objects at run time in C++.
- Inputs
  - [gainput](https://github.com/jkuhlmann/gainput) : Awesome C++ input library for games
  - [libgamepad](https://github.com/mtwilliams/libgamepad) : Cross-platform library for gamepad input. MIT licensed.
- Maps
  - [USD](https://github.com/PixarAnimationStudios/USD) : Pixar Universal Scene Description 
  - [voxels](https://github.com/stoyannk/voxels) : Voxels Library - C++ library for voxel manipulation and polygonization
  - [tmxlite](https://github.com/fallahn/tmxlite) : lightweight C++14 parser for Tiled tmx files
- [Achieve](https://github.com/Dovyski/Achieve) : Library to manage and implement achievements in a game.
- [GA-SDK-UNREAL](https://github.com/GameAnalytics/GA-SDK-UNREAL) : A repository containing the GameAnalytics Unreal4 Plugin including documentation.
- [](https://github.com/njh0602/match_maker) : A simple, header-only match maker(match making) implementation for C++. 


## Tools
- [NormalMap-Online](https://github.com/cpetry/NormalMap-Online) : NormalMap Generator Online
- [TextureGenerator-Online](https://github.com/cpetry/TextureGenerator-Online) : Procedural texture creator Online
- [unosolo](https://github.com/SuperV1234/unosolo) : Work-in-progress Rust application that converts C++ libraries to single self-contained headers.
- [incbin](https://github.com/rmitton/incbin) : Tiny cross-platform utility for including binaries into C source.
- [blink](https://github.com/crosire/blink) : A tool which allows you to edit source code of any C++ project live at runtime 
- [SIMD-Visualiser](https://github.com/piotte13/SIMD-Visualiser) : A tool to graphically visualize SIMD code 
- [MarkovNameGenerator](https://github.com/Tw1ddle/MarkovNameGenerator) : Markov process-based procedural name and word generator 
- [Procedural-Terrain-Estimator](https://github.com/Snowapril/Procedural-Terrain-Estimator) : Generate Height map with Generator (OpenGL and imgui) and Construct Splat Map with generated height map using Algorithm(DPS, BFS, Gradient Descent ... etc)
- [dxil-signing](https://github.com/gwihlidal/dxil-signing) : Utility to sign DXIL code after compilation 
- [ShaderConstructor](https://github.com/Microsoft/ShaderConductor) : ShaderConductor is a tool designed for cross-compiling HLSL to other shading languages 
- [nvtop](https://github.com/Syllo/nvtop) : NVIDIA GPUs htop like monitoring tool 


## GameDesign
- [gamebook](https://github.com/r-lyeh/gamebook) : An unified game design document convention (CC0, Markdown)


## Awesome
- [awesome-cpp](https://github.com/fffaraz/awesome-cpp) : A curated list of awesome C/C++ frameworks, libraries, resources, and shiny things. Inspired by awesome-... stuff
- [awesome-c](https://github.com/uhub/awesome-c) : A curated list of awesome C frameworks, libraries and software.
- [awesome](https://github.com/sindresorhus/awesome) : Curated list of awesome lists
- [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) : Awesome Vulkan ecosystem
- [awesome-bits](https://github.com/keon/awesome-bits) : A curated list of awesome bitwise operations and tricks
- [awesome-gamedev](https://github.com/Calinou/awesome-gamedev) : A collection of free software and free culture resources for making amazing games
- [awesome-game-networking](https://github.com/MFatihMAR/Awesome-Game-Networking) : A Curated List of Game Network Programming Resources 
- [awesome-behavior-trees](https://github.com/BehaviorTree/awesome-behavior-trees) : A list of awesome Behavior Trees resources 
- [awesome-gametalks](https://github.com/ellisonleao/awesome-gametalks) : A curated list of gaming talks (development, design, etc)
- [awesome-design](https://github.com/Calinou/awesome-design) : Best UI/UX Design Sources For Developer & Designer Ever :)
- [magictools](https://github.com/ellisonleao/magictools) : A list of Game Development resources to make magic happen.
- [cpplinks](https://github.com/MattPD/cpplinks) : A categorized list of C++ resources.
- [ModernCpp](https://github.com/utilForever/ModernCpp) : A curated list of Modern C++ articles, examples, tutorials, frameworks, libraries, and shiny things. 

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
