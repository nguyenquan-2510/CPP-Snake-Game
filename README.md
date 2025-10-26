# CPP-Snake-Game
A snake game written in C++ with Raylib

Ok no replay yet :)
Dont ask me .. Cuz i copy the code line by line


#############################################################
CONFIGURE RAYLIB FOR VISUAL STUDIO

1. Yes obviously u need to install VS and C++ desktop development tick for installation xD
2. Install vcpkg ( Idk what is this )
   - Clone this repository: https://github.com/microsoft/vcpkg.git
   - Head to the target folder and open in terminal
   - type .\bootstrap-vcpkg.bat
     + If you can not run, check the Set-ExecutionPolicy and change to something like bypass or allsigned
       not restricted ( have to use administrator shell )
  - run ./vcpkg integrate install
  - run ./vcpkg install raylib:x64-windows ( or somthing else )
3. Add #include <raylib.h> and some libs related to this to your code

################################################################
