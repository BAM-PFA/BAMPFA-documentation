+++
draft="false"

title = "How to use Adobe Bridge"
description = ""

[menu.main]
parent="imaging"
identifier = "bridge"
weight = 5

+++

**Using Adobe Bridge (to batch rename & edit metadata)**

Adobe Bridge can be used to do many complex processes in managing photos, but it is easy enough to use it for some simple, handy tasks. For our purposes at BAMPFA, Bridge is best for renaming photos ([to follow our naming conventions](https://berkeley.app.box.com/files/0/f/11507803981/1/f_103350620609)) and for adding basic metadata to images.


**tl;dr**<br/>
here's the video:<br/>
<iframe width="560" height="315" src="https://www.youtube.com/embed/0LCzah5E9QM" frameborder="0" allowfullscreen></iframe>


**Basic Usage**

Bridge is laid out similarly to the Mac OS Finder window. When you open the program, typically you start out in the last place you visited in Bridge. In this example, we are in a folder called "neil jenney 1981" and you can see the contents listed along with a thumbnail of each item. To navigate to different folders, double click on them. You can click on a single item, or a group of items, in order to see info about your selection or perform some action on it. Your selection will be highlighted by a yellow box:

![image alt text](images/general-imaging/bridge/general-overview.png)

**TIP! **

To select a range of images, click on the first one, hold down shift, then click on the last one. To select images that are not contiguous, select one, the to select any others, hold down COMMAND (⌘) and click away.

![image alt text](images/general-imaging/bridge/general-multi-select.png)

**Batch Renaming Images**

This is probably the most useful thing Bridge can do for us. Let’s say we have 100 film stills for "Some Film" by “A. Director” and we get the images named something helpful like “1.jpg” “image34.tif” etc. Bridge makes it really simple to name them correctly: Director_Some-Film_001.jpg, and so on. 

First, you will make life simpler by putting all the images you want to change into one folder. Once you have them in one folder, select them all by hitting "COMMAND" plus “A” :

 

Then from the top menu bar, select Tools > Batch Rename...

 ![image alt text](images/general-imaging/bridge/batch-rename.png?height=250px)

The window that opens will let us build new filenames in many exciting ways. You can add and remove steps in making filenames with the + and - buttons. In our example, select *Text* for the first row, then *Sequence Number* for the second. NOTE THE UNDERSCORES!

![image alt text](images/general-imaging/bridge/filename-levels.png?height=250px)


You can the select the number of digits for your sequence number, and the number at which you want to start (it doesn’t have to be 1). The default number of digits is three, which is what we use anyway. You can also see a preview of what the filenames will look like at the bottom of the window:

![image alt text](images/general-imaging/bridge/filename-sequence-num.png?height=300px)

Hit the RENAME button and you are done! 

![image alt text](images/general-imaging/bridge/general-select.png?height=250px)

As a bonus example, let’s consider that instead of "A. Director" we learn that “Some Film” was directed by Jane Doolittle. Oops! Bridge also makes it easy to replace parts of a filename. Remove any extra steps with the minus button and in the first row, select “String substitution” instead of “Text.”

![image alt text](images/general-imaging/bridge/filename-string-substitution.png?height=250px)

In the boxes that appear you want to "Find" Director and “Replace” it with Doolittle:

 ![image alt text](images/general-imaging/bridge/filename-string-sub-part2.png?height=250px)

Voilà!

![image alt text](images/general-imaging/bridge/general-select-all.png?height=250px)

**Editing Metadata with Bridge**

You can also edit some image metadata in Bridge. Unfortunately, you can’t (yet?) use Bridge to edit the metadata that we need for Piction, but you can do things like add copyright notices, photo credits, descriptions, keywords, etc. To edit one image, just select one, and to edit multiple images, select a group/range. Note that if you select a group you will apply the metadata to ALL the images, so beware. Maybe not all the photos were shot by the same person? Use your best judgment.

Metadata fields are viewed and edited in the right-hand pane: 

![image alt text](images/general-imaging/bridge/metadata-1.png)


If you have selected multiple images, you will see "*Multiple values*" for fields where images have more than one value (like filename, file size, etc.).

![image alt text](images/general-imaging/bridge/metadata-2.png)


Also, each of the menus (collapsed at right) has a different set of fields. The IPTC ones are usually the most useful.

To edit a field, click into it and enter the value you want:

When you navigate away from the image(s) that you were editing you will get a pop-up asking if you want to apply the changes:

![image alt text](images/general-imaging/bridge/apply-changes.png?height=250px)

You could also click on the tiny, nearly invisible check mark at the bottom right corner of the program window:


![image alt text](images/general-imaging/bridge/metadata-check.png)


That’s it. If you have questions, please ask Michael for help or more instructions!

