## About Me
Currently working as an analyst/trader in the securitized products space.

My finance folder is filled with random ideas and code I found/tinkered about math/finance for idea generation. I unfortunately cannot share any real world trading.

My Emacs setup is for the non-technical user (such as myself) to hopefully help someoene else who was searching the internet non-stop with questions that they had.

## Emacs Basic Setup
These changes should be dropped into the .emacs file.

You can add multiple languages for Org Mode using Org Babel. You can see below I have R and Python activated.
```sh
;; To active Babel languages
(org-babel-do-load-languages
 'org-babel-load-languages
 '((R . t)
   (python . t)))
```
Running code blocks usually wants you to confirm if you would like run it. This will bypass that message and run the block on command.
```sh
;; To get rid of the y/n confirm when running code blocks
(setq org-confirm-babel-evaluate nil)
```
This one was extremely helpful as changing the left to 450 has my Emacs open in the center of my computer screen rather than on the top left. The height and width are for your window size on startup.
```sh
;; setting default frame size on startup
(setq default-frame-alist '( (left . 450) (top . 0) (height . 40) (width . 100) ))
```
