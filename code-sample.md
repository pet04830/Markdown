# Code Samples

As a tech writer, you may find yourself *embedded* or partnered with 
an engineering team, such as an application team in a tech startup 
or a larger company like 3M or Honeywell.
Thats why we need to know the tools that engineers use, such as Markdown 
and GitHub. 
Thats called *Docs as Code*

As a tech writer with an engineer team, you may need to document 
code. You don't have to understand the code, just document it. 

For example, you might need to document a command. 
One command that processes Markdown is `pandoc`

**Note** To format inline code, use a backtick before and after the 
inline code. 

For example, to use `pandoc` to convert a Markdown File to something else, 
like Word document (`docx`) use this command:

    pandoc --from markdown --to docx file.md -o file.docx
Jim hates using 4 spaces to do code blocks. Thats becuase Jim is rea;ly old 
and learned (when he was your age) a super p;d programing language called 
FORTRAN 77. 
IN FORTRAN, leading spaces are significant.
Another way to make code blocks without leading spaces is to us a 
*code fence*. Thats three backticks before and after the code sample.

```

          INTEGER I 
          DO 10 I=1,10
 10       PRINT *,I
```
