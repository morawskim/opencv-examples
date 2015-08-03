Facedetection is simple C++ program, which detects faces. Required openCV library.

Compiling
===========================
Download git repo

    git clone git://github.com/morawskim/opencv-examples.git 

Go to facedetection subdir

    cd ./facedetection

Go to build dir

    cp ./build/
    
Run cmake

    cmake ..

Compile

    make
    
Add finally run program

    opencv_facedetection path/to/image/with/people.jpg
