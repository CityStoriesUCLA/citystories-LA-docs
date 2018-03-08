---
title: "Module 8: Filling in the article data and content"
permalink: /docs/mod8/
---

Now that you have created your article Markdown file and uploaded some images, you are ready to begin filling in some of your article info. In addition to completing the frontmatter, you'll need to add and properly format your article text, images, and a bibliography. The following sections will show you how. 

#### Adding new content to your article
Whenever you want to add new content or edit your existing content, you'll need to use the **Edit** mode.
* Navigate to the `.md` file for your article in the `_posts` directory.
* Click on the `.md` file to open it. - *Make sure you are opening and editing your group's article!*
* Click on the **pencil icon** in the top right of the file.
* Once you are in **Edit** mode, you can switch from "No wrap" to "**Soft wrap**" in the pull-down menu in the top right corner of the file area. This will wrap the text so you can see all your content in the window.
* Make any changes / additions to your `.md` file.
* When you are ready, scroll down to bottom of the page, make sure "**Commit directly to the `master` branch**" option is selected, then click on the "**Commit changes**" button.

#### Filling in the template
We are going to fill in some of your content here in class to get you started.

##### The Front matter
The first section is the front matter where we will put the metadata for our articles. (What's metadata?)
* `layout: post`-- Leave this as-is! 
* `title:` This is where you will put the title of your article. It's best if you enclose it in quotation marks. `title: "My article title"` 
    * Also, make sure your title isn't the same as an article title from a previous class.
* `date:` Enter the date in machine-readable format (YYYY-MM-DD), for example `date: 2018-03-12`
* `categories:` List your category here, all lower-case, enclosed in quotes, inside square brackets, ex. `categories: ["politics and society"]`
* `author:` List the names of the authors here, separated by commas. Enclose the whole thing in quotes: `author: "Dawn, Niqui, Andy"`
    * You can use for full name, first name and last initial or first initial and lastname, or you can use "Anonymous."
* `lat:` and `lng:` This is where we'll put our geo-coordinates. We'll get to this in a bit.
* `collectiontitle:` Put the name of the collection that your object(s) are from here. Use the format recommended by the Curator. Enlcose the whole statement in quotes.
* `quarter:` List the current academic quarter here. Example: `quarter: Winter 2018`
* `desc:` This is for a short description of the place. It will display on the map popup. Limit this to **no more than 320 characters**.

<script src="https://gist.github.com/kirschbombe/48024b54c2ae787093dabdeae7a986aa.js"></script>

_Now, let's save our changes and check out the live page again to see the info we just added._ Remember, you may need to clear your browser's cache or try opening in a new browser to see your changes.

##### The Map Marker
To connect your article to a place on the map, you'll need to gather a few bits of information (all this information will go in the frontmatter):

**Brief description for your place marker - this goes in the `desc: ` field in the frontmatter**
* Each article has a corresponding place marker, or pop-up, on the map. This displays the **place name** and a **brief description**.
    * Work with your instructor to determine a location in Los Angeles for your map marker - and provide a name.
    * Write a short summary, quote, or description that reflects the importance of the place to the item(s) about which you are writing. You can change this later as your annotation develops, but go ahead and put in a short summary now. Limit to 320 characters or less!

**The geographic coordinates**
* We'll need geographic coordinates to pin the marker to the map. You can look up geographic coordinates for your location here: [http://gps-coordinates.org/](http://gps-coordinates.org/)
* Add the coordinates to the frontmatter in the corresponding `lat: ` and `long: ` fields

Scroll down and saver your work :)

##### The article Body
The text of your article begins after the three dashes at the end of the front matter `---`. Just add your text, keeping in mind these Markdown formatting rules:

* New paragraphs require a full line in-between the two paragraphs.
* You can use styles such as **bold** `**bold**` and _italics_ `_italics_`.
* You can create sub-headings in your article using hashtags (#). Four hashtags `####` create a level 4 heading, which is what we recommend for sub-headings in your article. You'll need a space between the last (#) and the first letter of the heading text: `#### My sub-heading`. 
* Add links to your article: `[Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)` will result in [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

See the cheatsheet linked above for more Markdown tips. Don't get crazy though; we want to keep it simple and clean :)

##### Images

_This step requires the information you gathered earlier in the Image Worksheet._

Now that you've uploaded your images to the repository, you can add them to your article. Feel free to add your images below the article text, or distribute them throughout the text. 

Each image has two parts: the **image link with alt-text** AND the **caption**. A complete image is formatted like this:

<script src="https://gist.github.com/kirschbombe/824930bbe036dec9b40ff08943cb9500.js"></script>

The first part contains the Alt-Text followed and the image path:
* Alt-Text is surrounded by square brackets `[]`
* The image path will be `images/[filename].jpg` - inserting the name of the image file in place of `[filename]`
* Notice there is no space between the Alt-Text and the image path segments
* On the next line, add the tag `{:.image}` - this is important! This makes the Lightbox feature work.

The second part contains the title and attribution statemtment:
* List the title first, followed by a period `.`
* Follow this with the attribution statement.
    * The attribution statement should contain the creator and date, if known, followed by a statement like "Image courtesy of UCLA Library Special Collections." If you visited a library unit other than the UCLA Library Special Collections (for example, the Chicano Studies Research Center), use their name in place of "UCLA Library Special Collections."
* On the next line, ad the `{:.caption}` tag - this is import to format the caption properly!

Repeat for each image, then scroll down and save your work :)

##### Bibliography
* Next, we'll add the citation(s) for the archival objects we will be writing about. You should already have this information in your Image Worksheet from your archives and special collections visit.
* Using MLA format, add your first citation as a numbered item (1.) just under the `{:.bibliography}` tag (no extra lines!).
* Once you have more items for your bibliography, enter each item as a numbered list item. Be sure to put your citations in alphabetical order by author or, if no author, by title.

<script src="https://gist.github.com/kirschbombe/04a7066dd196e91cbda66e9f26888881.js"></script>

_Now, let's save our changes again and check out the live page again to see the info we just added._ Remember, you may need to [clear your browser's cache](../cache) or try opening in a new browser to see your changes.
