# VIM-CheatSheet
This is a set of most used vim's commands and shortcuts ... 
>Vim is a highly configurable text editor built to make creating and changing any kind of text very efficient. It is included as "vi" with most UNIX systems and with Apple OS X.



## Open a text file inside a folder
1. Navigate to the folder using `cd`.
```
cd laragon/www/some_project/
```
2. then open any file using `vim` + the name of this file.
```
vim README.md
```


## Close the vim editor
*you probably won't be able to close the vim editor if it is your first time, we all have been there.*

1. click on `Esc` btn.
2. click on the colon `:`
3. write `:q!`

`:q!` => close without saving any changes.

`:wq` => close after saving all changes.


## Control the cursor
*to start controlling the cursor, you have to close the **INSERT** Mode or any other mode by  clicking on `ESC` Btn*.

*to start writing you have to start the **INSERT** Mode by clicking on `i` in your keyboard*.

**Click on `Esc` Btn** then navigate with:

`h`=> move the cursor to the **Left**

`j` => move the cursor **Down**

`k` => move the cursor **Up**

`l` => move the cursor to the **Right**

`0` => move the cursor to the **Start of the line**

`$` => move the cursor to the **End of the line**

`gg` => move to the **first line of the document**.

`H` => move the cursor to the **Top of screen**

`L` => move the cursor to the **Bottom of screen**

`{` => move to the **start of a block**.

`}` => move to the **end of a block**.

*Example :*
<br />
function foo() {
<br />
    alert('Hello World 1')
<br />
    cons:pencil2:ole.log(123)
<br />
    alert('I am amans199')
<br />
}

considering the pen as an cursor : 
<br />
***clicking on => will move the cursor to***

`h` => con:pencil2:sole.log(123)

`j` => ale:pencil2:rt('I am amans199')

`k` => ale:pencil2:rt('Hello World 1')

`l` => conso:pencil2:le.log(123)

`0` (ZERO) => :pencil2:console.log(123)

`$` => console.log(123):pencil2:

`gg` => :pencil2:function foo() {

`H` => :pencil2:function foo() {

`L` => }:pencil2:

`{` => :pencil2:function foo() {

`}` => }:pencil2:




### Hints for better usage:
* write a number before `k` or most of other shortcuts to implement it more than once.
*Example:*
1. Hit on `Esc` Btn.

2. write `20h` will move the cursor 20 letters to the left.

3. write `20k` will move the cursor 20 lines up.

4. write `5{` will move the cursor 5 blocks up.

and so on...

---
* you will see the difference between { and H , } and L if there is more than one block in the screen

---
* `H` and `L` have control only over the screen you see. not the whole document.

---


