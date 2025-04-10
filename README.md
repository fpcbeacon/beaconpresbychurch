# BeaconPresbyChurch.org

This is the source for the First Presbyterian Church of Beacon website.
To see the live site head over to [BeaconPresbyChurch.org](https://beaconpresbychurch.org).

## Editing a Page

Unfortunately, this site does not have a rich text editor so you'll have to make updates in plain text but with some special styling to cause the formatting.
This limits the output formatting but also helps keep a consistent look and feel.
See [Markdown Basics](#Markdown-Basics) below for tips.

For small updates, it's easiest to find the page, click on the small pencil icon on the top left, and make the update.
The page preview in GitHub should be good enough to see simple changes, but for anything beyond simple Markdown you'll have to view it on the actual site.

## Bigger Changes

For changes that are more than a quick change to a page (such as styling differences, whole new pages, etc), 
it's best to fork this GitHub repository to create your own sandbox to make changes.
Then you can create a pull request to make the changes live.

See [Forking](FORKING.md) for details how to make your own working copy of the site for edits.

## Markdown Basics

### Headings
Headings are created using hash symbols. The more hashes, the smaller the heading.
For example:

```markdown
# Top Level Heading

## Second Heading
```

### Formating

Text can also be formatted by wrapping it in symbols. 

**Bold text** can be indicated by using two asterisks `**like this**`.

_Italics_ can be indicated by using underscores `_like this_`.

Or _**the two together**_ `_**like so**_`.

### Links

Links are created by putting text in square brackets followed by the url in parenthesis.
For example to link to Google, you'd write `[Google](google.com)`.

When creating a link to another page in this site, just use the file name instead, such as `(Donate Now!)[donate.md]`.

### Line Wrapping

In markdown putting text on the next line does **not** make it wrap in the actual page.
Instead, it will just continue on the same line.

However, if you put an empy line between text, Markdown will treat it as a new paragraph.

If you need to make a line wrap without breaking to a new paragraph, you can use the &lt;br&gt; tag like the following, but that should be done sparingly:

```Markdown
First line<br>
Second line
```

### Images

First you'll have to upload any image to the [images folder](images). 
Then adding it to the page looks similar to a link but prefixed by an exclamation mark.
For example `![FPC Title](images/fpc_title.png)`. 
The text in the square brackets is what is used if the image can't load or for the visual impared.

### HTML

Markdown also support HTML tags (stuff inside of &lt; and &gt; characters).
We use that for more complicated code such as imbedding Canva posters.
If formatting can be done without HTML, that's preferable, but if not, go ahead and use HTML.

### More

There's a lot more to Markdown. See GitHub's [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) page for more.
