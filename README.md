# Content Editor Overview

## Description

In this lesson you will learn how to structure and format content for the web in the WordPress Content Editor for pages and posts. The editor uses a WYSIWYG (What You See Is What You Get) toolbar that is similar to word processing software and text editing applications. You don't need to understand HTML code which is the standard for web content, as you can use the visual editor which creates and manages the underlying code for you. (Note that the WordPress editor does allow users to see and modify the actual HTML code for content, if desired.) You'll also be able to add links, add images and media, and insert symbols and special characters into web content.

## Objectives

At the end of this lesson, you will be able to:

*   Recognize the need to structure and format content for the web.
*   Choose toolbar and screen modes.
*   Identify toolbar features for formatting content.
*   Apply WYSIWYG formatting to content.
*   Add links to content.
*   Add content from other sources.
*   Insert symbols and special characters.

## Target Audience

Who is this lesson intended for? What interests/skills would they bring? Choose all that apply.

* [x] Users
* [ ] Designers
* [ ] Developers
* [ ] Speakers
* [ ] All

## Experience Level

How much experience would a participant need to get the most from this lesson?

* [x] Beginner
* [ ] Intermediate
* [ ] Advanced
* [ ] Any

## Type of Instruction

Which strategies will be used for this lesson plan? Choose all that apply.

* [x] Demonstration
* [ ] Discussion
* [x] Exercises
* [ ] Feedback
* [x] Lecture (Presentation)
* [ ] Show & Tell
* [ ] Tutorial

## Time Estimate (Duration)

60 minutes

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Ability to use a general text editor
*   Interest in creating and formatting web content
*   Basic familiarity with the [WordPress Dashboard](https://github.com/wptrainingteam/dashboard-overview)

## Readiness Questions

Have you used any WYSIWYG editors such as:

*   An email program with a text editor?
*   Microsoft Word?
*   Google Docs?

## Materials Needed

*   A way to display your computer to the group
*   A WordPress site that you can show
*	[Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) for sample content, if needed

## Notes for the Instructor

*   **No slides are available for this lesson as it is mostly demonstration.**
*		Students should import the [Theme Unit Test Data](https://wpcom-themes.svn.automattic.com/demo/theme-unit-test-data.xml) if they do not have sufficient content to work with.
*   Be prepared to explain the basics of structured text, distinguishing between block elements and inline elements, so that students do not get frustrated attempting to apply excessive manual formatting.
*   Be prepared to explain the difference between a paragraph break (press the return/enter key) and a line break (press shift key + return/enter key) for proper paragraph structuring.

## Have You Thought About...?

What could present challenges to delivering this lesson? Is there anything that can be done in advance to prepare for those challenges?

*  Participants could be in the Text editor instead of the Visual editor. Do you want to go over that too?
*  What if a participant doesn’t has a WordPress site to work with? Can they log into yours and work there?

## Lesson Overview

* Lecture on the need for proper formatting of web content
* Demonstrate each of the toolbar buttons by displaying the content editor and showing how each button is used
* Student exercises on formatting content using the buttons in the toolbar

## Exercises

**Add Headings to a Blog Post**

Using either [lorem ipsum text](http://meettheipsums.com/) or existing copy, have students:

1. Switch between Visual and Text modes.
1. Add a variety of headings within a blog post. (Remember that Heading 1 is for the title of the blog post, so students should use Headings 2-6 inside their posts.)
1. Apply bold and italic formatting to text.
1. Add a link to an external webpage.
1. Change the color of some text.
1. Make a paragraph a blockquote.
1. Add a special character to their text.
1. Right-align a paragraph.

## Assessment

**What is the name of the collection of buttons inside the content editor?**

1.  WYSIWYG
2.  The visual editor
3.  The toolbar
4.  The button bar

**Answer:** 3\. The toolbar

**Why is proper formatting of the content within a blog post important?**

1. It looks better and is easier to read
1. It's easier for search engines to understand the page
1. It makes the information more accessibility and mobile friendly
1. It helps organize the information
1. All of the above

**Answer:** 5\. All of the above

**Can a blockquote be applied to a sentence in a paragraph?**

1.  Yes
2.  No

**Answer:** 2\. No. It is a block element and applies to the entire paragraph.

**What does the toolbar toggle allow a user to do?**

1.  Add a break in the text
2.  Allow the user to move between Visual and Text editing modes
3.  Reveals/hides the 2nd row of buttons in the toolbar
4.  Move a block of text to the right

**Answer:** 3\. Reveals/hides the 2nd row of buttons in the toolbar

## Additional Resources

None.

## Example Lesson

### Creating Content for the Web

Creating content for the web is not the same as word processing or desktop publishing since there is a difference in how websites display content versus the printed page. A printed page has fixed dimensions and a fixed layout and the content will look the same on any printed version, including PDF format. Websites, on the other hand, can have different layouts on different devices.

In the early days of the web, the people who built the Web devoted a lot of effort into mimicking precise layouts that resembled printed pages, even though not all systems could be accommodated. Now with the proliferation of mobile devices, it's neither possible nor desirable to attempt mimic the printed page on the web. The more you try to manually control the layout of a web page in the editor, the more likely that is to fail on some devices. Mobile-friendly responsive web design uses fluid and flexible layout methods for optimal viewing and user experience to make it easy to navigate and read web content with a minimum of resizing, panning, and scrolling on most any device.

WordPress themes use a combination of Hypertext Markup Language (HTML) and Cascading Style Sheets (CSS) to display the layout content. So while you can master the structure and format of web content, the overall design of the website is controlled by the theme which handles much of the design for the content on the website.

### Using the Content Editor

The content editor is available when editing a Post or Page. In the backend administrative Dashboard, select Posts or Pages and then click on a title or hover or an item and click on "Edit." The content editor may be available for other content items, such as custom post types (e.g., Staff, Event, Portfolio), but that depends upon the theme, plugin, or developer customization.

When it comes to styling the text in the content, you select the text to style and then click the appropriate button on the toolbar to apply the style. Some text operations only work properly if there is a paragraph break **both above and below** the text being styled. These are called block elements and they include: paragraphs, headings, bulleted lists, numbered lists, horizontal lines, and blockquotes. (Otherwise it is known as an inline element.) Knowing how to work with block elements makes for a much more satisfying experience when using the editor. For example, for paragraph alignment your cursor simply needs to be somewhere in the paragraph that is to be aligned.

**The edits you make to your text only appear on your site after you click the "Update" button.** Also, the editor typically displays generic formatting, while the frontend of the website will apply the full, complete formatting based on the theme.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png) To check the appearance of changes without publishing them, click the "Preview Changes" button. This will open another browser tab to display what your page or post will look like on the site.

#### Toolbar

When you open a page or post to edit it, the basic WYSIWYG toolbar appears at the top of the editing panel. By default the editor only displays a single row of formatting buttons. You can use the Toolbar Toggle button, also called the _kitchen sink_, to make a second row of  toolbar buttons available.

![Toolbar Toggle button](/images/content-editor-toolbar-toggle-button.png)

With two rows of formatting buttons on the toolbar, you can toggle back to a single row by clicking the Toolbar Toggle button.

![Toolbar with both rows visible](/images/content-editor-toolbar-all.png)

### Screen Modes

The editor has four modes of viewing available.

![View modes](/images/content-editor-view-modes.png)

**Visual (1)**: The default view that shows a generic WYSIWYG version of the content.

**Text (2)**: HTML version of the content, if you need to manually adjust the HTML tags.

**Distraction-free (3)**: Hides the Dashboard menu and meta boxes, also called _Zen_ mode.

**Preview (4)**: Front-end version of the content that applies the full theme formatting for the website.

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-warning.png) Note that the HTML shown in the text mode view is limited and does not show how WordPress will apply HTML for the published content. Paragraph tags are automatically inserted where there are blank lines between content blocks, special characters may be converted to character entity codes, and other rules are applied including capturing and removing unnecessary or potentially malicious HTML code.

### Headings

![Headings dropdown list](/images/content-editor-headings-dropdown.png)

Heading tags are in a drop-down list and the first item in the toolbar. Heading tags are usually applied to short phrases or single words that organize content in an outline format that is more readable and appealing to users. Heading tags are also important for search engines, as they indicate a high-level outline of the overall content.

Heading 1 is a top-level tag in the outline of the content that is typically used for the Title of a page or post. It is a best practice to have only one Heading 1 tag on a webpage and therefore you should avoid using it within your content unless there is a specific reason to do so. Heading 2 is a second-level tag that can be used to denote sections of the content.Heading 3 is a third-level tag within a section that begins with a Heading 2 tag. And, this pattern continues all the way down to the lowest level with Heading 6.

### Text Styles

![Text Styles buttons for bold and italic](/images/content-editor-text-styles-buttons.png)

The first two buttons in the toolbar are basic styles for the copy in your post. You see these style options in many word processing programs and they can be used on individual words, entire sentences, complete paragraphs, or an entire document.

**Bold**: **Bolds text** (select the text and click the Bold button - or press cmd+b (Mac), ctl+b (PC) on your keyboard)

**Italic**: _Italicizes text_ (select the text and click the Italic button - or press cmd+i (Mac), ctl+i (PC) on your keyboard) You can also apply both _**bold and italic**_ styles to the same text by selecting the text and clicking both the Bold and Italic buttons.

### Text Formatting

![Text Formatting buttons](/images/content-editor-text-formatting-buttons.png)

The next three buttons on the toolbar offer formatting for block elements. Remember that most block elements start on a new line. Make a hard return by pressing the return or enter key before the sentence you want to format, or select an existing paragraph to demonstrate each one.

#### Bulleted (Un-ordered) List

Unorderd lists should be used for items that are in no particular order (where the sequence doesn't matter).

_Example:_
*   plugins
*   themes
*   pages

You can also remove the bullets from a list by selecting the entire list and click the bulleted list icon.

#### Numbered (Ordered) List

Ordered lists should be used for items that are in a particular order (where the sequence matters). They can also be useful for longer lists as it makes it easier to reference a specific item in the list.

_Example:_
1.  red
2.  green
3.  blue

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Nested lists are also possible, including mixed nested lists. place your cursor after the last character of the list item that will start the sub-list and press return on your keyboard.  Then click the Increase Indent button (in the bottom set of buttons on your toolbar) to start your sub-list.  Notice that the bullets in front of to the sub-list items look different. You can also make sub-lists below your sub-lists, but the bullets will start to all look the same.

_Example:_
*   plugins
	1. Akismet
	2. Hello Dolly
	3. Jetpack
*   themes
    *   twentythirteen
    *   twentyfourteeen
    *   kubrick
*   pages

#### Blockquote

Calls out a block of quoted text that is one or more paragraphs long. The styling of the blockquote can be controlled through custom CSS.

> This is a block quote. A hard return is needed above and below the text you'd like to convert to a blockquote. Select the text and click the blockquote button.

### Text Alignment

![Text Alignment buttons](/images/content-editor-text-alignment-buttons.png)

The next three buttons in the toolbar offer alignment formatting for block elements. Remember that most block elements start on a new line.  Select an existing paragraph to demonstrate each one.

#### Align Left

This text is left-aligned. Left-align will affect the entire paragraph. Since a paragraph is a block element, it needs to have a hard return both above and below it.

#### Align Center

<span style="text-align:center">This text is Center-aligned. Center-align will affect the entire paragraph. Since a paragraph is a block element, it needs to have a hard return both above and below it.

#### Align Right

<span style="text-align:right">This text is right-aligned. Right-align will affect the entire paragraph. Since a paragraph is a block element, it needs to have a hard return both above and below it.</span>

Place your cursor anywhere in a paragraph and click one of the align buttons to get the desired result. You can select multiple paragraphs and then click one paragraph align button to apply that alignment to all of the paragraphs selected.

### Linking to Content

![Insert Link button](/images/content-editor-insert-link-button.png)

When writing posts, you may want to create a link to outside content or other content on your site.

#### Insert/edit link

Select the word(s) that you'd like to link. Click the "Insert/edit link" icon and a pop up window will appear. There you'll be able to add a fully formed URL to a page that's not on your site or a link to a page within your website. You'll also be able to decide whether you want the link to open the page in a new browser tab or open the linked page within the same browser window. It is also possible to highlight the text you would like to link and paste the link directly over it to make an automatic link.

_Examples:_

[Opens the link in the same browser window](https://wordpress.org)

<a href="https://wordpress.org" target="_blank">Opens the link in a new browser window</a>

#### Remove link

Select the link that you would like to remove. Click the "Remove link" button in the toolbar and it will remove the link, but leave the text.

#### Insert Read More tag

![Read More link button](/images/content-editor-read-more-link-button.png)

The Read More tag allow the user to determine where they would like the text on their blog page to be cut off, when post excerpts are displayed on your home or post archive pages.  Place your cursor at the point where you'd like to direct users to read the rest of your post and click the "Insert Read More tag".

### Strikethrough

![Strikethrough button](/images/content-editor-strikethrough-button.png)

<del>Draws a strikethrough line over the text</del> (select the text and click the Strikethrough button -- or press shift+alt+d on your keyboard)

### Horizontal Line

![Horizontal Line button](/images/content-editor-horizontal-line-button.png)

To insert a horizontal line between sections of your page you can make a hard return and then click the 'Horizontal line' icon to add the line and then click another hard return after the line before the content of the next section resumes.

* * *

### Text Color

![Text Color button](/images/content-editor-text-color-button.png)

You can change the color of the text by clicking this button and choosing from the predefined pallete or by creating a custom color.

### Clear Formatting

![Clear Formatting button](/images/content-editor-clear-formatting-button.png)

You may need to remove formatting that you've added, and sometimes you may need to remove formatting when copying and pasting content from other sources.

### Paste as text

![Paste as Text button](/images/content-editor-paste-as-text-button.png)

When you paste text copied from other sources, you may bring in formatting with that text. WordPress can easily recognize bold, italic, paragraph alignment, and other rich text formats, and can convert that to the proper HTML code as you paste content into the editor. However, there are many situations when excessive formatting is retained causing problems in how your content is formatted in WordPress.

You can avoid copy-and-paste formatting problems by using the "Paste as text" button to toggle to plain text mode that strips out all formatting as you paste. The button is outlined with a box when activated, and when clicked again, it is toggled off with no outline.

You may have to reapply bold, italic, and other formatting, but it is best to use the WordPress editor and your theme to control all formatting.

### Special Character

![Special Character button](/images/content-editor-special-character-button.png)

![Special Characters grid](/images/content-editor-special-character-modal.png)

The Special Character button displays a popup window of symbols and other special characters that extend beyond what can be typed on a keyboard, such as a copyright symbol. Hover the mouse over an item in the grid to see a large display and label on the right side. Click on the item in the grid to insert into your content.

### Indents

![Decrease indent and Increase indent](/images/content-editor-indents-buttons.png)

You can offset block elements, such as paragraphs, with increasing amounts of indented margin on the left side. This will indent the entire block.

### Decrease Indent and Increase Indent

**Increase Indent**: Adds an increment of indenting to the left side

**Decrease Indent:** Removes an increment of indenting.

### Undo & Redo

![Undo and Redo buttons](/images/content-editor-undo-buttons.png)

WordPress retains the last action you performed, either typing or with the toolbar.

**Undo:** Undo the last action performed.

**Redo:** Redo the last action that was undone.

### Keyboard Shortcuts

![Keyboard Shortcuts button](/images/content-editor-keyboard-shortcuts-button.png)

You can use a combination of keys to do things that normally need a mouse, trackpad, or other input device. Rather than reaching for your mouse to click on the toolbar, you can use keyboard shortcuts, which are displayed in a popup window when you click the Keyboard Shortcuts button or press shift-alt-h.

Windows and Linux use "Ctrl + letter", Mac uses "Command (⌘) + letter".

#### Default shortcuts

**Ctrl/Command + key**

<table class="wikitable">

<tbody>

<tr>

<th>Letter</th>

<th>Action</th>

</tr>

<tr>

<td>c</td>

<td>Copy</td>

</tr>

<tr>

<td>v</td>

<td>Paste</td>

</tr>

<tr>

<td>a</td>

<td>Select all</td>

</tr>

<tr>

<td>x</td>

<td>Cut</td>

</tr>

<tr>

<td>z</td>

<td>Undo</td>

</tr>

<tr>

<td>y</td>

<td>Redo</td>

</tr>

<tr>

<td>b</td>

<td>Bold</td>

</tr>

<tr>

<td>i</td>

<td>Italic</td>

</tr>

<tr>

<td>u</td>

<td>Underline</td>

</tr>

<tr>

<td>k</td>

<td>Insert/edit link</td>

</tr>

</tbody>

</table>

#### Additional shortcuts

**Alt + Shift + key** The following shortcuts use a different key combination: Windows/Linux: "Alt + Shift (⇧) + letter". Mac: "Ctrl + Option (alt ⌥) + letter". (Macs running any WordPress version below 4.2 use "Alt + Shift (⇧) + letter").

<table>

<tbody>

<tr>

<th>Letter</th>

<th>Action</th>

</tr>

<tr>

<td>n</td>

<td>Check Spelling (This requires a plugin.)</td>

</tr>

<tr>

<td>l</td>

<td>Align Left</td>

</tr>

<tr>

<td>j</td>

<td>Justify Text</td>

</tr>

<tr>

<td>c</td>

<td>Align Center</td>

</tr>

<tr>

<td>d</td>

<td>Strikethrough</td>

</tr>

<tr>

<td>r</td>

<td>Align Right</td>

</tr>

<tr>

<td>u</td>

<td>• List</td>

</tr>

<tr>

<td>a</td>

<td>Insert link</td>

</tr>

<tr>

<td>o</td>

<td>1\. List</td>

</tr>

<tr>

<td>s</td>

<td>Remove link</td>

</tr>

<tr>

<td>q</td>

<td>Quote</td>

</tr>

<tr>

<td>m</td>

<td>Insert Image</td>

</tr>

<tr>

<td>w</td>

<td>Distraction Free Writing mode</td>

</tr>

<tr>

<td>t</td>

<td>Insert More Tag</td>

</tr>

<tr>

<td>p</td>

<td>Insert Page Break tag</td>

</tr>

<tr>

<td>h</td>

<td>Help</td>

</tr>

<tr>

<td>x</td>

<td>Add/remove code tag</td>

</tr>

<tr>

<td>1</td>

<td>Heading 1</td>

</tr>

<tr>

<td>2</td>

<td>Heading 2</td>

</tr>

<tr>

<td>3</td>

<td>Heading 3</td>

</tr>

<tr>

<td>4</td>

<td>Heading 4</td>

</tr>

<tr>

<td>5</td>

<td>Heading 5</td>

</tr>

<tr>

<td>6</td>

<td>Heading 6</td>

</tr>

<tr>

<td>9</td>

<td>Address</td>

</tr>

</tbody>

</table>

#### Formatting shortcuts

When starting a new paragraph with one of these formatting shortcuts followed by a space, the formatting will be applied automatically. Press Backspace or Escape to undo.

<table>

<tbody>

<tr>

<th>Letter</th>

<th>Action</th>

</tr>

<tr>

<td>*</td>

<td>Start an unordered list</td>

</tr>

<tr>

<td>-</td>

<td>Start an unordered list</td>

</tr>

<tr>

<td>1.</td>

<td>Start an ordered list</td>

</tr>

<tr>

<td>1)</td>

<td>Start an ordered list</td>

</tr>

</tbody>

</table>

The following formatting shortcuts are replaced when pressing Enter. Press Escape or the Undo button to undo.

<table>

<tbody>

<tr>

<th>Letter</th>

<th>Action</th>

</tr>

<tr>

<td>##</td>

<td>H2</td>

</tr>

<tr>

<td>###</td>

<td>H3</td>

</tr>

<tr>

<td>####</td>

<td>H4</td>

</tr>

<tr>

<td>#####</td>

<td>H5</td>

</tr>

<tr>

<td>######</td>

<td>H6</td>

</tr>

<tr>

<td>></td>

<td>transform text into blockquote</td>

</tr>

<tr>

<td>---</td>

<td>horizontal line</td>

</tr>

<tr>

<td>``..``</td>

<td>transform text into code block</td>

</tr>

</tbody>

</table>

#### Focus shortcuts

<table class="wp-help-single">

<tbody>

<tr>

<td><kbd>Alt + F8</kbd></td>

<td>Inline toolbar (when an image, link or preview is selected)</td>

</tr>

<tr>

<td><kbd>Alt + F9</kbd></td>

<td>Editor menu (when enabled)</td>

</tr>

<tr>

<td><kbd>Alt + F10</kbd></td>

<td>Editor toolbar</td>

</tr>

<tr>

<td><kbd>Alt + F11</kbd></td>

<td>Elements path</td>

</tr>

</tbody>

</table>

To move focus to other buttons use Tab or the arrow keys. To return focus to the editor press Escape or use one of the buttons.

### Lesson Wrap Up

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/lightbulb.png) Follow with exercises and assessment outlined above.
