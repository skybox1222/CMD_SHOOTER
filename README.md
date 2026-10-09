# CMD Shooter 🚀

An action-packed retro **shoot 'em up game running entirely inside the Windows Command Prompt**. This project uses a clever character-mapping technique to render detailed pixel art sprites directly into the console, complete with background music and retro sound effects.

<img width="1115" height="628" alt="image" src="https://github.com/user-attachments/assets/b5c18027-5ddd-4852-96bc-3e77691b57ff" />

<img width="1115" height="628" alt="image" src="https://github.com/user-attachments/assets/8cb72b4a-faf9-4670-94b9-e6d0a0cc286e" />


## 🕹️ Features
* **Console-Based Action:** Classic scrolling shooter gameplay right in your CMD.
* **Character-Pixel Art:** Custom sprites drawn using a unique text-character formatting trick to simulate real pixels.
* **Retro Audio:** Built-in background music and sound effects (`.wav`) for an immersive arcade experience.
* **Lightweight & Fast:** Built entirely in C++ using native Windows APIs.

## 🛠️ Built With
* **Language:** C++
* **IDE:** Visual Studio
* **Libraries:** Native Windows API (`Windows.h`, `mmsystem.h` for audio)

## 🚀 How to Run

### Prerequisites
* A Windows Operating System.
* Visual Studio (with Desktop development with C++ workload installed).

### Steps to Compile and Play
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. Open the solution file `CMDSHOOTER.sln` in **Visual Studio**.
3. Set the build configuration to **Release** and **x64** (or x86 depending on your setup).
4. Press `Ctrl + F5` to compile and run the game.

## 📂 Project Structure
* `CmdShooter.cpp` - The main game loop, logic, and rendering engine.
* `Resource.rc` & `resource.h` - Windows resource files embedding the audio and icons.
* `retro.wav` - The game's sound effects and soundtrack.
* `CMDICO.ico` - Custom application icon.

## 📄 License
This project is open-source. Feel free to use, modify, and share it!

