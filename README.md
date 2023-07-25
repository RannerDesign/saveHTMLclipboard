
saveHTMLclipboard
=============

*Save HTML content of the clipboard into a text file*



Windows systems are supporting many formats for storing data in the clipboard. Typically if you paste content within an application, the application selects the appropriate format from the clipboard.

But sometimes it is necessary to capture content in a format not supported by the application. In this case only plain text is delivered.

Typical example: select and copy HTML format in a browser and want to paste it into notepad++ or similar programs.

**saveHTMLclipboard** is a small stand-alone application to support copying HTML content from the clipboard into a text file. It can be run locally without server, only HTML, CSS and JavaScript is needed.

Technically **saveHTMLclipboard** works with a `contenteditable` div-Element into which you can paste the HTML clipboard content. This content can then be saved as text file locally.

## Installation
* An installation is not needed
* Copy the `.html` file to any folder

## Technical Prerequisites
* Actual browser
* no further software is required

## Usage
Open `saveHTMLclipboard.html` in any browser. Paste HTML content from clipboard into the indicated area. The content now should be visible. It is furthermore possible to edit the content. The **Save button** opens the usual download-file-save-as dialogue.

As clearing the div-Element manually sometimes does not work completely, use the **Clear button** to remove any content.

