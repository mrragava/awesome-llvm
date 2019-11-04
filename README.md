# [Documentation](https://llvm.org/docs/index.html)
- [LLVM Language Reference Manual](https://llvm.org/docs/LangRef.html)
- [LLVM Programmer’s Manual](https://llvm.org/docs/ProgrammersManual.html)
- [LLVM Coding Standards](https://llvm.org/docs/CodingStandards.html)
- [LLVM Style RTTI](https://llvm.org/docs/HowToSetUpLLVMStyleRTTI.html)
- [Writing an LLVM Pass](https://llvm.org/docs/WritingAnLLVMPass.html)
- [LLVM Alias Analysis Infrastructure](https://llvm.org/docs/AliasAnalysis.html)
- [Source Level Debugging](https://llvm.org/docs/SourceLevelDebugging.html)
- [Create A Project](https://llvm.org/docs/Projects.html)
- [LLVM Developer Policy](https://llvm.org/docs/DeveloperPolicy.html)
- [CommandLine 2.0 Library Manual](https://llvm.org/docs/CommandLine.html)
- [Getting Started with the LLVM System](https://llvm.org/docs/GettingStarted.html)
- [LLVM Tutorials](https://llvm.org/docs/tutorial/index.html)
- [Python Version of the LLVM Tutorial](https://github.com/eliben/pykaleidoscope)
- [LLVM’s Analysis and Transform Passes](https://llvm.org/docs/Passes.html)
- [FAQ](https://llvm.org/docs/FAQ.html)
- [LLVM Testing Infrastructure Guide](https://llvm.org/docs/TestingGuide.html)
- [The Often Misunderstood GEP Instruction](https://llvm.org/docs/GetElementPtr.html)
- [Exception Handling in LLVM](https://llvm.org/docs/ExceptionHandling.html)
- [LLVM Bitcode File Format](https://llvm.org/docs/BitCodeFormat.html)
- [Writing an LLVM Backend](https://llvm.org/docs/WritingAnLLVMBackend.html)
- [Sanitizers](docs/sanitizers) - AddressSanitizer, MemorySanitizer, ThreadSanitizer, UndefinedBehaviorSanitizer, LeakSanitizer, etc


# Official Pages
- https://llvm.org/
- <a href="https://clang.llvm.org/">Clang</a>
- https://blog.llvm.org/
- https://llvm.org/devmtg/
- Mailing List
  - [llvm-dev](https://lists.cs.uiuc.edu/mailman/listinfo/llvmdev)([nabble forum page](https://llvm.1065342.n5.nabble.com/LLVM-Dev-f3.html)), [llvm-weekly](https://llvmweekly.org/)
  - [cfe-dev](https://lists.cs.uiuc.edu/mailman/listinfo/cfe-dev)

# Other Pages
- [The Architecture of Open Source Applications - LLVM](https://www.aosabook.org/en/llvm.html)
- [ELLCC](https://ellcc.org/demo/index.cgi) - Online LLVM Demo Page
- [Eli Bendersky's website](https://eli.thegreenplace.net/)
- [ChenWj's LLVM Wiki](https://people.cs.nctu.edu.tw/~chenwj/dokuwiki/doku.php?id=llvm)(Traditional Chinese)
- [An Unofficial LLVM Website](https://llvm.lyngvig.org/Articles/)
- [LLVM @ StackOverflow](https://stackoverflow.com/questions/tagged/llvm)
- [Clang @ StackOverflow](https://stackoverflow.com/questions/tagged/clang)
- Papers
  - https://llvm.org/pubs/
  - [LLVM @ Google Scholar](https://scholar.google.com.sg/scholar?hl=en&q=llvm&btnG=&as_sdt=1%2C5&as_sdtp=)
  - [LLVM @ Microsoft Academic Search](https://academic.research.microsoft.com/Search?query=llvm)
  - [LLVM @ ACM-DL](https://dl.acm.org/results.cfm?h=1&cfid=474738638&cftoken=86744949)
  - [LLVM @ IEEEXplore](https://ieeexplore.ieee.org/search/searchresult.jsp?newsearch=true&queryText=llvm)
  - [LLVM @ DBLP](https://dblp.org/search/#query=llvm&qp=H1.37:W1.3:F1.4:F2.4:F3.4:F4.3)

# Official Tools ([R1](https://llvm.org/docs/CommandGuide/index.html), [R2](https://llvm.org/ProjectsWithLLVM/))
- [opt](https://llvm.org/docs/CommandGuide/opt.html) - LLVM optimizer
- [lit](https://llvm.org/docs/CommandGuide/lit.html) - LLVM Integrated Tester
- [lli](https://llvm.org/docs/CommandGuide/lli.html) - Directly execute programs from LLVM bitcode
- [llvm-dis](https://llvm.org/docs/CommandGuide/llvm-dis.html) - LLVM disassembler
- [llvm-as](https://llvm.org/docs/CommandGuide/llvm-as.html) - LLVM assembler
- [llvm-link](https://llvm.org/docs/CommandGuide/llvm-link.html) - LLVM bitcode linker
- ~~[llvm-ld](https://llvm.org/releases/2.9/docs/CommandGuide/html/llvm-ld.html)(<=2.9) - LLVM linker~~
- [llvm-dwarfdump](https://llvm.org/docs/CommandGuide/llvm-dwarfdump.html) - Print contents of DWARF sections
- [llvm-config](https://llvm.org/docs/CommandGuide/llvm-config.html) - Print LLVM compilation options
- [llvm-extract](https://llvm.org/docs/CommandGuide/llvm-extract.html) - Extract functions from an LLVM module
- [llvm-bcanalyzer](https://llvm.org/docs/CommandGuide/llvm-bcanalyzer.html) - LLVM bitcode analyzer
- [llvm-objdump](https://llvm.org/docs/CommandGuide/llvm-objdump.html) - LLVM objdump
- [llvm-nm](https://llvm.org/docs/CommandGuide/llvm-nm.html) - LLVM nm
- [llvm-readobj](https://llvm.org/docs/CommandGuide/llvm-readobj.html) - LLVM object reader
- [llvm-diff](https://llvm.org/docs/CommandGuide/llvm-diff.html) - LLVM structural "diff"
- [llc](https://llvm.org/docs/CommandGuide/llc.html) -  LLVM static compiler
- [llvm-ar](https://llvm.org/docs/CommandGuide/llvm-ar.html)(llvm-ranlib) - LLVM archiver
- [clang](https://clang.llvm.org/) - Official C/C++/Objective C/Objective C++ front-end
- [clang-format](https://clang.llvm.org/docs/ClangFormat.html) - Format C/C++/Obj-C code with different styles
- [clang-check](https://clang.llvm.org/docs/ClangCheck.html) - Error checking and AST dumping based on [LibTooling](https://clang.llvm.org/docs/LibTooling.html)
- [scan-build](https://clang-analyzer.llvm.org/) - Clang Static Analyzer
- [scan-view](https://clang-analyzer.llvm.org/) - Clang Static Analysis Viewer
- ~~[clang-modernize](https://clang.llvm.org/extra/clang-modernize.html) - Modernize C++ code~~
- [clang-tidy](https://clang.llvm.org/extra/clang-tidy.html) - [Lint-like checks and beyondslides](https://llvm.org/devmtg/2014-04/PDFs/Talks/clang-tidy%20LLVM%20Euro%202014.pdf)
- ~~[DragonEgg](https://dragonegg.llvm.org/) - Using LLVM as a GCC backend~~
- [Polly](https://polly.llvm.org/) - LLVM Framework for High-Level Loop and Data-Locality Optimizations
- [LLDB](https://lldb.llvm.org/) - The LLDB Debugger
- [libfuzzer](https://llvm.org/docs/LibFuzzer.html) - a library for coverage-guided fuzz testing

# Unofficial Tools/Framework
- [American fuzzy lop (AFL)](https://lcamtuf.coredump.cx/afl/) - LLVM mode for instrumentation
- [SVF-tools](https://github.com/SVF-tools/SVF) - Pointer Analysis and Program Dependence Analysis for C and C++ Programs
- [Infer](https://github.com/facebook/infer) - Facebook's static analysis framework; C/C++/objc is based on LLVM/Clang
- [wllvm](https://github.com/travitch/whole-program-llvm) - A wrapper script to build whole-program LLVM bitcode files; its go port [gllvm](https://github.com/SRI-CSL/gllvm)
- [Bear](https://github.com/rizsotto/Bear) - A tool that generates a compilation database for clang tooling
- [klee](https://github.com/klee/klee) - Symbolic Virtual Machine
- [CppInsights](https://github.com/andreasfertig/cppinsights) ([site](https://cppinsights.io/)) - See your source code with the eyes of a compiler
- [S2E](https://github.com/s2e) - Selective Symbolic Execution (use KLEE as symbolic executor)
- [RetDec](https://github.com/avast-tl/retdec) - a retargetable machine-code decompiler based on LLVM
- [capstone](https://www.capstone-engine.org/beyond_llvm.html) - Disassembler based on the MC component of the LLVM compiler infrastructure
- [rtags](https://github.com/Andersbakken/rtags) - A c/c++ client/server indexer for c/c++/objc[++]
- ~~[slicer](https://github.com/wujingyue/slicer) - Schedule Specialization Framework~~
- ~~[LLBMC](https://llbmc.org/) - The Low-Level Bounded Model Checker~~
- [whole-program-llvm](https://github.com/travitch/whole-program-llvm) - A wrapper script to build whole-program LLVM bitcode files
- [DWGrep](https://pmachata.github.io/dwgrep/) - A tool for querying Dwarf (debuginfo) graphs
- [Emscripten](https://github.com/kripken/emscripten) - An LLVM-to-JavaScript Compiler
- [mcsema](https://github.com/trailofbits/mcsema) - An x86 to LLVM IR decompiler
- ~~[stack](https://github.com/xiw/stack) - A static checker for identifying unstable code~~
- ~~[andersen](https://github.com/grievejia/andersen) - Andersen's inclusion-based pointer analysis re-implementation in LLVM~~
- ~~[NeonGoby](https://github.com/wujingyue/neongoby) - Alias Analysis Checker~~

# Books
- [Getting Started with LLVM Core Libraries](https://www.amazon.com/Getting-Started-LLVM-Core-Libraries/dp/1782166920), also available on [ACM library](https://dl.acm.org/citation.cfm?id=2692607)
- [LLVM Cookbook](https://www.amazon.com/LLVM-Cookbook-Mayur-Pandey/dp/178528598X)
- [LLVM Essentials](https://www.amazon.com/LLVM-Essentials-Suyog-Sarda/dp/1785280805/)

# Tutorials
- [llvm-clang-samples](https://github.com/eliben/llvm-clang-samples) - Examples of LLVM and Clang written by Dr. [Eli Bendersky](https://eli.thegreenplace.net/)
- [srg-llvm-pass-tutorial](https://github.com/delcypher/srg-llvm-pass-tutorial) - A tutorial about llvm passes from [Software reliability group](https://srg.doc.ic.ac.uk/)
- [clang-llvm-tutorial](https://github.com/lijiansong/clang-llvm-tutorial) - clang & llvm examples
- [Get Started with the LLVM C API](https://pauladamsmith.com/blog/2015/01/how-to-get-started-with-llvm-c-api.html)

# Installation
- [LLVM Debian/Ubuntu nightly packages](https://apt.llvm.org/)
- [Mac OS Homebrew Formula](https://github.com/Homebrew/homebrew-core/blob/master/Formula/llvm.rb)

# LLVM backed Languages
- C/C++/ObjC/ObjC++
- [Swift](https://developer.apple.com/swift/)
- [GHC Haskell](https://www.haskell.org/ghc/)
- [Rust](https://www.rust-lang.org)
- [Julia](https://julialang.org/)
- [go-llvm](https://github.com/go-llvm/llgo)
- [scala-native](https://github.com/scala-native/scala-native)
- [ldc](https://github.com/ldc-developers/ldc)

# Bindings
- [llvmlite](https://github.com/numba/llvmlite) - A lightweight LLVM python binding for writing JIT compilers
- [LLVM Rust crates](https://crates.io/search?q=llvm)
