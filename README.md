AuthorInfo
==========
This is a mirror of http://www.vim.org/scripts/script.php?script_id=2902

You can add your author info in any source files,such as cpp,c,java,and c#,python,php,bash....
Like this:
-------------------------------------------------
  Author:          example - http://www.example.cn
  Email:           example@gmail.com
  FileName:        
  Description:     
  Version:         0.0.1
  LastChange:      2011-02-15 19:32:25
  History:         
--------------------------------------------------
when you type <F4>,this will add in the head of your source file,and when you type <F4> again,It will update automatically.

Usage
---------
* you need install The NERD Commenter first.
  url is : http://www.vim.org/scripts/script.php?script_id=1218

* you need some config in vimrc:
  let g:vimrc_author='example'
  let g:vimrc_email='example@gmail.com'
  let g:vimrc_homepage='http://www.example.cn'

* nmap <F4> :AuthorInfoDetect<cr>

