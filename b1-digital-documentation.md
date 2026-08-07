# NATIONAL CLASSES, KANHAULI, VAISHALI
**CBSE Class X — Information Technology (Subject Code: 402)**  
**STUDY NOTES: UNIT 1 (DIGITAL DOCUMENTATION — ADVANCED) — VERSION 2**  

---

# Chapter 1: Digital Documentation (Advanced)

## 1.1 Apply Styles in the Document

A **Style** is a named collection of formatting characteristics (such as font face, size, color, alignment, margins, borders, and line spacing) that can be saved and applied as a single package to text, tables, frames, and other document elements. Styles speed up formatting, shift user focus from visual aesthetics to content creation, and enforce structural, uniform design across professional publications.

### Style Categories in LibreOffice Writer

LibreOffice Writer provides six primary categories of styles to format distinct document elements:

| Style Category | Scope & Elements Defined | CBSE Key Examples |
| :--- | :--- | :--- |
| **Page Style** | Defines basic layout structures of document pages, including page size, margins, header/footer locations, borders, backgrounds, and footnote boundaries. | Standard Portrait, Alternate Odd and Even Pages, Envelope, Title Page, Index Page layouts. |
| **Paragraph Style** | Formats paragraph layout, including tab stops, text alignment, line spacing, paragraph borders, margins, indents, and bullet hierarchies. | Heading 1 to Heading 10, Body Text, Title, Preformatted, List Indents. |
| **Character Style** | Applies text-formatting attributes to a block of letters, words, or character spans within a paragraph, without altering paragraph alignments. | Text color, size, highlighting, bold, italic, and underline modifications. |
| **Frame Style** | Controls layout of frames (containers holding text, images, or lists), including size, positioning, borders, and wrapping behavior of surrounding text. | Image Container, Graphics frame, Side Panel, Margin Note boxes. |
| **List Style** | Sets bullets, numbering, or custom outlines on a sequence of list paragraphs, including numerical prefix formats and indentation alignments. | Numbered lists (1, a, i), Bullet lists (circle, square, custom image). |
| **Table Style** | Controls the styling of data tables, including cell margins, border layouts, cell background fills, and interior text alignments. | Alternating Row, Colorful Grid, Clean Spec, clean academic grid fills. |

### Methods to Access and Apply Predefined Styles

Predefined styles in LibreOffice Writer can be accessed using four major interface options:
* **Menu Bar**: Select *Styles* option from the main menu bar at the top of the screen.
* **Styles Drop-down Box**: Use the Style drop-down list box present on the Formatting Toolbar.
* **Sidebar Menu**: Click the *Styles* button present on the right sidebar panel.
* **Keyboard Shortcut**: Press the **F11** function key to toggle the Styles and Formatting panel instantly.

#### Steps to Apply Styles on a Document
1. Select the text or element (character, paragraph, table, page, or frame) to be formatted.
2. Open the Styles panel (F11) and click the appropriate style category icon at the top of the panel.
3. A list of predefined styles under that category will appear. Double-click the desired style name to apply it.

### Fill Format Mode

The **Fill Format Mode** is used to apply a selected style to multiple scattered text blocks or elements inside a document in rapid succession, without having to select the text and double-click the style each time.

#### Steps to Apply Styles in Fill Format Mode
1. Open the document and display the Styles panel (F11). Choose the desired style category and select the specific style.
2. Click the **Fill Format Mode** button (represented by a paint bucket icon) at the top right of the Styles panel.
3. Move the mouse pointer (which changes to a paint bucket cursor) to the desired text block or element and click to apply the style.
4. Repeat the clicking action at all other scattered locations inside the document as needed.
5. To quit Fill Format Mode, click the **Fill Format** button again, or press the **Esc** (Escape) key on your keyboard.

### Advanced Style Management & Diagnostic Tools

To maintain complete professional control over layout design, LibreOffice Writer includes specialized diagnostic and layout settings:

* **Style Inspector**: 
  * **Definition**: A diagnostic sidebar panel used to inspect all the structural formatting characteristics applied to a selected text block.
  * **Utility**: It displays the hierarchical stack of formatting rules, displaying exactly which attributes are inherited from the Paragraph Style, which are overridden by a Character Style, and which are forced by manual Direct Formatting. This is crucial for finding and cleaning up manual formatting mistakes.
* **Spotlight Styles**:
  * **Definition**: A visual layout assistance feature available under the Styles sidebar panel.
  * **Utility**: Enabling Spotlight Styles color-codes text directly in the document editor workspace based on the style applied to it. This provides an immediate, high-contrast map of style distributions across the page, helping editors verify structural consistency at a glance.
* **Using the Direct Cursor**:
  * **Definition**: A formatting setting that allows the user to double-click on any empty space on a document page and begin typing immediately.
  * **Mechanism**: Once enabled, Writer automatically calculates the cursor's spatial coordinates and inserts the required empty paragraph lines, tabs, and spaces in the background to place the text precisely where the user double-clicked. This can be toggled on or off via *Edit ➔ Direct Cursor Mode* or under *Tools ➔ Options ➔ LibreOffice Writer ➔ Formatting Aids*.
* **Insert Mode vs. Overwrite Mode**:
  * **Insert Mode (Default)**: Typing new text pushes existing characters to the right of the cursor.
  * **Overwrite Mode**: Typing new text automatically replaces and overwrites existing characters to the right of the cursor, one by one. Toggle between these modes by pressing the **Insert (Ins)** key on the keyboard, or by clicking the active mode indicator on the Status Bar.

### Creating and Updating New Styles

LibreOffice Writer allows users to design custom styles using two primary mechanisms: *From Selection* and *Using Drag and Drop*.

#### Mechanism A: Creating a New Style 'From Selection'
1. Select a portion of the document, format it manually (set font, size, indents, color) exactly as desired.
2. Open the Styles panel (F11) and select the specific category icon (e.g., Paragraph Styles) under which the new style should belong.
3. Click the *Style Actions* drop-down button at the top right of the panel and select **New Style from Selection**.
4. In the *Create Style* dialog box, type a unique, descriptive name for the custom style.
5. Click **OK** to save and add the new style into the list of available styles.

#### Mechanism B: Creating a New Style 'Using Drag and Drop'
1. Select and format a text segment in the document as required.
2. Open the Styles panel (F11) and select the targeted style category icon.
3. Click and hold the left mouse button on the formatted text block, then drag the selection directly into the Styles panel list area.
4. In the *Create Style* dialog box that appears, type the name of the new style.
5. Click **OK** to register the custom style.
6. **CRITICAL WARNING:** Drag and Drop mechanism *cannot* be used to create Page Styles. Page Styles must be created manually.

#### Steps to Update a Style from a Selection
1. Select a text segment that already uses the style you wish to modify.
2. Apply manual formatting changes (such as changing the font size or indents) to this selected text.
3. Ensure the style name to be updated is selected in the Styles panel (F11).
4. Click the *Style Actions* drop-down button and select **Update Selected Style**. All text blocks using this style will update instantly.

### Loading Styles from Templates or Documents

You can import custom styles into your current document from an existing document or a preset template using the **Load Styles** feature:
1. Open your current document, click the *Style Actions* button in the Styles panel, and select **Load Styles**.
2. In the *Load Styles* dialog box, select the category of templates or click the **From File** button to locate an existing document.
3. Select the specific template or document from which styles are to be imported.
4. Check the boxes for the types of styles to be imported (Text, Frame, Pages, Numbering, Overwrite). Checking *Overwrite* replaces current styles of the same name with the imported ones.
5. Click **OK** to copy and merge the styles into your current workspace.

> **EXAM TIP:**  
> CBSE Board exams frequently ask about 'Page Style' capabilities vs 'Character Style' scopes. Page Style defines page boundaries (margins, headers), while Character Style works on individual words (text color, sizing). Drag-and-drop cannot create Page Styles.

---

## 1.2 Insert and Use Images in Document

Graphics, shapes, charts, and photographs enhance document clarity and make information highly presentable. LibreOffice Writer supports several mechanisms to insert and customize visual elements.

### Three Ways to Insert Images into Writer
* **From a File**: Select **Insert ➔ Image** from the main menu, navigate to the image file path on your computer, select the file, and click *Open*.
* **From the Gallery**: Click the **Gallery** icon on the sidebar. Choose a category, select the desired image, and drag and drop it into your document workspace.
* **From a Scanner**: Connect a scanner, select **Insert ➔ Media ➔ Scan ➔ Select Source**. Choose the scanner device, then click **Request** to capture and insert the scanned image directly.

### Modifying and Formatting Images

Once an image is inserted, the user can customize its visual scale and behavior using properties found in the *Image Toolbar*, the *Drawing Object Properties bar*, or by right-clicking the image and choosing *Properties*:
* **Cropping**: Removes unwanted outer areas of an image without changing its scale. Right-click the image, select **Properties ➔ Crop**. You can choose to:
  - *Keep Scale*: Changing the crop limits alters the physical dimensions of the image while preserving the scale of the interior subject.
  - *Keep Image Size*: Alters the scale of the interior subject to fit the locked, original frame boundaries of the graphic.
* **Resizing**: Click the image to display its eight blue sizing handles. Drag a corner handle to resize. **CRITICAL TIP:** To maintain the original **Aspect Ratio** (the proportional relationship of width and height) during resize, hold down the **Shift** key while dragging, or check the *Keep Ratio* box in the Image Properties dialog.
* **Rotating**: Allows spinning the image at any angle. Select the image, click the **Rotate** icon on the Image Toolbar. Sizing handles turn red. Click and drag any corner handle in a circular motion to rotate the image.
* **Image Mode**: Modifies the graphic color channel mapping on the fly:
  - *Default*: Displays the original graphic colors.
  - *Grayscale*: Converts colors into shades of gray.
  - *Black and White*: Converts all pixels into pure black or pure white.
  - *Watermark*: Significantly reduces contrast and increases brightness, allowing the image to sit quietly in the background without obscuring overlapping text.

### Text Wrapping Around Images

Text wrapping determines how the surrounding text flows and aligns in relation to the inserted graphic. Writer provides six primary wrapping behaviors:

| Wrap Mode | Text Flow & Alignment Behavior | Key Visual Characteristic |
| :--- | :--- | :--- |
| **Wrap Off / None** | The graphic is treated as an independent block. No text flows to its left or right. Text stops above the image and resumes directly below it. | Image occupies the full horizontal line segment. |
| **Page Wrap / Parallel** | Text flows on both the left and right sides of the image, provided there is enough margin space on either side. | Text is split and aligned around the graphic. |
| **Optimal Page Wrap** | Text flows only on the single side of the graphic that has the largest horizontal space. No text is placed on the narrower margin side if it is less than 2 cm. | Text flows only on the spacious side to prevent narrow, unreadable text columns. |
| **Wrap Through** | The image is layered on top of or behind the text. Text flows continuously directly across the image as if the image does not exist. | Text lines run directly over the graphic. |
| **Wrap Before** | Text flows only to the left of the image. The right side remains empty. | Graphic acts as a right-hand margin block. |
| **Wrap After** | Text flows only to the right of the image. The left side remains empty. | Graphic acts as a left-hand margin block. |

### Anchoring and Positioning Objects

**Anchoring** is the technical reference point that binds a graphic to a specific structural part of a document (like a page, paragraph, or character). This reference point dictates how the image moves dynamically when text is added or deleted.
* **To Page**: Binds the image to a fixed location on a specific page number. The image does not move even if text before it is deleted or expanded.
* **To Paragraph**: Binds the image to a specific paragraph. As the paragraph moves up or down due to text changes, the image moves with it.
* **To Character**: Binds the image to a specific character. It behaves like a paragraph anchor but retains precise spatial alignments next to characters.
* **As Character**: The image behaves exactly like an inline text character. It flows within the text line itself and alters line height to fit its size.
* **To Frame**: Binds the image directly to an surrounding frame layout container.

### Grouping Multiple Graphical Objects

**Grouping** allows users to combine multiple shapes, drawings, or images into a single unified object. Once grouped, editing actions (like resizing, moving, or copying) are applied to all interior shapes simultaneously, preserving their spatial relationships.

#### Steps to Group / Ungroup Objects
1. Click and hold the **Shift** key on the keyboard, then left-click each of the individual shapes or images to select them.
2. Right-click anywhere on the selected elements to open the context menu.
3. Select **Group ➔ Group** from the popup menu. Sizing handles will merge, indicating a single group.
4. To separate grouped elements, right-click the group and select **Group ➔ Ungroup** from the context menu. (Alternatively, use *Format ➔ Group ➔ Group* or *Format ➔ Group ➔ Ungroup*).

> **EXAM TIP:**  
> The difference between 'Keep Scale' and 'Keep Image Size' during cropping is a very high-yield board exam question. Make sure to memorize that 'Keep Scale' alters the image boundaries, while 'Keep Image Size' scales the picture to fit the original layout frame.

---

## 1.3 Create and Use Template

A **Template** is a pre-designed document layout containing predefined formatting styles, page structures, placeholders, headers, footers, and logos. Using templates speeds up document creation by eliminating the need to design layouts from scratch. In Writer, templates are saved with the unique file extension **.ott**.

### Template Management Operations

* **Creating a Template**:
  1. Open a blank document and design your layout (add logos, student tables, header text).
  2. Select **File ➔ Templates ➔ Save** from the main menu.
  3. Type a descriptive name in the *Template Name* box, select a template category, and click **Save**.
* **Using Predefined Templates**:
  1. Select **File ➔ New ➔ Templates** or use the keyboard shortcut **Ctrl + Shift + N** to open the Template Manager.
  2. In the *Templates* dialog box, browse categories, select the desired template, and click **Open**.
* **Checking Template Associations**: To find out which template is associated with a document, go to **File ➔ Properties**. The associated template name is displayed in the *General* tab. If the document was created from the default template, no template name will be listed.
* **Setting up a Custom Default Template**: If you want a custom layout to open automatically every time a new text document is created, open the Templates dialog (Ctrl+Shift+N), right-click your custom template, and select **Set as Default**.
* **Resetting to Factory Default**: To undo a custom default template, open the Templates dialog, click the *Settings* icon, hover over *Reset Default Template*, and select *Text Document*.
* **Importing Templates**: Open the Templates dialog, click the **Import** button at the bottom right. Choose the category, locate the downloaded template file on your system, and click **Open**.
* **Exporting Templates**: Open the Templates dialog, select the template to export, click the **Export** button, choose the destination directory on your computer, and click **OK**. This is highly useful for sharing layouts with multiple users.
* **Applying Template to Blank Document**:
  1. Open the template and copy its contents using **Ctrl+A** and **Ctrl+C**.
  2. Open a blank document and paste the content using **Ctrl+V**. Save the file as normal.

---

## 1.4 Create and Customize Table of Contents

A **Table of Contents (TOC)** is an indexed guide placed at the beginning of a document that lists headings, subheadings, and corresponding page numbers. Writer automatically extracts heading paragraph styles (Heading 1 to Heading 10) across the entire document to construct a unified TOC.

### Steps to Create a Table of Contents
1. Open the document and systematically apply standard paragraph heading styles (Heading 1, Heading 2, Heading 3, etc.) to all your section titles.
2. Place the cursor at the specific position where the Table of Contents is to be inserted.
3. From the main menu bar, select **Insert ➔ Table of Contents and Index ➔ Table of Contents, Index or Bibliography**.
4. In the *Type* tab, you can customize the main title of your TOC in the *Title Text Box* (the default name is 'Table of Contents').
5. Keep the **Protected against manual changes** checkbox selected. This protects the TOC from accidental manual editing on the page.
6. Click **OK** to insert the Table of Contents into your document.

### Customizing a Table of Contents (The Five Tabs)

To customize an existing TOC, right-click anywhere on the table of contents and select **Edit Index** from the popup menu. The dialog box displays five distinct customization tabs:
* **Type Tab**: Used to alter the main title of the TOC, change the index type, select if the index covers the entire document or just a section, and toggle manual write protection.
* **Entries Tab**: Used to structure the visual layout of individual TOC lines. You can configure and map elements for each heading level (1-10):
  - *E#*: Chapter Number.
  - *E*: Entry Text (Heading name).
  - *T*: Tab Stop (dots separating text from page numbers).
  - *#*: Page Number.
  - *LS*: Link Start (beginning of a hyperlink bind).
  - *LE*: Link End (closing point of a hyperlink bind). Mapping LS and LE creates hyperlinked headings.
* **Styles Tab**: Allows users to map custom paragraph formatting styles to different heading levels in the TOC.
* **Columns Tab**: Configures a multi-column layout for the Table of Contents instead of a single-column layout.
* **Background Tab**: Changes the background of the TOC. You can select the **Color** button to choose a flat solid color, or select **Bitmap** to apply a custom graphic background.

### Advanced TOC & Indexing: Concordance Files
* **Definition**: A **Concordance File** is an external data file (saved with the **`.sdi`** extension) used to automate the indexing of keywords in long documents. 
* **Mechanism**: Instead of manually selecting each word and tagging it as an index entry, the user lists the target keywords in the concordance file. When compiling an Alphabetical Index, Writer reads this file, automatically searches the entire document for those words, and maps them to their respective page numbers.

### Steps to Update / Delete the TOC Manually

**CRITICAL SYLLABUS POINT:** Table of Contents **does not update** automatically in LibreOffice Writer when headings or page numbers are edited. You must update it manually:
* **Updating the TOC**: Right-click anywhere in the Table of Contents and select **Update Index** from the context menu. All edits and page shifts will sync instantly.
* **Deleting the TOC**: Right-click anywhere in the TOC and select **Delete Index** from the context menu to remove it completely.

---

## 1.5 Track Changes and Document Review

The **Track Changes** feature is an advanced collaborative review tool that keeps a detailed record of all insertions, deletions, formatting changes, and comments made to a document by various reviewers.

### Key Track Changes Operations

* **Toggling Track Changes**: From the menu bar, select **Edit ➔ Track Changes ➔ Record** (or press **Ctrl + Shift + C**). Alternatively, display the toolbar using **View ➔ Toolbars ➔ Track Changes** and select the *Record* button.
* **Review Protection**: To ensure no reviewer can disable the record feature, select **Edit ➔ Track Changes ➔ Protect**, enter a secure password, and click OK. Now, tracking cannot be disabled without inputting the correct password.
* **Accepting / Rejecting Changes**:
  - *Individual*: Click on any tracked change in the document, then click the **Accept Tracked Change** or **Reject Tracked Change** button on the toolbar.
  - *Batch Manage*: Click **Manage Tracked Changes** on the toolbar to open a dialog containing a detailed list of all edits. You can review each edit and click *Accept*, *Reject*, *Accept All*, or *Reject All*.
* **Adding Comments**: To add a review note without altering text, click where you want the comment, and click **Insert Comment** on the toolbar (or press **Ctrl + Alt + C**). A colored review box appears in the right margin.
* **Deleting Comments**: Click the down-arrow icon at the bottom-right of the comment box. Select *Delete Comment*, *Delete All Comments by [Author]*, or *Delete All Comments*.
* **Comparing Documents**: If a reviewer returns an edited document where changes were not tracked, you can compare it with your original document:
  1. Open the edited document.
  2. Select **Edit ➔ Track Changes ➔ Compare Documents**.
  3. Browse and select your original document file.
  4. Writer will highlight all discrepancies in the *Manage Changes* dialog box. You can then systematically accept or reject each change.

---

## 1.6 Implement Mail Merge

**Mail Merge** is a powerful utility used to generate a mass batch of personalized documents (such as letters, circulars, certificates, invoices, or address labels) from a single master layout. It merges a static document with a structured list of recipient details, saving massive amounts of administrative time.

### The Three Core Components of Mail Merge

* **Main Document**: The primary text file containing the standard body text, formatting structure, graphics, and placeholders (called *Merge Fields*) where recipient-specific data will be inserted.
* **Data Source**: The structured database, spreadsheet, or text table containing the variable records (e.g., Name, Address, Contact Number) organized columns-wise under specific field headers.
* **Merged Document**: The final generated output consisting of multiple pages, where the main document is replicated and populated with each corresponding row of data from the data source.

### Steps to Perform Mail Merge (Using Mail Merge Wizard)

To execute Mail Merge systematically, launch the wizard by selecting **Tools ➔ Mail Merge Wizard** from the main menu bar. Follow these eight structural steps:
1. **Select Starting Document**: Choose whether to use the current document, create a new document, or load an existing file as your base layout.
2. **Select Document Type**: Choose between creating personalized **Letters** (output as printed documents) or **E-mail messages**.
3. **Insert Address Block**: Click *Select Address List* to select or create your data source. Map the fields (e.g., align 'First Name' in database to '<First Name>' in document placeholder) to match column headers.
4. **Create Salutation**: Configure custom salutations (such as 'Dear Mr. [Last Name],' or 'Dear Friend,').
5. **Adjust Layout**: Set the exact vertical position of the address block and salutation on the page.
6. **Edit Document**: Review the draft merged layout. You can click *Exclude recipient* to skip specific contacts or make temporary text adjustments.
7. **Personalize Document**: Search and edit individual pages if specific recipients require unique, customized notes.
8. **Save, Print or Send**: Finalize the operation:
  - *Save Starting Document*: Saves the master main document with merge fields.
  - *Save Merged Document*: Saves the merged pages as a single large file or as multiple separate files.
  - *Save, Print or Send Emails*: Outputs all personalized pages directly to a printer or sends them via email.

---
# NATIONAL CLASSES, KANHAULI, VAISHALI
