# STM32Cube VS Code Video Tutorial Projects

![STM32](https://img.shields.io/badge/STM32-MCU-blue)
![VS Code](https://img.shields.io/badge/VS_Code-Workflow-007ACC)
![CMake](https://img.shields.io/badge/CMake-Build_System-green)
![TrustZone](https://img.shields.io/badge/Security-TrustZone-orange)
![STM32H755](https://img.shields.io/badge/Multi--Core-STM32H755-red)

Reference projects accompanying STM32 video tutorials focused on modern embedded development workflows using:

- **STM32CubeMX**
- **STM32CubeIDE for Visual Studio Code**
- **Visual Studio Code**
- **CMake**
- **STM32CubeProgrammer**
- **ST-LINK**

These projects are intended for learning, demonstrations, workshops, and hands-on training sessions covering STM32 development from project creation through debugging and deployment.

> [!IMPORTANT]
> **STM32CubeIDE for Visual Studio Code** is required to use these projects.

---

## Repository Overview

The STM32Cube ecosystem simplifies embedded software development by providing integrated tools for configuration, code generation, compilation, debugging, and device programming.

This repository contains practical examples demonstrating:

✅ STM32CubeMX project creation  
✅ CMake-based build systems  
✅ VS Code integration  
✅ Secure development with TrustZone®  
✅ Dual-core application development  
✅ Modern STM32 development workflows

---

## Included Projects

| Project | Device | Focus Area |
|----------|----------|------------|
| **VSCODE_MOOC_STM32L4** | STM32L476xx | Basic VS Code & CMake workflow |
| **H563_vscode_tz** | STM32H563xx | TrustZone® Security |
| **MOOC_H755_dualcore** | STM32H755xx | Dual-Core Development |

---

## VSCODE_MOOC_STM32L4

### Description

General-purpose STM32 reference application demonstrating:

- STM32CubeMX code generation
- CMake project configuration
- Visual Studio Code integration
- Debug workflows
- Project organization best practices

### Target Device

**STM32L476xx**

### Learning Objectives

- Create STM32 projects using STM32CubeMX
- Configure CMake build environments
- Build and debug applications from VS Code
- Understand STM32 project structure

---

## H563_vscode_tz

### Description

Demonstrates secure firmware development using **Arm TrustZone®** on STM32H5 devices.

The project illustrates how to partition software into **Secure** and **Non-Secure** domains while maintaining a streamlined VS Code development workflow.

### Target Device

**STM32H563xx**

### Learning Objectives

- Configure TrustZone in STM32CubeMX
- Create Secure and Non-Secure projects
- Implement Secure Callable interfaces
- Understand secure firmware architectures

---

## MOOC_H755_dualcore

### Description

Reference project demonstrating STM32H7 dual-core application development.

This example shows how applications can be distributed across both Cortex-M7 and Cortex-M4 cores while sharing system resources and exchanging data.

### Target Device

**STM32H755xx**

### Learning Objectives

- Dual-core project organization
- Core-to-core communication concepts
- Shared peripheral management
- Multi-core debugging workflows

---

## Software Requirements

### Required Tools

- Visual Studio Code
- STM32CubeIDE for Visual Studio Code
- STM32CubeMX
- GNU Arm Embedded Toolchain
- CMake
- Ninja

### Recommended Tools

- STM32CubeProgrammer
- ST-LINK drivers and utilities
- Cortex-Debug VS Code extension

---

## Repository Structure

```text
.
├── VSCODE_MOOC_STM32L4/
├── H563_vscode_tz/
└── MOOC_H755_dualcore/
