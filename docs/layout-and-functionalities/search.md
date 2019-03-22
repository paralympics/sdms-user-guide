# Search Forms & Results Matrix

Each section handling one particular data entity of SDMS, e.g. sports, events, organizations or athletes, has a search functionality to target the user’s data.

The search page in turns offers a results matrix with an input row for the search criteria. When a new section is opened, the current criteria are automatically applied, along with the user’s permission criteria (for example, an NPC user for Germany will only receive search results about German athletes), and the results are displayed. Generally, the search returns all relevant results when initially opened, and the current criteria can then be modified. When changing the drop-down boxes, the search is automatically reset, while when changing text boxes, users must refresh or press the **Enter** (return) key on their keyboard.

<figure>
    <img class="screenshot" src="_img/figures/2.8-search-results-matrix.png" alt="Search Results Matrix">
    <figcaption>Figure 2.8: Search Results Matrix - Countries</figcaption>
</figure>

Users specify their search parameters by entering text or selecting items from the dropdown search fields. Each search field only allows for entries with fewer or the same number of characters defined in the database structure.

The reset button <img src="_img/inline/icon-reset.svg" alt="Reset Button" class="inline"> resets the search to its initial parameters. If you need to clear the grid of all parameters, use the clear grid button in the bottom row.

Users specify their search parameter by entering text or select items from the dropdown search fields. Each search field only allows for entries with fewer or the same number of characters defined in the database structure.

In the result of each search conducted the information is displayed in columns and rows (a search results matrix). Users may manipulate the width of each column, change the order of the columns by drag-and-drop and sort by a column according to need. The current sorting column is indicated by a downwards (ascending) or upwards (descending) pointing triangle.

If you wish to remove or clear a search criterion, click the cross next to its drop down box or text field. The application treats most text searches as asking for text strings that ‘contain’ the supplied text, rather than exact matches.

The footer consists of several icons for handling the data or page through the full set of data, as shown in the table below:

| **Icon**                                                                               | **Description**                                                                                                                     |
| :------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------- |
| <img src="_img/inline/icon-delete.svg" alt="Delete" class="inline">                    | Deletes the selected row(s). On attempt to delete data which is related to other information or entities, an error message appears. |
| <img src="_img/inline/icon-reload.svg" alt="Reload" class="inline" >                   | Reloads the grid.                                                                                                                   |
| <img src="_img/inline/icon-reset.svg" alt="Reset" class="inline">                      | Clears the search parameters.                                                                                                       |
| <img src="_img/inline/icon-column.svg" alt="Column" class="inline">                    | Manipulate order and number of columns supported by a small interface.<span class="asterisk">*</span>                               |
| <img src="_img/inline/icon-print.svg" alt="Print" class="inline print">                | Prints all data based on search criteria and column selection and order in one new window.                                          |
| <img src="_img/inline/icon-export.svg" alt="Export" class="inline">                    | Exports all data based on search criteria and column selection and order into an Excel file.                                        |
| <img src="_img/inline/icon-save.svg" alt="Save" class="inline">                        | Save grid settings for later, will be used as default settings until reset or overwritten.                                          |
| <img src="_img/inline/icon-tools.png" alt="Tools" class="inline icon-set" width="85%"> | Tools to select matrix pages.                                                                                                       |
| <img src="_img/inline/icon-first.svg" alt="First" class="inline">                      | Go to first page.                                                                                                                   |
| <img src="_img/inline/icon-previous.svg" alt="Previous" class="inline">                | Go to previous page.                                                                                                                |
| <img src="_img/inline/icon-next.svg" alt="Next" class="inline">                        | Go to next page.                                                                                                                    |
| <img src="_img/inline/icon-last.svg" alt="Last" class="inline">                        | Go to last page.                                                                                                                    |
| <img src="_img/inline/icon-direct.png" alt="Direct" class="inline icon-set">           | Direct page selection: change page number and press **Enter**.                                                                      |
| <img src="_img/inline/icon-rows.png" alt="Rows" class="inline icon-set">               | Changes the number of rows per page.                                                                                                |
| <img src="_img/inline/icon-current.png" alt="Current" class="inline icon-set">         | Shows current position and total data rows based on search criteria.                                                                |

<p class="footnote">
    <small><span class="asterisk">*</span>Hidden columns which do not fit in the default view can be added here if necessary.</small>
</p>

Each row in the matrix represents one data set with some basic information.
- That row the mouse cursor is just selecting is highlighted in light blue.
- To select a row for deletion or other actions in specific sections, the user ticks the box on the left hand side. Selected rows are highlighted in yellow.
- When a data row is clicked, the detail page opens to review and manipulate. Some screens do not have a detail page; in that case, clicking selects the row.

Underneath the search results matrix, two buttons duplicate the functionality of icons in the matrix footer, namely the **Delete** button (same as <img src="_img/inline/icon-delete.svg" alt="Delete" class="inline">) and the **Grid Export** button (same as <img src="_img/inline/icon-export.svg" alt="Grid Export" class="inline">).

When the detail page is opened, you can go back by clicking **Back to Search Results**. This button re-applies the search criteria and opens the previous search results matrix page. Additional buttons on the detail page open a blank form to create a new data set (**Add New X** or **New**), save, refresh, delete, or clear the loaded detail page. Further buttons designed for a specific detail page are described in the respective chapters of this guide.
