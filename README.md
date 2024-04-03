# PinnedVector v1.3.1

PinnedVector is a versatile data structure designed to efficiently manage dynamic memory allocation in C++ projects. With a focus on optimizing performance and memory management, it offers the following features:

- **Constant Time Growth:** PinnedVector can dynamically expand its size with O(1) complexity without necessitating changes to its pointer or element copying, all while ensuring memory remains contiguous.
- **Efficient Memory Reservation:** It has the capability to reserve significant amounts of memory without immediate allocation, preserving resources until needed.

---
## Tested Platforms

PinnedVector has been rigorously tested on the following platform:

- 64-bit Linux (OpenSUSE)

---
## Credits

Special thanks to the [author](https://github.com/meemknight), whose insights and contributions have greatly enhanced PinnedVector. For further understanding, refer to the author's insightful YouTube video [here](https://youtu.be/p1EogAEktZ4).

---
## Usage

For CMake-based projects, utilize the provided CMakeLists.txt to link the PinnedVector library seamlessly. Otherwise, simply copy and include the header file. Please note that C++17 is required for compatibility.

---
## TODO

- [ ] Implement memory checking after vector deletion.
- [ ] Optimize size expansion algorithm for smarter growth.
- [ ] Implement functionality to shrink to fit.
- [ ] To Be Determined...

These tasks outline ongoing development goals for further refining PinnedVector's functionality and performance.

