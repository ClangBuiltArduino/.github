# ClangBuiltArduino

ClangBuiltArduino is an independent initiative aimed at enhancing LLVM/Clang support for Arduino programs and related software. By addressing compatibility issues and improving cross-compiler support, we strive to make it easier to build Arduino projects using modern LLVM/Clang toolchains.

> Disclaimer:
> ClangBuiltArduino is an independent initiative. We are not affiliated with or endorsed by Arduino or the LLVM Project.

## About the Project
The Arduino ecosystem has long relied on GCC as its default toolchain. While GCC is robust and widely adopted, LLVM/Clang offers several benefits, including:
- Unified Toolchain: With LLVM/Clang, you can use a single toolchain for multiple architectures, avoiding the need for maintaining multiple prefixed toolchains for each target.
- Advanced Diagnostics: Clang provides detailed error messages and warnings, making it easier to debug and optimize code.
- Tooling Ecosystem: Leverage powerful tools like Clang-Tidy, Clang-Format, and LibTooling for static analysis, code formatting, and custom tooling.
Our goal is to:
1. Identify and fix issues that prevent Arduino programs from building with LLVM/Clang.
2. Contribute patches upstream to relevant repositories.
3. Serve as a centralized hub for discussing LLVM/Clang compatibility with Arduino software.
