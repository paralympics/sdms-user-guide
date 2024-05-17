# Classification

More detailed information about classification, including signed forms, information about historic classifications, details about the classification event, and so forth, are accessed from this menu. This also allows for restriction of access, as Paralympic classification involves sensitive medical information that should ideally be accessed by as few people as possible.

The section is organized by athlete, with a specifically designed search form for classification relevant information. The athlete specific screen is then split into 3 tabs: a Classification tab for viewing, modifying, adding, archiving and deleting classifications, a Profile tab where medical information about current classifications may be added as text, and a Documentation tab for upload of PDF scans of forms and sheets.

Employees in World Para sports are authorized to modify these data, while classifiers, NPCs and LOCs have read-only access. NPCs are also solely allowed to enter an athlete in a *New* class as they wait for their athletes to be classified, but this must be done in the registration section. NPCs can additionally upload some forms on behalf of their athlete, e.g. medical diagnostic forms and equipment designs. These uploads must be done from the *Documentation* tab of the athlete's classification detail page, by clicking *Choose File* in the correct field and uploading from their own computer system.

## Search form

In addition to the fields displayed on the athlete search grid, the grid also shows the sport and class of each athlete. The table below lists the possible search fields; none are compulsory, by default the grid displays all athletes which the user can access. Only active athletes are displayed in this search; if a user wishes to access information of retired athletes, they must change the career status (see [Career Status Updates](participants/registration-and-update.md#career-status-updates)) of the athlete before being able to access information from here.

| **Field**         | **Format**        | **Comments**                       |
| ----------------- | ----------------- | ---------------------------------- |
| **SDMS ID**       | integer boxes     | enter single ID for single athlete |
| **Family name**   | text (30)         |                                    |
| **Given name**    | text (30)         |                                    |
| **Gender**        | drop down         |                                    |
| **NPC**           | drop down [NPC]   |                                    |
| **Sport**         | drop down [sport] |                                    |
| **Current Class** | text field        |                                    |

## Details

When opening an athlete's classification details page (Figure 4.6), each classification instance has its own row in its respective section (*Current or Historical*). Any current classification not with *New* status should be accompanied by documentation and confirmation from classifiers. If the athlete's class changes, this should be documented by adding a new classification section and moving the outdated one to *Historical* status.

The process of applying classification changes is performed automatically whenever users enter a new classification or when new results are added to SDMS.

<figure>
    <img class="screenshot" src="_img/figures/4.6-classification-details-tab.png" alt="Classification Details tab">
    <figcaption>Figure 4.6: Classification Details tab</figcaption>
</figure>

In the table below, the fields are listed in the format they can be accessed from the *New Classification* form when defining a new classification for an athlete.

| **Field**                  | **Format**                                               | **Comments**                                                                          |
| -------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------- |
| **Sport**                  | drop-down box [sport]                                    |                                                                                       |
| **Class**                  | 3 drop-down boxes [class]                                | populated on sport selection. A new classification is created on each class selection |
| **Status**                 | *Confirmed*, *New*, or *Review*                          | applies to all selected classes                                                       |
| **Date of Classification** | date [yyyy-mm-dd]                                        |                                                                                       |
| **Year of Review**         | year [integer 2000-2100]                                 | year of scheduled review                                                              |
| **Classifier 1**           | name (50 characters)                                     |                                                                                       |
| **Classifier 2**           | name (50 characters)                                     |                                                                                       |
| **Classifier 3**           | name (50 characters)                                     |                                                                                       |
| **Limited to**             | drop-down boxes [class group, discipline and event type] | only appears in the classification table                                              |

## Profile

The *Profile* tab displays information about the athlete's medical details. This tab is organized in sections by sport, with each section having text areas or text fields specific to the classification report compiled by classifiers in each sport. In the following table, the general fields are listed first, followed by sport-specific fields.

| **Field**                                   | **Format**                | **Comments**                                      |
| ------------------------------------------- | ------------------------- | ------------------------------------------------- |
| **Diagnosis**                               | text area                 |                                                   |
| **Physical Assessment**                     | text area                 |                                                   |
| **Medical Assessment**                      | text area                 |                                                   |
| **Observation**                             | text area                 |                                                   |
| **Exceptions**                              | text area (30 characters) |                                                   |
| **Comments**                                | text area                 |                                                   |
| **Training Sessions per Week**              | text field                | should be given as a number                       |
| <span class="table-header">Athletics</span> |                           |                                                   |
| **F45 Subclass**                            | text field                | 1 character                                       |
| **Height**                                  | text field                | maximum standing height (cm)                      |
| <span class="table-header">Shooting</span>  |                           |                                                   |
| **Class Specification**                     | text fields               | For SH1 and SH2, there exist A/B/C specifications |
| **Visible Free Height**                     | text field                | in cm                                             |

## Files
The Files tab allows for uploading and accessing sheets and forms relating to classification issues. Each athlete has one files tab per sport they are classified in.

### Upload a Medical Diagnostic Form

1. Search for the athlete from the Classification search form using any criteria available.

<figure>
    <img class="screenshot" src="_img/figures/4.7-classification-documentation-tab.png" alt="The important section of the Documentation tab">
    <figcaption>Figure 4.7: The important section of the Files tab</figcaption>
</figure>
   
1. If you have any documents to upload, go to the Files tab of the relevant sport.
   
2. Click *Browse* in the Medical Form 1 row.
   
3. Select the document from your local hard drive or network, and click *Open* (may be dependent on your language settings or browser). If successful, the file name should appear.
   
4.The files are then automatically uploaded to the SDMS servers. Any file previously accessible from that specific row is automatically moved to the *File Archive* section.