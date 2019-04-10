# Classification Report

The *Classification Report* is the main report produced by SDMS, and the one with the most customizable options. It can be used to prepare classification schedules for competitions, get an overview of all athletes from a country, region, and or sport. It can also be used to review the registration and license status, if this is necessary. For example, it may be desirable to only include already licensed athletes when entering athletes for the schedule, or if one would like an overview of all information an NPC has entered about an athlete.

A classification report can only be produced for one sport at a time; therefore, the Sport drop-down box is compulsory. It is populated based on the selection in the Season drop-down box, which by default selects the most current summer season. To switch between winter and summer sports, you must therefore select a winter season.

## License Status

The final compulsory field is the *License Status* drop-down box. This controls the license status of the included athletes. By default, the report only includes athletes who are (were, for past seasons) licensed for the selected season. To change this, there are five options:
- **Licensed:** shows only athletes with an active license for the selected season
- **Licensed & Pending:** filters all athletes with active or pending licence status for the selected season
- **Registered:** all athletes from the licence management that have been accepted for the selected season unless they have an incomplete, cancelled or frozen licence status
- **Registered & Cancelled:** shows all athletes from the licence management for the selected season
- **Complete Database:** shows all athletes in the entire database (with an SDMS ID). Choose this option if you do not want to restrict the search to a particular season.

## Other Options

A comprehensive table of all search options follows.

| **Field**                     | **Type**                                                                        | **Description**                                                                                                                                              |
| ----------------------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Sport**                     | Drop-down box [sport]                                                           | Select by sport                                                                                                                                              |
| **Region**                    | Drop-down box [region]                                                          | Select by region (continent)                                                                                                                                 |
| **NPC**                       | Drop-down box [country]                                                         | Select your own NPC                                                                                                                                          |
| **Show registration status**  | Checkbox                                                                        | Include columns on registration criteria (Excel only)                                                                                                        |
| **License Status**            | Drop-down box                                                                   | Compulsory field, see section [License Status](#license-status)                                                                                              |
| **Season**                    | Drop-down box [season]                                                          |                                                                                                                                                              |
| **License Programme**         | Drop-down box [license category]                                                |                                                                                                                                                              |
| **Competition Module & Code** | Text field and drop-down box                                                    | Limit your search to athletes entered for a specific competition                                                                                             |
|                               | <span class="table-header center">Specifications – for Excel report only</span> |                                                                                                                                                              |
| **show license status**       | Checkbox                                                                        | When ticked, license status (e.g. New, Licensed, etc.) of the athlete for the selected season and sport is printed                                           |
| **show license comments**     | Checkbox                                                                        | Any IPC comments about licensing or registration are printed.                                                                                                |
|                               | <span class="table-header">Classification Profile Data</span>                   |                                                                                                                                                              |
| **Field name**                | Checkboxes                                                                      | These are the classification fields as can be entered from the *Profile* section. See section [License Status](#license-status) for a list of field meanings |
|                               | <span class="table-header">Sorting</span>                                       |                                                                                                                                                              |
| **Sort Order**                | Radio boxes                                                                     | The report is always sorted by NPC first. Ordering within NPC can be done by *Name* or by *SDMS ID*.                                                         |

# PDF Export

PDF reports are printed in landscape format, with a set number of columns (6-8 depending on the sport) when you click the *Open as PDF* button. The report is also timestamped and verified with the official logos of IPC and SDMS.

From the left, each row includes personal data – SDMS ID, family name, given name, gender, date of birth – the athlete’s current class in each of the major class groups, the class status, and the year of review. If the athlete is in different classes for different events and/or disciplines, this is also shown next to the class name.

Athletes with Guide as typed are simply listed with ‘Guide’ next to personal data, and no classification data is loaded.

If the tickboxes of classification profile data is included in the report, each additional field is printed on a separate row below the personal and classification data. The field name is printed in italics below the gender column, and the field content below the class data.

If an athlete is registered with two or more current classes in the same event type, an error message is printed in red below the athlete’s row.

# Excel Export

The Excel export is similar to the PDF, but meant for internal use and manipulation. The athletes are listed in rows by the sorting order specified; as there is no restriction on horizontal space in a spreadsheet, all classification data is displayed in a single row. Further, you can include columns which indicate whether the classification files have been uploaded in the documentation tab.

This also allows space to include some extra columns with registration, licensing, and uploaded form data; these are listed as *Specifications* in the Other Options table.

In Excel, you can manipulate the report with search filters, sorts, etc., but this is spreadsheet-specific, and outside the scope of this manual.