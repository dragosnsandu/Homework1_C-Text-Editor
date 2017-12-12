# C Text Editor
<b>Homework #1</b><br>

The editor gets three files as parameters (date.in - containing the original text, operations.in - list all the operations that will be applied to the text, output.out - the file where the text will be written after the operations are applied over initial text).
<br>
To do this, all text is retrieved and pasted into a double-typed list, each element in the list being represented by one character in the initial text.
<br>
By using <i>preluare_operatii</i> function, the operatii.in file is analyzed and all the operations described in this file are extracted and executed. The undo and redo functionalities are provided by using two stacks; first store all operations that are different than <b>undo</b> and <b>redo</b> operations.
<br>
After all the desired changes have been made to the default text, the modified one is read one character by one and write in the <b>date.out</b> file, this being the content the user wanted to get.