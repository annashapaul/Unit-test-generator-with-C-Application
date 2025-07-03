# Unit-test-generator-with-C-Application

Project Structure (After Setup)
cpp-test-generator/
├── src/                 # Input C++ project
├── tests/               # Generated unit tests
├── build/               # Build artifacts
├── instructions/
│   ├── gen_tests.yaml
│   ├── refine_tests.yaml
│   └── fix_build.yaml
├── scripts/
│   ├── generate_tests.py
│   ├── refine_tests.py
│   ├── build_and_debug.py
│   └── coverage_analysis.py
├── report.md
└── README.md




Step 1: Environment Setup
Dependencies:
. C++ compiler (g++ or clang++)
. cmake, make
. Google Test: via apt or vcpkg
. LLM API or local LLaMA
. Python 3 with requests, pyyaml, and subprocess

...Install Google Test...
sudo apt install libgtest-dev cmake
cd /usr/src/gtest
sudo cmake CMakeLists.txt
sudo make
sudo cp *.a /usr/lib
