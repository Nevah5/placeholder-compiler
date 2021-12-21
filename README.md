# placeholder-compiler
## About this repo
In this repository, you can find a compiler, that replaces placeholders (`${placeholertitle}`) in the specified file (`index.php`).

## How to use
To use the project, you just execute the index file with php.<br>
To edit the input and output file names, just edit lines `3-5` in `index.php`.
```
$input = "template.html";
$file_replacements = "input.txt";
$output = "index.html";
```

IMPORTANT!
You can only use one placeholder per line in the input file!
