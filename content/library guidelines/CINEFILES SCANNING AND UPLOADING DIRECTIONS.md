+++
draft="false"

title = "CineFiles Scanning and Uploading"
description=""

[menu.main]
parent="library"
identifier = "cinefiles scanning"
weight = 1

+++

CINEFILES SCANNING AND UPLOADING DIRECTIONS

## Before you start scanning

Make a folder for yourself where you will save all your work for the day. Name it according to this structure:**YYMMDDyourname** Example: 150729Maya

* Put the folder into the Cinefiles folder: CINEFILES>IMAGES IN PROCESS

## Get ready to scan!

Look in the drawer for documents that need to be scanned.	

* If you start to scan an entire folder of documents, be sure to keep them together, and keep scanned documents separate from unscanned ones. It helps to plan our scanning shift so that you complete a folder that you begin.

 On the back page of each document, you will find a document number and the total number of pages in the document: ex: 1p #56123; 24pp. #56124

* Take note of this number. You will use it to name your image files and to look up the corresponding document record in Collection Space.

Decide whether you will scan the document in Grayscale (black and white) or Color (color).

## Now, really get ready to scan

Open Epson Scan. It is in the dock and looks like a little scanner.

Take a look at the settings in the window that opens.  These are important! They should look like the picture below.

* Document Type: Reflective

* Document Source: Document Table

* Auto Exposure Type: Photo/Document depending on what you are scanning (not too critical)

* Image Type: 16-bit Grayscale or 48-bit Color

* Resolution: 300dpi

* *All the Adjustment boxes should be unckecked!*

![epson scan dialog](https://lh4.googleusercontent.com/OJC80MF7Shhl33_AEHEv9wutDh9YhrQR-Anuo8FE-QRuUebzvHFXdixppUpQjPRGSEcIuO_vwH1WagnHgPlAoETi4txcoBpveKCnAFvcc0yIcEmuVpPgvkni_6BX5bhCcmY7Nk8)

Put the first page of your document face down on the glass. Don’t smudge the nice clean glass! Put a piece of black construction paper behind your document. There are different sizes available on the table. Having a dark background prevents whatever is on the back of the document from showing up when you scan.

* If the document has more than one page, unstaple/unclip/etc. the pages. You will scan them one at a time. Don’t lose track of the order!

* If the document is larger than the scanning area, you can scan one section at a time and stitch the pieces in Photoshop. See the Special Cases section at the end of this document.

Hit the Preview button. You will see a preview of the entire scanning bed with your document hopefully included. Use the cursor to select the area that you want to scan. 

* You don’t need to line the document up precisely with the edge of the scanner, or select the document in the Preview window too precisely. You will correct crooked images and do all your cropping in Photoshop. 

Hit the Scan button. A dialog box will pop up asking you how you want to save your image and where you want it saved: 

![epson scan save dialog](https://lh4.googleusercontent.com/o6-tB1cVFjQXHnIjx34cQbZunM5Fvqm-M7RsENdqFR5tiHLAeymghBtLcwJ23gtcw57vsu6r0TmTW7AzIDBIMKkmBBtEA88gsfxE_v97JoTwGJdhF_t4HREmcENKD7qWflYA3Bc)

Tell Epson where you want your files to be saved. You only need to set this location at the beginning of your shift, but it is important to make sure you are not saving to the last person’s folder!

* Hit the Choose… button and navigate to the folder you created earlier. Good job.

Now you will create the file name for the image you are about to create. In the Prefix box, use the document number to make a filename like the one above using this format: **####.p#.300col(or gray).tif**

* This filename format is critical. Epson also remembers this setting, so make sure that you enter the right document and page numbers each time you scan a new document. 

* You don’t need to add .tif in the Prefix box. This is added automatically. 

* Reset the Start Number to 001 for each new document. You will delete this number later, but you can use it to keep track of images in progress.

Make sure Type is set to TIFF. You can leave all the other settings alone. 

Hit OK and the scanner will start to scan. 

Repeat for the other documents in your workflow.

## Edit images in Photoshop

Now you should have a manageable batch of images in your IN PROGRESS folder. Somewhere between 5-10 should be good, or a booklet worth of images. It depends.

Open your batch of images in PS. There are lots of ways to do this. For example, you can select all the images in Finder and drag them to the PS icon in the dock. 

**Straighten your image** using the ruler tool. You can hit the keyboard shortcut "r" or find it in the tool menu bar. 

* It’s also helpful to ***_zoom in_*** during many of these editing procedures so you can see what you’re doing in greater detail.

**Crop your document** by drawing a marquee around the portion of the image you want to preserve.  You need leave only a small margin (¼") around the perimeter of the content.  If the indexer has made notations about the publication name, date and page numbers somewhere on the document, retain these notes.  Go to **Image > Crop** to cut away the excess border once you’ve drawn your marquee.  The selection marquee can be nudged using the keyboard arrows to make finer adjustments.

If you’re keeping the document in its original form, crop tightly around the outside edge.  Sometimes the text isn’t printed exactly parallel to the edge of the paper; when this is the case, it’s more important to level the text and allow the paper edges to be skewed.  You’ll crop around the outermost edges of the paper, even if it’s a bit crooked.  If you used a black cover paper during the scan, make sure to crop that out so you don’t have a black background behind your document.  (Using the Magic Wand selection tool is an efficient way to crop out your black background, taking care that you don’t also select parts of the document you mean to keep.)

Select the _photograph(s)_ in the document and adjust them for contrast and shadow details using Levels. If there are several photos on the same page, they can usually be adjusted at the same time by selecting them all. (To add to a selection or create more than one discrete selection, press Shift while drawing your marquee. To subtract from a selection, press Option while drawing the marquee.)  Go to **Image > Adjustments > Levels** to open the Levels dialog box. An in-depth explanation of how to use Levels follows this section.

Generally, you won’t need to make any color adjustments to your image, as the scanner is part of the color management system used by Photoshop and will produce fairly accurate color as viewed on your monitor.  One adjustment you might make occasionally is to the saturation, as the Epson scanner tends to bump up the saturation (intensity) of color scans a bit.  Go to **Image > Adjustments > Hue/Saturation** and move the Saturation slider 5-20 points to the left (negative numbers), until the day-glo look is toned down a notch. 

Use the **Gaussian Blur** filter to lessen the moiré patterns you may see as a result of halftone dots used when printing photographic images.  Go to **Filter > Blur > Gaussian Blur** and enter a number somewhere between 0.1 and 1.5.  The goal is to blur the halftone dots just enough to alleviate the moiré effect without unnecessarily blurring the image.  You can enter a low number to start and view the effect by selecting and deselecting the Preview box, and zooming in to see what’s happening at different viewing magnifications.  Click OK when satisfied with the result.	

Adjust the darkness and contrast of your _text_ with Levels.  At this point you still have your photograph selected, so the easiest way to select the text is to **invert your selection,** which will select everything *except* the photograph.  Go to **Select > Inverse**, open Levels and make your adjustments to optimize legibility.  If you’re working with a color scan, you should desaturate the text (remove any color cast) by using **Image > Adjustments > Desaturate**.  This also has the effect of decreasing the file size, which is especially desirable when working with large color files.  

Our aim in using Levels for both text and photographs is to maximize the viewing quality of the documents on the CineFiles web site; we can usually improve on the quality of a poor photocopy or faded newsprint with a Levels adjustment.  These adjustments are somewhat subjective, but the rule-of-thumb goals are **good contrast** **and** **legibility**.

 

**Clean up** the document by selecting and cutting any extraneous artifacts that interfere with legibility, e.g., shadowy background spots on a bad photocopy, newsprint bleed-through on a newspaper article, or little scraps of black lines left over from moving things around.  No need to get obsessive about this, just crop anything that makes it hard to read the text.

**Change the mode**of your document from 16-bits per channel to 8-bits per channel.  Go to **Image > Mode > 8 Bits/Channel**.  This is a very important step and easy to forget.  We scan in 16-bit mode for grayscale and color (16 bits per 3 color channels = 48-bit color) in order to capture the maximum amount of information during the scan.  This is desirable for editing, as you’ll maintain more of the original digital information.  However, the file size is too large to manage if we leave it in 16-bit mode, so the last thing to do before saving is to convert the image to 8-bit mode.    

