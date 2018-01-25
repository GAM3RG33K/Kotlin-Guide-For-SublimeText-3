# Kotlin-Guide-For-SublimeText-3
This Guide is useful for windows based Sublime Text 3 Editor

Follow the following steps to install kotlin language build in SublimeText 3:

1. Install Kotlin build package:
	1. Go to : Preferences -> Package Control -> Install Package
	2. Type Kotlin and click on "kotlin for sublime 2"
	3. Close Sublime Text 3

2. Install kotlin Compiler on windows:
	1. Install kotlin complier:
		Latest release can be found here : 
			https://github.com/JetBrains/kotlin/releases

	2. Download and extract the archive any where you want
		Let's call that path : %KOTLIN_DIR%

3. Add kotlin compiler path to Environment variables:
	1. Go to Desktop
	2. Right Click on My computer(for win 7) OR Computer (for win8+)
	3. Click on Properties
	4. Go to Advanced System Settings -> Advanced -> Environment Variables
	5. Select "Path" variable from System variables
	6. add following path at the end of the Value:

		for example (kotlin-compiler-1.2.21): 
			Path = %KOTLIN_DIR%\\kotlin-compiler-1.2.21\\kotlinc\\bin
	7. Save the path.

