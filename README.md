
<img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg">

<div id="header" align="center">
    <img width="250" src="https://media0.giphy.com/media/l3y66DUgpND7AohGS2/200w.gif?cid=82a1493bphdpqia18ll7exnm8k9xpia58ttp8rr4mijoz6g9&rid=200w.gif&ct=s">
  
Automates/facilitates creation of temporary file folders.
  </div>
  
  
## 💭 Installing
1. First clone my repository ``git clone https://github.com/mavinsi/gbman``
2. Give execution permission to the script ``sudo chmod +x install.sh``
3. now run the install script ``sudo ./install.sh``
## 🚮 Tutorial


### How create a trash storage directory?
To create your directory to throw your garbage is very simple just type: ``gbman create`` or ``gbman cr``
    
```
 gbman create 
[GarbageMan] - Created garbage collection directory.
```
    




### How to send your file to the trash storage directory
To upload your file to the collection directory, just type: ``gbman get filename/directory``
    
```
> gbman get useless_files.jar
[GarbageMan] - Looking for useless_files.jar
[GarbageMan]  - trash collected
```
    




### How to discard a file?
To dispose of your garbage, in gbman we have 2 options, a light one where your files are sent to /tmp/
on your system and another where they are automatically removed.

    
To soft clean just type: ``gbman clean`` or ``gbman cl``
```
> gbman clean
[GarbageMan] - I found 1 trash's files
[GarbageMan]  - Your garbage has been collected    
```
 
<br>
    
To hard clean just type: ``gbman cleanf`` or  ``gbman clr``
```
> gbman cleanf
[GarbageMan] - i found 1 trash's files
[GarbageMan]  - incinerate your trash
 ```

