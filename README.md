```
-all x64:
--C/C++
---General
----Additional Include Directories: C:\SFML-2.5.1\include;
--Linker
---General
----Additional Library Directories: C:\SFML-2.5.1\lib;


-debug x64:
--C/C++
---General
----Additional Include Directories: C:\SFML-2.5.1\include;
--Linker
---General
----Additional Library Directories: C:\SFML-2.5.1\lib;
--Linker
---Input
----Additional Dependencies: sfml-system-d.lib;sfml-window-d.lib;sfml-graphics-d.lib;


-release x64:
--C/C++
---General
----Additional Include Directories: C:\SFML-2.5.1\include;
--C/C++
---Preprocessor
----Preprocessor Definitions: SFML_STATIC;
--Linker
---General
----Additional Library Directories: C:\SFML-2.5.1\lib;
--Linker
---Input
----Additional Dependencies: sfml-system-s.lib;sfml-window-s.lib;sfml-graphics-s.lib;winmm.lib;opengl32.lib;freetype.lib;



--C:\SFML-2.5.1\bin Copy all the dll files located in the .\x64\Debug folder of the project
```
