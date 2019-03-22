# Error Messages and Notices

The application informs the user about the success or error on his actions in any screen or data set. These messages appear at the top of the application, underneath the primary menu bar.

## Information

White notices on a green background report on general information to the user such as successfully lig in.

<figure>
    <img src="_img/inline/flash-message-info.png" alt="Flash message for information" class="screenshot" >
</figure>

## Success

White notices on blue background report on the successful actions like submission of data, creation, update, or deletion of a data set, creation of a new invoice etc.

<figure>
    <img src="_img/inline/flash-message-success.png" alt="Flash message for successful action" class="screenshot" >
</figure>

## Error

On the other hand, red messages indicate that the intended action was not successfully performed to prevent that incorrect data are stored or data sets removed which are associated with other important data sets.

<figure>
    <img src="_img/inline/flash-message-error.png" alt="Flash message for error" class="screenshot">
</figure>

Notices to the user vanish after a short time; they can also be clicked on to remove them immediately.
Reasons for an error are manifold, the most common errors are

- Mandatory fields were not filled.
- Attached files do not meet the requirements (see [File Attachments](layout-and-functionalities/file-attachments.md)).
- The field value has not the right content or format (see [Data Fields](layout-and-functionalities/data-fields.md)).
- An essential data set (like an athlete) is attempted to be deleted although other essential data sets (like licenses, results, or records) are associated.
- User credentials were incorrect on login attempt (see [Security and Passwords](layout-and-functionalities/access.md#security-and-passwords)).
  In the data set detail pages, the values that the user changed or included are stored from the previous submission, except file selections from the user’s local terminal for security reasons.

Most of the cases can be resolved by the user reading and applying the instructions of the error message. When an unclear or cryptic error message appears, please contact the SDMS Administrator for explanation and support to fix the issue.

## Warning

A yellow warning message is displayed when the user’s action could cause database integrity issues. Usually, the user’s action is not carried out.

<figure>
    <img src="_img/inline/flash-message-warning.png" alt="Flash message for warning" class="screenshot">
</figure>
