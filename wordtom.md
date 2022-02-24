# Welcome! 
 Hello students! This guide is to help assist you in converting a word file (.doc/.docx) to a Markdown file (.md). These step-by-step instructions should allow for a smooth transition while converting documents. Let's do this!
# How to Convert Word Files to Markdown Using Pandoc 

## Tools 
-	A selected document from Microsoft Word (.docx)
-	Pandoc downloaded and installed on your device
## Steps 
1.	Select a document from Microsoft Word <br>
    - For the purpose of this guide our Microsoft Word document will be `"autumn.docx"`
2.	Erase any presentation features 
<br> **Note:** These features may include Table of Contents or a fancy cover page

3.	Open computer terminal/Command Prompt and change directory (cd) to the file holding your Microsoft Word document <br>
    - To change directory type `"cd"` in the terminal, hit space, and drag the folder holding `"autumn.docx"` into the computer terminal
4.	In the computer terminal or Command Prompt application write the conversion code

**Note:** Commands needed are as follows - <br>  
>>	**Pandoc** = The main command <br>
	**-s** = Source file <br>
	**-t** = Target format
	<br> **--extract media** = Sets folder to retrieve messages 
	<br> **-o** = Output file 

<br>**The Conversion Code:** <br>
`_pandoc -s autumn.docx -t markdown --extract-media=images -o autumn.md_`

After typing the conversion code press `'enter.'` <br> When you look in your folder holding the original Word file, there should be a copy of that file as a newly converted Markdown file. 
	 



<br>[Back to Home Page](index.md)