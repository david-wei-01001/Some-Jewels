- How to use GhostScript to flatten pdf?

  1. [Download GS](https://www.ghostscript.com/releases/gsdnld.html)
  2. In PowerShell, run:
  ```bash
  gswin64c.exe -dSAFER -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -dPDFSETTINGS=/prepress -dPassThroughJPEGImages=true -dPreserveAnnots=false -sOutputFile=<Out File Name> <In File Name>
  ```
- [This Tool will handle Everything about file coversion, manipulation, annotation, ...](https://smallpdf.com/#r=app)

- how to SCP via jump host?
  ```bash
  scp -o ProxyJump=<Jump Host> <Local Path to File> <Final Host>:<Path to Folder>
  ```
  or copy back:
  ```bash
  scp -J <Jump Host> <Final Host>:<Path to File> <Path to Folder>


- How to open .ssh/config?
  1. Press Ctrl + O (or Cmd + O on macOS)
  2. go to *.ssh* then *config*
