# OreolQGroundControl

Edited version


##### Option 2: Build with CMake
1. Create and navigate to a build directory:
   ```bash
   mkdir build && cd build
   ```
2. Configure the project:
   ```bash
   ~/Qt/6.8.3/gcc_64/bin/qt-cmake -G Ninja -DCMAKE_BUILD_TYPE=Debug ..
   ```
   > Replace `~/Qt/6.8.3/gcc_64` with your Qt installation path if different.
3. Build the project:
   ```bash
   cmake --build . --config Debug
   ```
4. Run QGroundControl:
   ```bash
   ./Debug/QGroundControl
   ```

#### 5. Create Installation Files (Optional)
To generate installation files:
```bash
cmake --install . --config Release
```
