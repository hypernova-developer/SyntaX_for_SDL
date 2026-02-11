# SyntaX for SDL3 🛡️

A modular graphical extension for the **SyntaX** ecosystem. This library wraps the complexity of SDL3 into a powerful, easy-to-use C++ interface while maintaining maximum performance.

## Features
* **Zero Boilerplate:** Initialize a window and renderer in a single line.
* **Allman Style:** Clean and consistent code architecture.
* **SyntaX Integrated:** Works seamlessly with the `bettersyntax` namespace.
* **Optimized:** Native C++ performance for graphical applications.

## Installation

### Prerequisites
* **SDL3:** Ensure you have the [SDL3 development libraries](https://github.com/libsdl-org/SDL/releases) installed on your system.
* **Compiler:** A C++17 compatible compiler (GCC, Clang, or MSVC).

### Setup
1. Clone this repository:
   ```bash
   git clone [https://github.com/hypernova-developer/SyntaX_for_SDL.git](https://github.com/hypernova-developer/SyntaX_for_SDL.git)
   ```
2. Include the header in your project:
   ```cpp
   #include "include/bettersdl.hpp"
   ```
3. Link the SDL3 library in your build system.

## Quick Start

```cpp
#include "bettersdl.hpp"

int main(int argc, char* argv[])
{
    // Create the engine instance
    bettersyntax::sdl::Engine app("SyntaX Power", 1280, 720);

    while (app.isRunning())
    {
        app.update(); // Handle events
        app.clear();  // Clear with SyntaX Purple
        app.render(); // Present frame
    }

    return 0;
}
```

## License
Part of the SyntaX Project. Maintained by @hypernova-developer.
