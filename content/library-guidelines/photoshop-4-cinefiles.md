+++
draft="false"

title = "Photoshop for CineFiles"
description=""

[menu.main]
parent="library"
identifier = "cinefiles photoshop"
weight = 2

+++

## TL;DR

* Rotate image to be upright and straighten with ruler and 'rotate arbitrary.'
* Crop image (not too tight, not too loose)
* Adjust levels (bring sliders into portion of image curve where there is data)
* Adjust brightness/contrast for legibility
* For above steps you may need to select/deselect images and text on a single page in order to modify them separately
* Clean up dust specks, torn edges, stains, staples, etc. (don't go overboard)
* Change the mode to 8-bit from 16-bit
* Save-as (replace the existing image if needed) and use LZW tiff compression.
* Mark your image as done

## Editing images in Photoshop for CineFiles

Now you should have a manageable batch of images in your IN PROGRESS folder. Somewhere between 5-10 should be good, or a booklet worth of images. It depends.

Open your batch of images in PS. There are lots of ways to do this. For example, you can select all the images in Finder and drag them to the PS icon in the dock. 

**Straighten your image** using the ruler tool. You can hit the keyboard shortcut "r" or find it in the tool menu bar. 

* It’s also helpful to ***_zoom in_*** during many of these editing procedures so you can see what you’re doing in greater detail.

**Crop your document** by drawing a marquee around the portion of the image you want to preserve.  You only need to leave only a small margin (¼") around the perimeter of the content.  If the indexer has made notations about the publication name, date and page numbers somewhere on the document, retain these notes.  Go to **Image > Crop** to cut away the excess border once you’ve drawn your marquee.  The selection marquee can be nudged using the keyboard arrows to make finer adjustments.

If you’re keeping the document in its original form, crop tightly around the outside edge.  Sometimes the text isn’t printed exactly parallel to the edge of the paper; when this is the case, it’s more important to level the text and allow the paper edges to be skewed.  You’ll crop around the outermost edges of the paper, even if it’s a bit crooked.  If you used a black cover paper during the scan, make sure to crop that out so you don’t have a black background behind your document.  (Using the Magic Wand selection tool is an efficient way to crop out your black background, taking care that you don’t also select parts of the document you mean to keep.)

Select the _photograph(s)_ in the document and adjust them for contrast and shadow details using Levels. If there are several photos on the same page, they can usually be adjusted at the same time by selecting them all. (To add to a selection or create more than one discrete selection, press Shift while drawing your marquee. To subtract from a selection, press Option while drawing the marquee.)  Go to **Image > Adjustments > Levels** to open the Levels dialog box. An in-depth explanation of how to use Levels follows this section.

Generally, you won’t need to make any color adjustments to your image, as the scanner is part of the color management system used by Photoshop and will produce fairly accurate color as viewed on your monitor.  One adjustment you might make occasionally is to the saturation, as the Epson scanner tends to bump up the saturation (intensity) of color scans a bit.  Go to **Image > Adjustments > Hue/Saturation** and move the Saturation slider 5-20 points to the left (negative numbers), until the day-glo look is toned down a notch. 

Use the **Gaussian Blur** filter to lessen the moiré patterns you may see as a result of halftone dots used when printing photographic images.  Go to **Filter > Blur > Gaussian Blur** and enter a number somewhere between 0.1 and 1.5.  The goal is to blur the halftone dots just enough to alleviate the moiré effect without unnecessarily blurring the image.  You can enter a low number to start and view the effect by selecting and deselecting the Preview box, and zooming in to see what’s happening at different viewing magnifications.  Click OK when satisfied with the result.	

Adjust the darkness and contrast of your _text_ with Levels.  At this point you still have your photograph selected, so the easiest way to select the text is to **invert your selection,** which will select everything *except* the photograph.  Go to **Select > Inverse**, open Levels and make your adjustments to optimize legibility.  If you’re working with a color scan, you should desaturate the text (remove any color cast) by using **Image > Adjustments > Desaturate**.  This also has the effect of decreasing the file size, which is especially desirable when working with large color files.  

Our aim in using Levels for both text and photographs is to maximize the viewing quality of the documents on the CineFiles web site; we can usually improve on the quality of a poor photocopy or faded newsprint with a Levels adjustment.  These adjustments are somewhat subjective, but the rule-of-thumb goals are **good contrast** **and** **legibility**.

**Clean up** the document by selecting and cutting any extraneous artifacts that interfere with legibility, e.g., shadowy background spots on a bad photocopy, newsprint bleed-through on a newspaper article, or little scraps of black lines left over from moving things around.  No need to get obsessive about this, just crop anything that makes it hard to read the text.

**Change the mode**of your document from 16-bits per channel to 8-bits per channel.  Go to **Image > Mode > 8 Bits/Channel**.  This is a very important step and easy to forget.  We scan in 16-bit mode for grayscale and color (16 bits per 3 color channels = 48-bit color) in order to capture the maximum amount of information during the scan.  This is desirable for editing, as you’ll maintain more of the original digital information.  However, the file size is too large to manage if we leave it in 16-bit mode, so the last thing to do before saving is to convert the image to 8-bit mode.

