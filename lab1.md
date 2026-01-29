# MINISTRY OF EDUCATION AND SCIENCE OF UKRAINE  
## KYIV PROFESSIONAL COLLEGE OF COMMUNICATIONS  

---

# REPORT  
## on Laboratory Work №1  
### in the discipline "Operating Systems"

---

**Topic:**  
Introduction to virtual machine environments and features of the Linux operating system

---

**Completed by:**  
Student of group **BIKS-33**  
**Serbina Yaroslava Viacheslavivna**

---

**Instructor:**  
**Sushanova Viktoriia Serhiivna**

---

**Kyiv — 2025**

---


# Laboratory Work №1  
## Operating Systems

---

## Topic
Introduction to virtual machine environments and features of the Linux operating system

---

## Purpose
1. To study hypervisors of different types and virtualization when working with operating systems.  
2. To get familiar with the main types of modern operating systems and their basic capabilities.

---

## Pre-lab Preparation

### Glossary of Basic English Terms (Virtual Environments)

**Virtual Machine** — a software-based emulation of a physical computer that runs an operating system and applications.

**Virtualization** — a technology that allows multiple operating systems to run on a single physical machine.

**Hypervisor** — software or firmware that creates and manages virtual machines.

**Type 1 Hypervisor** — a hypervisor that runs directly on the physical hardware without a host operating system.

**Type 2 Hypervisor** — a hypervisor that runs on top of a host operating system.

**Host Operating System** — the main operating system installed on the physical machine.

**Guest Operating System** — an operating system installed and running inside a virtual machine.

**Kernel** — the core component of an operating system that manages hardware resources.

---

### Hypervisor Concept and Types

A hypervisor is software that is used to create and manage virtual machines. It allows multiple operating systems to run simultaneously on a single physical computer and distributes hardware resources between them.

According to the theoretical material, there are two main types of hypervisors.  
Type 1 hypervisors run directly on the hardware without a host operating system and are usually used on servers.  
Type 2 hypervisors are installed on top of an existing operating system and are more commonly used on personal computers.

---

### Hypervisor Components and Capabilities (Variant 16 — VirtualBox)

According to my variant, the VirtualBox hypervisor was considered. VirtualBox belongs to Type 2 hypervisors and operates on the basis of a host operating system. It allows users to create virtual machines with different guest operating systems.

The main components of VirtualBox include the host operating system, virtual machines, and virtual hardware resources such as the processor, RAM, and virtual hard disk.

The main capabilities of VirtualBox include creating and running multiple virtual machines, installing different operating systems, allocating hardware resources between them, and saving the state of a virtual machine.

---

## Answers to the Questions

### Stages of Deploying an Operating System Using VirtualBox

To deploy an operating system in the VirtualBox environment, it is first necessary to install the hypervisor on the computer. Then a new virtual machine is created and the operating system type and version are selected. After that, basic parameters such as RAM size and virtual hard disk space are configured. At the final stage, the installation image of the operating system is connected and the system is installed.

---

### Hardware Limitations for Installing 32-bit and 64-bit Operating Systems

When installing a 32-bit operating system, there is a limitation on the amount of RAM that can be used, which usually does not exceed 4 GB. To install a 64-bit operating system, a processor that supports 64-bit architecture and hardware virtualization is required. Without such support, installation or proper operation of a 64-bit OS is not possible.

---

### Main Stages of Installing Linux in Text Mode

When installing Linux in text mode, the user selects the interface language and configures the keyboard layout. Next, disk partitioning is performed and basic system packages are selected. After that, a user account is created, basic system settings are configured, and the operating system installation is completed.

---

### Installing GNOME and KDE After Text-Mode Installation

If Linux is already installed in text mode, graphical desktop environments can be installed using a package manager.

To install **GNOME**, the following command is used: `sudo apt install ubuntu-gnome-desktop`

To install **KDE**, the following command is used: `sudo apt install kde-standard`

---

### Graphical Interfaces Used in Linux Distributions (Variant 16)

**KDE** is a modern and functional graphical desktop environment that offers a user-friendly interface and extensive customization options. It is widely used in many Linux distributions as a full-featured working environment.

**Fluxbox** is a lightweight and minimalist graphical environment that consumes very few system resources. It is suitable for computers with limited hardware capabilities or for users who prefer simplicity.

---

## Control Questions

### 1. Comparison of Type 1 and Type 2 Hypervisors

Type 1 hypervisors operate directly on the computer hardware without using a host operating system. They provide better performance and reliability, therefore they are most often used on servers and in corporate environments.

Type 2 hypervisors are installed on top of an existing operating system and use its resources. This type of hypervisor is usually used on personal computers for learning, testing, or running multiple operating systems simultaneously.

---

### 2. GNU GPL Concept and Its Main Idea

GNU GPL is a free software license that guarantees users the right to use, modify, and distribute software. The main concept of this license is that any modifications of the program code must also remain open and available to other users.

---

### 3. The Essence of Open Source Software

Open source software provides free access to the source code. This allows users to study how a program works, modify it according to their needs, and improve it. This approach promotes transparency, security, and rapid software development.

---

### 4. Definition of a Distribution

A distribution is a ready-made set of software based on the Linux kernel, which includes the kernel, system utilities, libraries, and usually a graphical environment. Distributions simplify the process of installing and using the Linux operating system.

---

### 5. System Administration Tasks Using Linux

Using Linux, it is possible to perform server administration, user and access rights management, network configuration, data backup, system resource monitoring, and task automation using scripts.

---

### 6. Relationship Between Android and Linux

The Android operating system is based on the Linux kernel. Linux provides Android with memory management, process management, and hardware resource control, while other Android components are adapted for mobile devices.

---

### 7. Embedded Linux Capabilities and Areas of Use

Embedded Linux is used in embedded systems such as routers, televisions, industrial equipment, and other specialized devices. It provides stable operation, flexible configuration, and the ability to adapt to specific hardware requirements.

---

### 8. Switching Linux Boot Modes and Differences Between CLI and GUI

The Linux boot mode can be switched between text mode (runlevel 3) and graphical mode (runlevel 5) by configuring system startup parameters.

The **CLI** mode involves controlling the system using terminal commands, while the **GUI** mode uses a graphical interface with windows and menus. CLI is more flexible and precise, whereas GUI is more convenient for everyday use.
