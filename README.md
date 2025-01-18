# My-ref-books repos
- A collection of all the books which I have read or will be reading some day.
- Collection created using 'git lfs'.

## Instructions to upload all the files at once:
- clone the repo
- Add your files to the repo locally
- install 'git lfs' using "brew install git-lfs" in the terminal (for mac)
- cd to the repo, and run 'git lfs install'
- run "git lfs track "*.pdf"", replace the extension with whatever your file ext is
- run "git add ."
- run "git commit -m "commit message""
- git push -u origin main

## Instructions to upload a single file (one at a time):
- clone the repo
- Add your file to the repo locally
- install 'git lfs' using "brew install git-lfs" in the terminal (for mac)
- cd to the repo, and run 'git lfs install'
- run "git lfs track "\path\of\your\file.pdf"
- run "git add ."
- run "git commit -m "commit message""
- git push -u origin main
