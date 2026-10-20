# Capstone_Project_FEUP_24_25

This repository contains the work for my Capstone Project, the final course in the Bachelor's in Informatics and Computer Engineering at FEUP (Faculty of Engineering of the University of Porto).

Developed in collaboration with **Diogo Leandro**, **Martim Ferreira**, and **Angy Pita.**

## Repository Structure

- [**PI_24_25_FEUP**](https://github.com/luhen39/PI_24_25_FEUP)
    - Contains the development, organization, and documentation as part of the Curricular Unit "Capstone Project".
    - It includes supporting documents, such as user guides (`Guião Milk-V.pdf`), a final report, and a project poster, which provide essential information on setup and implementation.
    - Structured with directories for test programs and compilation templates. The test programs evaluate various POSIX system calls related to standard I/O (e.g., `printf`, `read`/`write`), process management (`fork`, `pipe`), and thread operations (`pthread` functions).
    - For detailed instructions on how to perform tasks and configure the environment, please refer to the documentation present [**here**](https://github.com/luhen39/PI_24_25_FEUP).

- [**minimal_module_compilation**](https://github.com/luhen39/minix_milk_v_duo_s/tree/minimal_module_compilation)
    - Contains an adapted version of the **Linux Usermode Driver Platform (UMDP)** kernel module, originally created by [**Joaquim Monteiro**](https://github.com/MonterraByte/linux-usermode-driver-platform), which allows user-space applications to interact directly with hardware.
    - The modifications, focused on files `umdp_ac.c` and `umdp_core.c`, ensure compatibility with embedded systems based on the **RISC-V** architecture, specifically the **Milk-V Duo S**.
    - It includes simplified build scripts for cross-compiling the kernel module (`umdp.ko`) and the static library (`libumdp.a`) using the **RISC-V** toolchain, providing all the necessary instructions for deployment and execution on the target device.

### Note

Please note that both linked repositories contain documentation and comments primarily in Portuguese. English translations are not provided, interested users should translate content as needed.

---

Final Grade: 16/20
