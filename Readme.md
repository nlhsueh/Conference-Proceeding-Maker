
# ProceedingMaker Project

When you use **EashChair** to manage your paper submission and review, this ProceedingMaker is especially good to work with.

## How to Use This Maker 
1. Download all final version PDF files from EasyChair, put to ./paper directory. Note that in this demo project, I just put a little fake papers.
2. Modify the TCSE.tex (of course you can rename to your conference name) to make the proceeding. If you have experience of latex, I believe that is easy to you.
3. ./paperList.tex is the file to organize your sessions. I recommend you 
    1. copy paper information from EasyChair to the a excel file, such as agenda.xlsx 
    2. arrange the sessions in the agenda.xlsx
    3. (optional) add some texts for formating latex file in the next step
    4. copy the text from .xlsx to the paperList.tex 

## Configuration

You may want to make a Conference Manual (大會手冊) or 論文集 (proceeding), Then you can choose to print one-page or all-pages.
1. \ShowPapertrue: show papers or not
2. \AllPagetrue: show all pages or not. When this is true, you should set \OnePagefalse
