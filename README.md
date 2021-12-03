# Trishul
<p align="center" >
  <img src="https://github.com/SxNade/Trishul/blob/main/extras/Triishul.webp" width="500"/>
</p>

**Trishul searches for sensitive data with options to specify custom files and custom keywords to look for in filesystem**

## Prerequisites 

**Before you can start using Trishul you need to install some dependencies that Trishul depends on**
___
### Installing textract and antiword

*Trishul utilizes the powerful textract library to extract text from any type of non-txt file such as xlsx,docx or even jpegs and mp4s*
```bash
# you can install textract with pip3 
pip3 install textract
```

*antiword is something utlized by textract itself to process .doc files into .docx and then extract text from them*
```bash
# we can simply use apt to install it
apt install antiword
```
## Installing and Running Trishul

**Once you have the dependencies in place, you can start using Trishul**

```bash
git clone https://github.com/SxNade/Trishul
cd Trishul
chmod +x trishul

./trushul --help
```

## Options with Trishul
