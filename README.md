<h1 align="center">Notepad</h1>

<p align="center">
  <img 
    src="https://user-images.githubusercontent.com/78868769/162090045-dadf0cd5-5069-4b38-b315-f0c3da18c6b9.png"
  >
</p>

## Introduction
<p align="left">
Hi everyone I created this notepad application using Qt (C++ framework for GUI). 
Qt has an amazing UI which lets the user build valuable project easily , 
its widgets are very helpful assets.
</p>

## Tools
* Qt Creator
* Qt Designer
* CSS Style Sheet

## Fratures

* Create new notepad file
* Open previous file
* Print current file
* Copy text 
* Cut text
* Paste text
* Undo
* Redo

## Logic Used

    void on_actionNew_triggered();
    
    void on_actionOpen_triggered();
    
    void on_actionSave_triggered();
    
    void on_actionPrint_triggered();
    
    void on_actionExit_triggered();
    
    void on_actionCopy_triggered();
    
    void on_actionPaste_triggered();
    
    void on_actionCut_triggered();
    
    void on_actionUndo_triggered();
    
    void on_actionRedo_triggered();

> * on_actionNew_triggered() function - Creates a new file . 
> * on_actionOpen_triggered() function - Open an existing file/document. 
> * on_actionSave_triggered() function - Saves  the current file that you are working on . 
> * void on_actionPrint_triggered() function - Prints the document . 
> * void on_actionExit_triggered() function - Exits the recent file .
> * void on_actionCopy_triggered() function - Copies the text that has been selected . 
> * void on_actionPaste_triggered() function - Pastes the text . 
> * void on_actionCut_triggered() function - Cut the text that has been selected . 
> * void on_actionUndo_triggered() function - Undo the recently done task. 
> * void on_actionRedo_triggered() function - Restores the actions that were undone . 
