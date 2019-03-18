# Data Fields

Search criteria forms, entity detail pages and similar generally are simple HTML forms and are composed of free text fields, drop down menus, radio, and tick boxes. Each field is labelled according to its value behind. Some fields have prepended a small info icon <img src="src" alt="Information Icon"> which contains more explanations and regulations about the field and its content when clicked. <!-- TODO: Add information icon -->

SDMS has a few additional functionalities or tools behind the fields the user must be aware of:

- Mandatory Fields – Fields with a light yellow background are mandatory. Leaving such a field blank upon submission will cause an error, and the data set won’t be saved unless the field has a valid value.
- Value Validity Control – Each field is subject to a set of specific rules. These rules might consider value length (number of characters), value type (integer, float, text, …) or even specific value formats (dates, NPC Code, …). On validation failure, an error is thrown.
- Files – When a file upload becomes necessary, the file is checked against the maximal file size (in bytes) and file format (photos, PDFs). Photos, in particular, are additional reviewed for potential limits in image size (in pixels).
- Character Sets – As the only language in SDMS is English, all names and other information shall be written in English language and using the English (Latin) alphabet. Most of the fields allow extended Latin characters (like ä, ß, ë, ç) even if not recommended; particularly, names should be supplied using the 26 characters of the English alphabet. Other writing systems (Greek, Cyrillic, Chinese etc) are not supported by SDMS on purpose; exceptions are clearly indicated.
- Date Field – The standardized date field format is yyyy-mm-dd (year – month – day).

  <!-- TODO: Date Field Images -->
  <img class="screenshot" src="src" alt="Date Field">

  When a date field (e.g., athlete’s date of birth) is focussed, a small calendar tool appears to facilitate the date format. Drop down boxes on top opens the respective sheet per month and year. The buttons <img src="src" alt="Left Scroll"> and <img src="src" alt="Right Scroll"> scroll through the calendar by month. Currently selected date is highlighted in orange. This small window closes automatically when a date is selected, the button Done is clicked or another field is focussed. In some date fields, minimum and maximum dates are set up. The calendar tool for those fields only displays the acceptable date range.
