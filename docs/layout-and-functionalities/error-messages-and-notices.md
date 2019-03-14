# Error Messages and Notices

The application informs the user about the success or error on his actions in any screen or data set. These messages appear at the top of the application, underneath the primary menu bar.

White notices on blue background report on the successful actions like submission of data, creation, update, or deletion of a data set, creation of a new invoice etc.

<!-- TODO: Blue flash message -->
<figure>
    <img class="screenshot" src="src" alt="Flash message for successful action">
    <!--<figcaption>caption</figcaption>-->
</figure>

On the other hand, red messages indicate that the intended action was not successfully performed to prevent that incorrect data are stored or data sets removed which are associated with other important data sets.

<!-- TODO: Red flash message -->
<figure>
    <img class="screenshot" src="src" alt="Flash message for error">
    <!--<figcaption>caption</figcaption>-->
</figure>

A yellow warning message is displayed when the user’s action could cause database integrity issues. Usually, the user’s action is not carried out.

<!-- TODO: Yellow flash message -->
<figure>
    <img class="screenshot" src="src" alt="Flash message for warning">
    <!--<figcaption>caption</figcaption>-->
</figure>

Notices to the user vanish after a short time; they can also be clicked on to remove them immediately.
Reasons for an error are manifold, the most common errors are

- Mandatory fields were not filled.
- Attached files do not meet the requirements (see chapter 2.5).
- The field value has not the right content or format (see chapter 2.4).
- An essential data set (like an athlete) is attempted to be deleted although other essential data sets (like licenses, results, or records) are associated.
- User credentials were incorrect on login attempt (see chapter 2.1.4).
  In the data set detail pages, the values that the user changed or included are stored from the previous submission, except file selections from the user’s local terminal for security reasons.

Most of the cases can be resolved by the user reading and applying the instructions of the error message. When an unclear or cryptic error message appears, please contact the SDMS Administrator for explanation and support to fix the issue.
