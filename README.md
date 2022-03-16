# Make sure you have python3 and git installed for Windows

## To install git
Visit https://git-scm.com/download/win and download the newest version and follow the magic wizard

## How to install TeXlinter Windows
git clone "https://github.com/maRkyB0019/TeXlinter.git"

## If you want to access TeXlinter.exe from anywhere copy the following command
## Start cmd as administrator
setx /M PATH "%PATH%;your-new-path-to-TeXlinter-folder"

## How to use the TeXlinter
TeXlinter.exe "your LaTex document"
## If you have your own rules
TeXlinter.exe "your LaTex document" --rules <your own rule .json or .yaml>
## If you want to see what have changed
TeXlinter.exe "your LaTex document" --header
## If you need a reminder
TeXlinter.exe help

## If you want to run a test and see what the linter changes
## Run the following
TeXlinter.exe --header "path to TeXlinter folder/test.tex"
