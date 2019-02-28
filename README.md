# clang-format-style
![Language](https://img.shields.io/badge/Language-C%2B%2B-brightgreen.svg)
[![Version](https://img.shields.io/badge/clang--format%20version-6.0-orange.svg)](https://releases.llvm.org/6.0.0/tools/clang/docs/ClangFormatStyleOptions.html)

## Using clang-formater on Ubuntu
 - First install clang-format-6.0 :
            
       sudo aptitude install clang-format-6.0

- Then copy the syle file of this repository into your project folder. Rename it as ".clang-format".
 - You just need to type the following command in the project's directory where the config file is stored:
 
       find . -name '*.h' -or -name '*.hpp' -or -name '*.cpp' | xargs clang-format-6.0 -i -style=file $1
 
## Summary
My personal config file for Clang-format!

 - [License](LICENSE)
