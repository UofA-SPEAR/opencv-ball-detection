# opencv-ball-detection
This will be used to detect tennis balls from a video feed.

Note: you will need to have opencv and cmake installed.

```bash
sudo apt-get install libopencv-dev
sudo apt-get install cmake
```

## Build Instructions

1. Clone this repo

```bash
git clone https://github.com/UofA-SPEAR/opencv-ball-detection.git
cd opencv-ball-detection
```

2. Create a build directory, run cmake, then run make

```bash
mkdir build
cd build
cmake ..
make
```

3. Run the compiled program

```bash
cd ..
./build/main tennis.jpg
```
