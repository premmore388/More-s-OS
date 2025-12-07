# 🖥️ More-s-OS

> A custom Operating System built from scratch in JavaScript — a deep dive into low-level programming and OS fundamentals.

![OS Development](https://img.shields.io/badge/OS-Development-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Assembly](https://img.shields.io/badge/Assembly-654FF0)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎯 About

**More-s-OS** is an educational operating system project that explores the fascinating world of low-level programming. Built as a learning journey, this project demonstrates how computers boot up and execute code at the most fundamental level.

This project was inspired by and built following the excellent tutorial by [dr Jonas Birch](https://www.youtube.com/@drJonasBirch).

---

## ✨ Features

- 🔄 Custom bootloader implementation
- 🧠 Kernel execution flow
- 💾 Memory management fundamentals
- ⚡ Interrupt handling
- 🔧 Low-level hardware interaction

---

## 🚀 Quick Start

### Prerequisites

- Linux environment (Ubuntu recommended)
- GCC Toolchain
- QEMU emulator
- GRUB bootloader
- Node.js

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/premmore388/More-s-OS.git
   cd More-s-OS
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the OS**
   ```bash
   # Instructions for running with QEMU
   qemu-system-x86_64 -drive format=raw,file=boot.bin
   ```

---

## 📁 Project Structure

```
More-s-OS/
├── boot.bin        # Compiled bootloader binary
├── main.js         # Main JavaScript entry point
├── tmp.asm         # Assembly source code
└── package.json    # Node.js dependencies
```

| File | Description |
|------|-------------|
| `boot.bin` | The bootloader binary that initializes the system |
| `main.js` | Core JavaScript logic for OS operations |
| `tmp.asm` | Low-level Assembly code for hardware interaction |
| `package.json` | Project configuration and dependencies |

---

## 🎓 What I Learned

Building this OS from scratch taught me:

| Concept | Description |
|---------|-------------|
| **Bootloaders** | How computers start up and load the kernel |
| **Kernel Execution** | The flow from BIOS to running code |
| **Memory Management** | Allocating and managing system memory |
| **Interrupts** | Handling hardware and software interrupts |
| **Assembly** | Writing low-level code for x86 architecture |
| **QEMU & GRUB** | Using emulators and bootloaders for development |

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C"/>
  <img src="https://img.shields.io/badge/Assembly-654FF0?style=for-the-badge" alt="Assembly"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white" alt="GCC"/>
  <img src="https://img.shields.io/badge/QEMU-FF6600?style=for-the-badge&logo=qemu&logoColor=white" alt="QEMU"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📺 Credits & Resources

- **Tutorial**: [dr Jonas Birch](https://www.youtube.com/@drJonasBirch) — for the amazing OS development tutorial
- **Tools**: QEMU, GRUB, GCC Toolchain

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Prem More**
- GitHub: [@premmore388](https://github.com/premmore388)
- LinkedIn: [Connect with me](https://www.linkedin.com/in/premmore)

---

<p align="center">
  <i>⭐ Star this repo if you found it interesting!</i>
</p>
