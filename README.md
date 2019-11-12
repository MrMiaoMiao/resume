# Resume Template

## Prerequisite
A full TeX distribution is assumed. Especially sure you have `xelatex` installed.
```bash
sudo apt install texlive-full
```

## Editing
1. Modify personal information in `personal_info.tex`
2. Modify any configuration or colour variables in the main `tex` files.
3. For `resume` and `cv`, all sections are included in their respective folders. You can add or remove sections following the same format
    a. Include the necessary sections in `resume.tex` or `cv.tex`
4. For `coverletter`, sections are included in the `coverletter.tex` file itself.
5. Make the resume! (see below)

## Compiling
All auxiliary files will be put in the `build` directory and all generated pdfs will be put in the `output` directory
- Running `make` will compile the `resume`, `cv`, and `coverletter` pdfs
- Running `make (resume|cv|coverletter)` will make that specific file
- Running `make clean` will remove the `build` directory
- Running `make cleanall` will remove the `build` and `output` directories
