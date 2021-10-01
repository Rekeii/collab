
# Introduction
An introduction to this spaghetti-style, absolutely scuffed hub of our brains combined. All done via [git](https://git-scm.com) and [ObsidianMD](https://obsidian.md/). 

Obsidian is a markdown note-taking system.

## File system explained:

- **00 Indexes** - filled with indexes that goes to note to note. 
- **01 Checklists**  - checklists.
- **02 Final Notes** - final or permanent notes (may or may not utilize), is not necessary. We can go full non-hierarchal note-taking.
- **03 Note Sequences** - halfway there to being permanent notes, may also be a sort of hub that leads to many quick notes.
- **04 Literary Notes** -  encoded reading materials.
- **05 Quick Notes** - dump for our notes. No hierarchy, completely fine if it's messy.
- **06 Reading Materials** - dump for reading materials such as pdfs, etc.
- **07 Media** - media dump folder.
- **08 Templates** - templates. (Enable Settings > Core Plugins > Templates , change template folder to 08 Templates)

## Contributing:
Wanna join us? Tell me and I'll add you as a contributer. Follow [this](https://github.com/gitobsidiantutorial/obsidian-git-tut-windows/blob/main/README.md), no need to make an empty repository, just clone mine. Create a new vault onto the cloned repository, turn off safe mode and install [ObsidianGit.](https://github.com/denolehov/obsidian-git)


## What do we use?
### Plugins:
#### Community Plugins
- [ObsidianGit](https://github.com/denolehov/obsidian-git)

#### Core Plugins
- Templates
![[Pasted image 20211001154351.png]]

### CSS Snippets:
- Centering all images:
```css
img {
  display: block;
  margin: 0px auto;
}
```
- [Bullet Point Relationship Lines](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/bullet-point-relationship-lines.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://github.com/deathau */
/* source: https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/2 */

.cm-hmd-list-indent .cm-tab,
ul ul {
  position: relative;
}
.cm-hmd-list-indent .cm-tab::before,
ul ul::before {
  content: "";
  border-left: 1px solid rgba(0, 122, 255, 0.25);
  position: absolute;
}
.cm-hmd-list-indent .cm-tab::before {
  left: 0;
  top: -5px;
  bottom: -4px;
}
ul ul::before {
  left: -11px;
  top: 0;
  bottom: 0;
}
```

- [Smaller Scrollbar](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/smaller-scrollbar.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://forum.obsidian.md/u/rsdimitrov */
/* source: https://forum.obsidian.md/t/optimize-obsidian-ui-for-a-more-seamless-experience/155/5 */

/* smaller scrollbar */
.CodeMirror-vscrollbar,
.CodeMirror-hscrollbar,
::-webkit-scrollbar {
  width: 3px;
}
```

- [Hyphenation and Justification](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/hyphenation-and-justification.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://forum.obsidian.md/u/boyd/summary */
/* source: https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/25 */

.cm-s-obsidian,
.markdown-preview-view {
  text-align: justify;
  hyphens: auto;
}
```

- [Stylish Block Quotes](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/stylish-blockquotes.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://forum.obsidian.md/u/Thery/summary */
/* source: https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/39 */

blockquote:before {
  font: 14px/20px italic Times, serif;
  content: "“";
  font-size: 3em;
  line-height: 0.1em;
  vertical-align: -0.4em;
}
blockquote p {
  display: inline;
}

/* Remove blockquote left margin */
blockquote {
  margin-inline-start: 0;
}
```

- [Larger Link Preview](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/bigger-link-popup-preview.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://github.com/cannibalox & https://github.com/konhi */
/* source: https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/82 */

.popover.hover-popover {
  transform: scale(0.8); /* makes the content smaller */
  max-height: 800px; /* was 300 */
  min-height: 100px;
  width: 500px; /* was 400 */
}

.popover.hover-popover .markdown-embed {
  height: 800px;
}
```

- [Custom Icons for Files and Folders](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/custom-icons-differing-files-and-folders.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://github.com/deathau */
/* source: https://discord.com/channels/686053708261228577/702656734631821413/755293685046050896 */

/* Emoji */
/*.nav-file-title-content::before { content: '🗒 '; }
.nav-folder-title-content::before { content: '📂 '; }*/

/* Flat font */
/* Requires: https://icomoon.io/#icons-icomoon/liga-font */
.nav-folder-children .nav-file-title-content:first-child::before {
  content: "\e924  ";
  font-family: "IcoMoon-Free";
}
.nav-folder-children .nav-folder-title-content::before {
  content: "\e930  ";
  font-family: "IcoMoon-Free";
}
```

- [Outliner for the Outline and File Explorer](https://github.com/kmaasrud/awesome-obsidian/blob/master/code/css-snippets/outliner-for-the-outline-and-file-explorer.css)
```css
/* get more snippets at https://github.com/kmaasrud/awesome-obsidian */
/* author: https://forum.obsidian.md/u/Shamama & https://forum.obsidian.md/u/wonton/summary & https://github.com/konhi */
/* source: https://forum.obsidian.md/t/meta-post-common-css-hacks/1978/112 */

.outline .tree-item-children {
  margin-left: 20px;
  border-left: 1px solid var(--background-modifier-border);
  border-radius: 4px;
  transition: all 0.5s ease-in-out;
}
.outline .tree-item-children:hover {
  margin:0 !important;
  border-left-color: var(--background-modifier-border);
}
.nav-folder-children .nav-folder-children {
  margin-left: 20px;
  padding-left: 0;
  border-left: 1px solid var(--background-modifier-border);
  border-radius: 4px;
  transition: all 0.5s ease-in-out;
}
.nav-folder-children .nav-folder-children:hover {
  margin:0 !important;
  border-left-color: var(--background-modifier-border);
}

```

## License
[MIT](https://choosealicense.com/licenses/mit/)
