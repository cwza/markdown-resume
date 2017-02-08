
## install
``` sh
git clone https://github.com/cwza/markdown-resume.git
npm install
```

## write resume
``` sh
vim ./example/source/cwzZhResume.md
vim ./example/source/cwzEnResume.md
```

## generate resume html
This command will generate html to ./examples/output
``` sh
npm start
```

## deploy to github page
This command will deploy all files at ./examples/output to github pages at gh-pages branch
``` sh
npm run deploy
```

## Deployed Resume is at following path
https://cwza.github.io/markdown-resume/cwzEnResume.html 
https://cwza.github.io/markdown-resume/cwzZhResume.html
