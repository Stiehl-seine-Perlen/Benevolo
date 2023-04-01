# Application Design Standards

To ensure our applications graphical user interfaces are design properly we agreed on the following patterns and designs for frontend components.

## HTML elements
- Font❓
- Colors❓
- Spacing❓
- Borders❓
- Background❓
- XHTML❓

### Buttons `<button></button>`

### Lists

#### Unordered Lists `<ul></ul>`

#### Ordered Lists `<ol></ol>`

#### List Items `<li></li>`

#### Description List `<dl></dl>`

##### Term `<dt></dt>`

##### Description `<dd></dd>`

### Tables

#### Head `<thead></thead>`

#### Body `<tbody></tbody>`

#### Foot `<tfoot></tfoot>`

#### Row `<tr></tr>`

#### Data `<td></td>`

### Text

#### Paragraph `<p></p>`

#### Quotations
- `<blockquote></blockquote>` defines a section that is quoted from another source. Browsers usually indent `<blockquote>` elements.
- `<q></q>` defines a short quotation. Browsers normally insert quotation marks around the quotation.
- `<abbr></abbr>`tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM". Marking abbreviations can give useful information to browsers, translation systems and search-engines.
- `<address></address>` defines the contact information for the author/owner of a document or an article. The contact information can be an email address, URL, physical address, phone number, social media handle, etc. The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.
- `<cite></cite>` defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.). Note: A person's name is not the title of a work. The text in the `<cite>` element usually renders in italic.
- Bold text `<b></b>`
- Important text `<strong></strong>`
- Italic text `<i></i>`
- Emphasized text `<em></em>`
- Marked text `<mark>`
- Smaller text `<small></small>`
- Deleted text `<del></del>`
- Inserted text `<ins></ins>`
- Subscript text `<sub></sub>`
- Superscript text `<sup></sup>`
- `Link <a href="#"></a>` 

### Headers

#### Heading 1 `<h1></h1>`

#### Heading 2 `<h2></h2>`

#### Heading 3 `<h3></h3>`

#### Heading 4 `<h4></h4>`

#### Heading 5 `<h5></h5>`

#### Heading 6 `<h6></h6>`

### Images `<img src="img.svg" alt="some image"/>`
- `<img/>`
- `<map></map>`
- `<area shape="" coords="" alt=""/>`
- `<picture/>` gives web developers more flexibility in specifying image resources. The `<picture>` element contains one or more `<source>` elements, each referring to different images through the srcset attribute. This way the browser can choose the image that best fits the current view and/or device. Each `<source>` element has a media attribute that defines when the image is the most suitable.
```html
<picture>
  <source media="(min-width: 650px)" srcset="group.jpg">
  <source media="(min-width: 465px)" srcset="car.jpg">
  <img src="people.jpg">
</picture>
```

