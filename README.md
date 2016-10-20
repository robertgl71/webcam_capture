# webcam_capture
Just webcam capture and playing using OpenCV
hub

1. Create a new account on GitHub. https://github.com/

2. Once logged in your git account, go to:
https://github.com/beta-robots/webcam_capture.git
and find the button “fork”. Click it!. This action “forks” this repository to your git space,
so it creates a new repository in your git space with the same content.

3. Clone YOUR recently created (forked) repository to your local machine:
git clone https://github.com/my_github_name/webcam_capture.git

4. Install CMake:
$apt-get install cmake

5. Install OpenCV library:
$sudo apt-get install libopencv-dev python-opencv

6. Compile the project. Open a terminal, go to the CMakeLists.txt folder and write:
$cmake .
$make

7. Execute the project with:
$./webcam_capture
