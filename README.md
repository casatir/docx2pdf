docx2pdf
========

An ugly-but-working way for docx to pdf conversion.

Who never get annoyed by a stupid doc/docx file sended by an also st**id collaborator that can't be properly opened/viewed without Microsoft Word ©?

This simple python script try to calm you down. 

# How to use it

Just do 

    docx2pdf /path/to/my/doc/or/docx/file.docx

in a terminal. The converted file just go to the same location of the docx one adding pdf extension.

# How does it works so well?

It just call an online converter [`conv2pdf.com`](http://www.conv2pdf.com) with the excellent [mechanize](http://wwwsearch.sourceforge.net/mechanize/).

# A nice GUI for non-geek (non-terminal) users?

Maybe...

