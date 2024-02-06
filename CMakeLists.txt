# Setzt die minimale erforderliche Version von CMake
cmake_minimum_required(VERSION 3.12)

set(CMAKE_TOOLCHAIN_FILE "/usr/share/emscripten/cmake/Modules/Platform/Emscripten.cmake")
# Definiert das Projekt und die verwendete Sprache
project(MyProject CXX)
# Setzt den C++-Standard
set(CMAKE_CXX_STANDARD 17)
# Fügt die Emscripten-Include-Verzeichnisse hinzu

# Fügt eine ausführbare Datei hinzu
add_executable(thorsten main.cpp)