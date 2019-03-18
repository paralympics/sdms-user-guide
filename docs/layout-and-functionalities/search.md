# Search Forms & Results Matrix

Each section handling one particular data entity of SDMS, e.g. sports, events, organizations or athletes, has a search functionality to target the user’s data.

The search page in turns offers a results matrix with an input row for the search criteria. When a new section is opened, the current criteria are automatically applied, along with the user’s permission criteria (for example, an NPC user for Germany will only receive search results about German athletes), and the results are displayed. Generally, the search returns all relevant results when initially opened, and the current criteria can then be modified. When changing the drop-down boxes, the search is automatically reset, while when changing text boxes, users must refresh or press the **Enter** (return) key on their keyboard.

<!-- TODO: search image -->
<figure>
    <img class="screenshot" src="src" alt="alt">
    <figcaption>Figure 2.6: Search Results Matrix</figcaption>
</figure>

Users specify their search parameters by entering text or selecting items from the dropdown search fields. Each search field only allows for entries with fewer or the same number of characters defined in the database structure.

<!-- TODO: reset button -->

The reset button <img src="src" alt="alt"> resets the search to its initial parameters. If you need to clear the grid of all parameters, use the clear grid button in the bottom row.

Users specify their search parameter by entering text or select items from the dropdown search fields. Each search field only allows for entries with fewer or the same number of characters defined in the database structure.

In the result of each search conducted the information is displayed in columns and rows (a search results matrix). Users may manipulate the width of each column, change the order of the columns by drag-and-drop and sort by a column according to need. The current sorting column is indicated by a downwards (ascending) or upwards (descending) pointing triangle.

If you wish to remove or clear a search criterion, click the cross next to its drop down box or text field. The application treats most text searches as asking for text strings that ‘contain’ the supplied text, rather than exact matches.

The footer consists of several icons for handling the data or page through the full set of data, as shown in the table below:

<!-- TODO: icon description table for grid -->

| **Icon** | **Description** |
| :------- | :-------------- |
| data     | data            |

Each row in the matrix represents one data set with some basic information.
- That row the mouse cursor is just selecting is highlighted in light blue.
- To select a row for deletion or other actions in specific sections, the user ticks the box on the left hand side. Selected rows are highlighted in yellow.
- When a data row is clicked, the detail page opens to review and manipulate. Some screens do not have a detail page; in that case, clicking selects the row.

<!-- TODO: delete & grid export icon -->
Underneath the search results matrix, two buttons duplicate the functionality of icons in the matrix footer, namely the **Delete** button (same as <img src="src" alt="alt">) and the **Grid Export** button (same as <img src="src" alt="alt">).

When the detail page is opened, you can go back by clicking **Back to Search Results**. This button re-applies the search criteria and opens the previous search results matrix page. Additional buttons on the detail page open a blank form to create a new data set (**Add New X** or **New**), save, refresh, delete, or clear the loaded detail page. Further buttons designed for a specific detail page are described in the respective chapters of this guide.
