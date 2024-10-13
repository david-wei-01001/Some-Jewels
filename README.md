- How to use GhostScript to flatten pdf?

  1. [Download GS](https://www.ghostscript.com/releases/gsdnld.html)
  2. In PowerShell, run:
  ```bash
  gswin64c.exe -dSAFER -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -dPDFSETTINGS=/prepress -dPassThroughJPEGImages=true -dPreserveAnnots=false -sOutputFile=<Out File Name> <In File Name>
  ```
- [This Tool will handle Everything about file coversion, manipulation, annotation, ...](https://smallpdf.com/#r=app)
