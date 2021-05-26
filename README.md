# PhpStorm autocompletion for Bolt

Configuring Contenttypes, Taxonomies, Fields, Relationships and Menus ( mentioned as definitions in 
the document ) is something you will do quite often when building sites using Bolt. With these 
Phpstorm Live Templates you can reduce the effort and time you spend configuring these Bolt definitions.

![](http://g.recordit.co/6E7dQh0os8.gif)

## How to install
1) Download the `settings.zip` from this repository
2) Open up PhpStorm
3) In the top menu go to `File > Import Settings`
4) Select the downloaded `settings.zip` file or directory where the file is located.

## How to use 
The autocompletion can be triggered by typing in the letter `b` in a `.yaml` file.

For a more specific autocompletion, for instance Bolt Fields, type in `bf` (`b` refers to Bolt and `f` 
refers to Fields). A list of suggestions with the different types of Fields will be displayed.

The list of suggestions can be navigated using the up/down keyboard arrows.

To select a suggestion from the list you can directly double click on it or press `Enter` or `Tab` to
select the suggestion that is focused.

Use the `Tab` key to move the focus into the next line through the structure options. 

**💡Tips**: Tab through the structure filling in the inline options first. For Contenttypes skip `fields`
and `relations` and add them in a second step. 

### Autocompletion variants
Aulthough not for all the definitions, there exist 2 variants:
* **Basic**: It adds the definition with the basic options 
* **Full:**: It adds the definition with all the possible options

### Contenttypes
List of Contenttypes autocomplete suggestions is triggered by typing in `bc`.

Autocomplete suggestions:
* `bc-basic`: Inserts the structure of a Contenttype with the basic options.
* `bc-full`: Inserts the structure of a Contenttype with all possible options.
 
### Taxonomies
List of Taxonomies autocomplete suggestions is triggered by typing in `bt`.

Autocomplete suggestions:
* `bt-categories`: Inserts the structure of a Taxonomy definition that behaves like **categories**.
* `bt-grouping`: Inserts the structure of a Taxonomy definition that behaves like **grouping**.
* `bt-tags`: Inserts the structure of a Taxonomy definition that behaves like **tags**.
* `bt-common-options`: Inserts all the general options applicable to Taxonomies. 

### Relationships
List of Relationships autocomplete suggestions is triggered by typing in `br`.

Autocomplete suggestions:
* `br-basic`: Inserts the structure of a Relationship definition with the basic options.

### Fields
List of Fields autocomplete suggestions is triggered by typing in `bf`.

Autocomplete suggestions:
* `bf-article-basic`: Inserts the structure of an **Article** Field with the basic options.
* `bf-checkbox-basic`: Inserts the structure of a **Checkbox** Field with the basic options.
* `bf-collection-basic`: Inserts the structure of a **Collection** Field with the basic options.
* `bf-data-basic`: Inserts the structure of a **Data** Field with the basic options.
* `bf-date-basic`: Inserts the structure of a **Date** Field with the basic options.
* `bf-email-basic`: Inserts the structure of a **Checkbox** Field with the basic options.
* `bf-embed-basic`: Inserts the structure of a **Embed** Field with the basic options.
* `bf-file-basic`: Inserts the structure of a **File** Field with the basic options.
* `bf-filelist-basic`: Inserts the structure of a **Filelist** Field with the basic options.
* `bf-hidden-basic`: Inserts the structure of a **Hidden** Field with the basic options.
* `bf-html-basic`: Inserts the structure of a **HTML** Field with the basic options.
* `bf-image-basic`: Inserts the structure of a **Image** Field with the basic options.
* `bf-imagelist-basic`: Inserts the structure of a **Imagelist** Field with the basic options.
* `bf-markdown-basic`: Inserts the structure of a **Markdown** Field with the basic options.
* `bf-number-basic`: Inserts the structure of a **Number** Field with the basic options.
* `bf-redactor-basic`: Inserts the structure of a **Redactor** Field with the basic options.
* `bf-select-basic`: Inserts the structure of a **Select** Field with the basic options.
* `bf-set-basic`: Inserts the structure of a **Set** Field with the basic options.
* `bf-slug-basic`: Inserts the structure of a **Slug** Field with the basic options.
* `bf-templateselect-basic`: Inserts the structure of a **Templateselect** Field with the basic options.
* `bf-text-basic`: Inserts the structure of a **Text** Field with the basic options.
* `bf-textarea-basic`: Inserts the structure of a **Textarea** Field with the basic options.

### Menus
List of Menus autocomplete suggestions is triggered by typing in `bm`.

* `bm-basic`: Inserts the main structure of the menu.
* `bm-item-basic`: Inserts the structure of a menu link (link/label).
* `bm-submenu-item-basic`: Inserts the structure of a submenu item. 