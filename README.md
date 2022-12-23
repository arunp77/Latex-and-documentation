# Latex-and-documentation
Here I will be giving a detail overview of latex. 
### Things to remember before starting a latex file
- One of the important thing to remember is that all latex files have extension `.tex`. 
- Like HTML, you can separately provide a class style file with an extension of `.css`.
- You can add any image, draw table, change text color, change style of the text similar to HTML but with some other commands. 
- For adding image, you can put all images in same folder for sake of simplicity or you can also call any image from any directory by providing the path of the file.

### Things required before starting your first latex project
- **Latex compler:** Depending on the system that you have, you need to install first a latex compiler and then a latex editor (always remember, don't install latex editor before latex complier otherwise, you may face some problem during compilation of the latex file). Installation process can be found at the respective website. To get some information on the latex complier see the [link](https://www.latex-project.org/get/#tex-distributions).

    * **For windows:** There are mainly two latex compiler for the windows. These are [MiKTeX](https://miktex.org/) and [TeX Live](https://tug.org/texlive/windows.html)
    * **For MacOS systems:** Maxtex is extensivly used. You can find installer on the [official website](http://www.tug.org/mactex/).
    * **For a Linux system:** Linux based OS system like UBUNTU, FEDORA [Check all Linux based OS](https://www.stackscale.com/blog/popular-linux-distributions/)), you can install texlive or texmaker by following steps given at [textlive link](https://www.tug.org/texlive/quickinstall.html). On UBUNTU, you can install using following commands (run each line one after one)
    1. Before we install TeX Live to update the apt packages index, enter the following apt command with sudo:
    ```
    sudo apt update
    ```
    2. Now to install TeX Live (a texlive-full package which is around 5,828 MB) enter the following command in the terminal:
    ```
    sudo apt install texlive-full -y
    ```
    To install Texmaker, enter the following command in the terminal (after `sudo apt update`):
    ```
    sudo apt install texmaker -y
    ```
    * **Online latex compile:** You can also run and create latex file, online on [overleaf website](https://www.overleaf.com/). Just you have to create a account. If you have some work in group/collaboration then this is one of the best option. Here all team members can complie a latex file simultaneously 
    with any error. Here you can see your team members edits in real time. I have been using it from last 6-7 years and in research community this is used extensively. 

    After instaling the latex complier in your system, you can create a file with a extension of `.tex` and complie it via command line. For example in MacOs and any linux OS, use following command to create a pdf file after the complation. 
    ```
    pdflatex filename.tex
    ```

- **Latex editor:**
# LaTex
L<sup>A</sup>T<sub>E</sub>X is a tool for typesetting professional-looking documents. 

# Latex document basic format
Like HTML and other programming languages, you need to start with decalyring what kind of this document is. 

```
\documentclass{article}
\begin{document}
First document. This is a simple example, with no 
extra parameters or packages included.
\end{document}
```
Here Latex document 







# Reference

* For reference, you can follow [Overleaf webpage https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)