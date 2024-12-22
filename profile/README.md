# ClangBuiltArduino

ClangBuiltArduino is an initiative aimed at adding and enhancing LLVM/Clang support for Arduino programs and related software. By addressing compatibility issues and improving compiler support, we strive to make it easier to build Arduino projects using modern LLVM toolchains.

> [!NOTE]  
> ClangBuiltArduino GitHub organization is an independent initiative. We are not affiliated with or endorsed by Arduino or the LLVM Project.

## About the Project
The Arduino ecosystem has long relied on GCC as its default toolchain. While GCC is widely adopted, clang offers several benefits, including:
- Unified Toolchain: With clang, you can use a single toolchain for multiple architectures, avoiding the need for maintaining multiple prefixed toolchains for each target.
- Advanced Diagnostics: Clang provides detailed code diagnostics in terms of error messages and warnings, making it easier to debug and optimize code.
- Modular Architecture: LLVM's highly modular design allows for creating slim toolchains by shipping only the necessary components.

Our goal is to:
1. Identify and fix issues that prevent Arduino programs from building with clang and other LLVM tools.
3. Contribute patches upstream to relevant repositories.
4. Provide custom board packages to integrate LLVM/Clang support into Arduino IDE.
5. Serve as a centralized issue tracker for LLVM compatibility with Arduino software.
