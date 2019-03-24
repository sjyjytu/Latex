# Latex

how to configure vscode and texlive?

1. download them

2. download  LaTex Workshop for vscode

3. open vscode, click file->Preferences->setting

4. ![1553444081130](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1553444081130.png) click this to open setting.json

5. add this code to the setting.json

6. ~~~json
   "latex-workshop.latex.recipes": [
           {
             "name": "pdflatex",
             "tools": [
               "pdflatex"
             ]
           },
           {
             "name": "latexmk",
             "tools": [
               "latexmk"
             ]
           },
           {
             "name": "pdflatex -> bibtex -> pdflatex*2",
             "tools": [
               "pdflatex",
               "bibtex",
               "pdflatex",
               "pdflatex"
             ]
           }
       ],
       "latex-workshop.view.pdf.viewer": "tab"
   ~~~

7. like this:![1553444240546](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1553444240546.png)

8. finally:![1553444523891](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1553444523891.png)

9. then you will see![1553444557264](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1553444557264.png)

   

