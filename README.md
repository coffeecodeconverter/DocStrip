simple .exe for windows only, 
batch-process PDFs and strips them to plain text. 
Allows you to quickly add multiple files and folders to build a "source list" which is then used to iterate through and build a "File list" to convert to plain text. 
Searches sub-folders recursively. 
Currenlty only supports PDF's and .TXT 

the purpose of this application is to automate the process of preparing documents for vector embeddings.

Written in VB.NET using .net framework 4.5. and PDFium (nuget package) 


main App:

![image](https://github.com/user-attachments/assets/3884da9a-e923-495e-88c9-8948d4d755e6)


manage your sources, by individual files or by directories on mass 

![image](https://github.com/user-attachments/assets/d7289ecb-d01d-498b-8317-4a9009bd89f0)


add by directory 

![image](https://github.com/user-attachments/assets/d96d4472-9805-4771-b307-2f3924bcd41a)


add multiple directories quickly 

![image](https://github.com/user-attachments/assets/9e83647b-c31e-43bf-b958-8ab2a48cb8d7)



all valid files (PDF / .txt so far) in all sub-folders recursively will be added.  

![image](https://github.com/user-attachments/assets/1e230aad-1d83-4ad9-bbfd-7c3f60326f51)


customize your options 

![image](https://github.com/user-attachments/assets/7f4034c0-e9bc-4c9f-ab85-c3d3576341af)


configure your outputs
you can write the plain text to the same directory as each origin file, or collated all of them to a new custom directory. 
you can also keep the original file name, choose a prefix, suffix, or an entirely custom name. 
if splitting by pages, it automatically names each new page file so nothing is overwritten. 

![image](https://github.com/user-attachments/assets/0722bbd4-49ae-4ece-a872-26cfae19a15b)


