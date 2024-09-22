simple .exe for windows only, 
batch-process PDFs and strips them to plain text. 
Allows you to quickly add multiple files and folders to build a "source list" which is then used to iterate through and build a "File list" to convert to plain text. 
Searches sub-folders recursively. 
Currenlty only supports PDF's and .TXT 

the purpose of this application is to automate the process of preparing documents for vector embeddings.

Written in VB.NET using .net framework 4.5. and PDFium (nuget package) 


main App:

![image](https://github.com/user-attachments/assets/7c150908-30f6-42e7-9321-1acd20ad4a1f)

manage your sources, by individual files or by directories on mass 

![image](https://github.com/user-attachments/assets/f132fda8-4324-4c23-9dfd-76e13fc8650a)

add by directory 

![image](https://github.com/user-attachments/assets/558dc861-fb4f-42f9-b2fe-72011280ade5)

add multiple directories quickly 

![image](https://github.com/user-attachments/assets/e1c74424-662d-418e-8d20-a01aff4fe338)

all valid files (PDF / .txt so far) in all sub-folders recursively will be added.  

![image](https://github.com/user-attachments/assets/51f5cd67-2ef8-461e-8beb-292e2966c1d5)

customize your options 

![image](https://github.com/user-attachments/assets/ad8b305e-f807-4301-b604-3b21422341cb)

configure your outputs
you can write the plain text to the same directory as each origin file, or collated all of them to a new custom directory. 
you can also keep the original file name, choose a prefix, suffix, or an entirely custom name. 
if splitting by pages, it automatically names each new page file so nothing is overwritten. 

![image](https://github.com/user-attachments/assets/b0682200-79cc-4499-87d0-38f074b0092d)

