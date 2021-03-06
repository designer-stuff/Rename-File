# @sumitkumar01/rename-file

![](https://img.shields.io/badge/RenameFile-v1.0.0-blue)

## A tiny package that can help you save a lot of precious time.

Have you ever encountered any situation when you are stuck with hundreds of files having names like FILE1, FILE2, FILE3 and so on. And the story doesn't end here. Now you have to arrange those files into different folders too. Sounds like an interesting task. Right 😁.

Well, if doing that task manually sounds like an awesome job. Then, I am sorry to say this tool is not for you 😔.

This tool will help you complete the task of hours or even days within seconds. Well, it's not a ninja technique. It's the power of code.

Enough with the introduction. Let's see how this tool works....

## Demo

![Demo!](/assets/Demo.gif)

**Titles Source:** [The Ultimate Git Mastery Course](https://codewithmosh.com/p/the-ultimate-git-course)

## Prerequisites

Let's do the preparation before seeing the actual magic

- First thing first and **very important**- Take **backup** of your files
- Make sure that the parent folder only contains two types of files - A **titles.txt** (pay attention to the naming convention) and files that needs to be modified
- Make sure that the titles.txt file contains the filea and directories name in the order that you want to arrange them
- Make sure that the files are as per the sequence in titles files
- Make sure _node.js_ is installed in your system

> **_titles.txt_** file structure should be as follows:
>
> Directory name should start with an capital Alphabet.
>
> For Ex: A. Directory Name 1 <br>
>
> File names should start in the format in which you prefer to sequence your files in the directory
>
> For Ex: 1. File Name1 or i. File Name2 etc.
>
> Sample Data:
>
> ![Demo!](/assets/data.png)
>
> **Titles Source:** [The Ultimate Git Mastery Course](https://codewithmosh.com/p/the-ultimate-git-course)\_

When all these arrangements are done you are ready to proceed further.

> **A gentle reminder please take backup of your code before running this tool**

## Software Requirements

This tool requires [Node.js](https://nodejs.org/) to run.

Verify if node is installed on your system.

```sh
npm --version
```

## Options

This package requires two arguments:

- --path - The path of the parent folder
- --ext - The extension of the files

## Execution

To run this package follow the below steps:

- First download the code to your local system either by downloading the zip and then extracting it or by using the command below

```sh
git clone https://github.com/designer-stuff/Rename-File.git
```

- Goto the downloaded folder and open `CMD` prompt in the same location

- Now run the below commands

```sh
npm install
```

```sh
npm run renameFile -- --path="<path of the parent folder>" --ext="<file extension>"
```

> **Note:** The path and extension arguments accepts string values.

## Development

Want to contribute? Great!

Please fork this project on [Github](https://github.com/designer-stuff/Rename-File)

## License

MIT

**Try it! It's FREE 👨‍💻. I hope this tool will be useful to you**
