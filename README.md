
<img src="https://img.shields.io/badge/Made%20with-Bash-1f425f.svg">

<div id="header" align="center">
    <img width="250" src="https://media0.giphy.com/media/l3y66DUgpND7AohGS2/200w.gif?cid=82a1493bphdpqia18ll7exnm8k9xpia58ttp8rr4mijoz6g9&rid=200w.gif&ct=s">
  
Automates/facilitates creation of temporary file folders.
  </div>
  
  
## 💭 Installing
1. First clone my repository ``git clone https://github.com/mavinsi/gbman``
2. Give execution permission to the script ``sudo chmod +x install.sh``
3. now run the install script ``sudo ./install.sh``
4. 
## 🚮 Using

To create a repository of garbage, temporary or useless files type ``gbman create`` or ``gbman cr`` with that will be created a repository called ``gbdir`` (GarbageDirectory), in it you can add, clone in github repositories among other things that you will only use for a short period of time.
After you have done what you need and you no longer need the files you can type the command ``gbman clean`` or ``gbman cl`` and all your files that are inside the gbdi will be cleaned by the janitor, with this cleaning method the files can be recovered inside the /tmp/ folder of linux.
but if you want to permanently remove the files without needing linux to do it for you, should use ``gbman cleanforce`` or ``gbman clf`` and the files will be deleted directly without having to go through /tmp/
