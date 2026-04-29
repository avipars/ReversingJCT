# Guide for Installation of Tools 

[View Full PDF](https://github.com/avipars/ReversingJCT/blob/main/Installs/Install%20Guide.pdf)

## Quick Links:
 
[Notepad++](https://notepad-plus-plus.org/downloads/)
- Make sure to select English while installing

[FASM and Training files](https://data.cyber.org.il/assembly/32bit/installs.zip)
- Follow the PDF guide (above) to setup FASM properly

- You can also get the files [here](https://github.com/avipars/ReversingJCT/raw/refs/heads/main/Installs/installs.zip)

- Or see them unzipped [here](https://github.com/avipars/ReversingJCT/tree/main/Installs/unzipped)

- Note: training.inc needs to be in the same directory of your ASM file that includes it. You can edit the ASM file by replacing ```include 'training.inc'``` with ```include 'C:\path\to\training.inc'``` (change path\to\ to the directory that has the training file)

[IDA-Free](https://hex-rays.com/ida-free/)
- Download the free version and then [set up your account and get a license](https://my.hex-rays.com/dashboard/licenses)
  * See [this guide](https://docs.hex-rays.com/getting-started/licensing#computer-licenses-activation) for more details 


## Bonus Stuff: 

- Install a hex editor plugin in Notepad++ or VSCode 

- If you are using VSCode, I made a tasks.json file which provides shortcuts for assembling and running your programs
   * In the parent directory, add a new folder named .vscode and inside place this [tasks.json](https://github.com/avipars/ReversingJCT/blob/main/.vscode/tasks.json) file
