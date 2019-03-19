# HTML to PDF

#### Requirements :

  1. Create a sample HTML file inside of your project.
  2. Download go package using the below command for parsing the HTMl template.
    ``go get "github.com/SebastiaanKlippert/go-wkhtmltopdf``
   
  3. We need to download another package for converting this html parse data to pdf using the below command.
    
       ``go get "html/template"``  
       
  4. Make sure to download the below library in your system using the following command.  
    ``sudo apt install wkhtmltopdf`` 
  
Now Start your code for generating pdf file from html.
Don't forget to mention your html and pdf path details inside your code.  
           