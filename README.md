# SumtraPDF-modified
To change the theme to dark or darker, the background color of files can change by "Backgroudcolor" tag in setting file in 3.5 version.
Besides, in the light mode, the background color of the bookmark box also can change by "MainWindowBackground" tag.

I just remove 'if (currentThemeIndex == 0)' in file Theme.cpp, since users can customize all colors both in LightTheme and DarkTheme, and the overall colors of sumatrapdf in user interface look very consistent and beautiful.

HOW TO: just replace the original sumatrapdf.exe with the one.
<img width="1080" alt="image" src="https://github.com/FLongWang/sumatraPDF-modified/assets/55866242/02871804-63f1-4980-845b-44a796f85289">



Please read https://github.com/sumatrapdfreader.
