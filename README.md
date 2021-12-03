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
```bash
./trishul --help


 _______   _     _           _             __   ___  
|__   __| (_)   | |         | |           /_ | / _ \ 
   | |_ __ _ ___| |__  _   _| |________   _| || | | |
   | | '__| / __| '_ \| | | | |______\ \ / / || | | |
   | | |  | \__ \ | | | |_| | |       \ V /| || |_| |
   |_|_|  |_|___/_| |_|\__,_|_|        \_/ |_(_)___/ 
   
Author: z3r0day
Copyright (c) 2021

Usage: 
./trishul [-h or --help] [-d or --dir]=<directory-path-to-start recursive search from> [-f or --file=file-names to look for in single quotes seprated by commas] [-s or --strings=strings to search for in given file-names, each strings should be in single quotes seprated by commas and in double quotes together [-t or --type txt]

Options:
  -h, --help            show this help message and exit
  -d DIR_PATH, --dir=DIR_PATH
                        specify the directory path to recursively search
  -f FILE_NAMES, --files=FILE_NAMES
                        specify keywords to look for in filenames seprated by
                        commas, wrapped in double quotes overall note that
                        specifying * scans all files with specified
                        extension
  -s STRINGS, --strings=STRINGS
                        specify strings to look for seprated by commas,
                        wrapped in double quotes overall
  -l LEVEL_NUMBER, --level=LEVEL_NUMBER
                        specify level of default files and keywords to look
                        for, only required if you don't specify custom files
                        and strings, note that default level is 0
  -t TYPE_OF_FILE, --type=TYPE_OF_FILE
                        specify file types, supported types are .csv,.doc,.doc
                        x,.eml,.epub,.gif,.htm,.html,.jpeg,.jpg,.json,.log,.mp
                        3,.msg,.odt,.ogg,.pdf,.png,.pptx,.ps,.psv,.rtf,.tab,.t
                        ff,.tif,.tiff,.tsv,.txt,.wav,.xls,.xlsx,csv,doc,docx,e
                        ml,epub,gif,htm,html,jpeg,jpg,json,log,mp3,msg,odt,ogg
                        ,pdf,png,pptx,ps,psv,rtf,tab,tff,tif,tiff,tsv,txt,wav,
                        xls,xlsx and default type is set to
                        .txt,.docx,.doc,.xml,.pdf,.xls,.xlsx
  -v VERBOSE_VALUE, --verbose=VERBOSE_VALUE
                        specify value for verbosity 0 or 1, 0 for
                        disabling and 1 for enabling only required when
                        looking for non text files

```

## Options with Trishul
