# Welcome!
Hello students! This guide is to walk you through how to convert a Markdown file (.md) to a Microsoft Word file (.doc/.docx). There are step-by-step tips to help this process be as easy as possible. Lets get started!
# How to Convert Markdown to a Word File Using Pandoc 

## Tools 
-	A selected file from Markdown (.md) 
-	Pandoc downloaded and installed on your computer 
-	Visual Studio Code downloaded and installed on your computer 
## Steps 
1)	Begin by opening your Markdown file in VS Code <br> 
    - For the purpose of this guide our Markdown file will be `"spring.md"`
2)	Go to your Command Prompt/computer terminal and change directory (cd) to the folder that contains your `"spring.md"` file <br> 
    - To change directory type `"cd"` in the terminal, hit space, and drag the folder holding `"spring.md"` into the computer terminal 
3)	Now write the conversion code in the computer terminal/Command Prompt <br> 

**Note:** Commands needed are as follows - <br>  
>>>**Pandoc** = The main control <br>
**-s** = Source file <br>
**-o** = Output file <br>
	
**The Conversion Code:** <br>
	`_pandoc -s spring.md -o spring.docx_`

After entering the conversion code press `'enter.'`<br> When you look in your folder holding the original Markdown file, there should be a copy of that file as a newly converted Microsoft Word file.




<br>[Back to Home Page](index.md)