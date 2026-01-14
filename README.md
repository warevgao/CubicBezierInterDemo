# CubicBezierInterDemo
A demonstration program for finding intersection points between two **3D Cubic Bézier curves**.

This project implements an algorithm to calculate intersections of spatial curves, supporting manual input, file loading, and built-in performance benchmarks.

## 📋 Features

* **3D Support**: Fully supports intersection calculations in 3D space, including non-coplanar curves.
* **Multiple Input Modes**:
    1.  **Manual Input**: Input control points via the console.
    2.  **File Input**: Batch load curve data from a TXT file.
    3.  **Benchmarks**: Run pre-defined complex geometric cases (tangential, interlocking, skew, etc.).
* **Performance Metrics**: Provides execution time statistics (average duration) in benchmark mode.
* **Precision**: Outputs precise 3D intersection coordinates `(x, y, z)` and corresponding parameters `(u, v)`.

## 🚀 Quick Start

### Prerequisites
* A C++ compiler supporting **C++11** or higher (e.g., `g++`, `clang++`, `MSVC`).
* Standard C++ Library (no external dependencies required).
