# Bresenham-s-circle-drawing-algorithm-Computer-Graphics-
Bresenham’s circle drawing algorithm in C++

Download the Graphics Header File Setup for CodeBlocks and Dev cpp(Files are given)

Instruction for adding graphics file in Code::Blocks 
***************************************************************************************************

1) Copy "graphics.h" and "winbgim.h" files to "include" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\CodeBlocks\MinGW\include\")

2) Copy "libbgi.a" to file to "lib" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\CodeBlocks\MinGW\lib\")

3) Open CodeBlocks and go to (Settings > Compiler > Linker Settings)

4) Link Libraries (left), Click on "Add" button, then click "Browse" and select the "libbbgi.a"
   file that you have copied in CodeBlocks directory..
   Default location is (C:\Program Files (x86)\CodeBlocks\MinGW\lib\libbgi.a)
   and then click "Open" button.

5) Other linker option (right), copy the text below and paste there
   -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

6) Click "OK"

Done...

Instruction for adding graphics file in Dev C++
***************************************************************************************************

1) Copy "graphics.h" and "winbgim.h" files to "include" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\Dev-Cpp\MinGW\include\")

2) Copy "libbgi.a" to file to "lib" folder of CodeBlocks directory.
   Default location is ("C:\Program Files (x86)\Dev-Cpp\MinGW\lib\")

3) Open Dev-Cpp and go to (Tools > Compiler  Options > Compiler)

4) Yo can see this command
	-lglu32 -lglut32 -lopengl32

5) After the -lopengl32,add space and copy the text below and paste there
   -lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32

6) Click "OK"

Done...
