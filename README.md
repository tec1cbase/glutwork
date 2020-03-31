
//  ---(FREEGLUT-freeglut-3.2.1)---------------
//  --Vande burg scales 3-31-2020 -- 
//  --Brian E Boothe -- 
////////////////////////////////////////////////////////
// # Compiling Freglut Project in terminal with g++ 
// only  Create a.out file  
// g++ filename.cpp -lGL -lGLU -lglut

// Compile Terminal 

// Compiled only::   g++ gl.cpp -o gl -lGL -lGLU -lglut

//Full Compile
g++ freeglut1.cpp -lX11 -lGL -lGLU -lglut -g -Wall -O2 -o freeglut1

//freeglut2.cpp     > producees a.out 
// ./a.out
gcc freeglut2.cpp -lGL -lGLU -lglut -lm 

