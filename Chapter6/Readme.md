How to compile the code

1.Go to folder src/ 

2.Open terminal in current path

3.Run command “javac Assembler.java” and “javac FileHelper.java”(java is required to be installed)

4.After compiling, there will be an “Assembler.class” and a “FileHelper.class” file in current path

How to run the code

1.Command format is “java Assembler path”. There is no need to place the .asm file in the same path with .class files. But if the .asm is in src/, you should add “./” before the filename

Example:
	java Assembler ./Fill.asm (if Fill.asm in src/)
	java Assembler ../Fill.asm (if Fill.asm in the parent directory of src/)
	java Assembler (absolute path of the file)

After finishing translation, there will be a .hack file with same name in the same path of the .asm file.
If you run “java Assembler /Users/Fill.asm”, there will be a Fill.hack in /Users/
