# Registration & Update

Each athlete must be registered and licensed before they are eligible to compete in IPC competitions, as outlined in [IPC Licensing Programme](ipc-licensing-programme/intention.md). From this menu, users are able to complete all steps in the registration part of the process, as well as search for and update already registered athletes. Data access is restricted by NPC and sport affiliation in order to provide more relevant data for the users and to protect personal data of the athletes.

## Details

Users must navigate the Athlete Registration search screen/table before they can modify any participant details. By clicking on a row in the grid or on the *New Athlete/Guide* button,users reach the details tab with fields described in the following table.

| **Field**                                                            | **Format**                                                               | **Searchable**      | **Comments**                                                                                                                                                                                                                                  |
| -------------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <span class="table-header">Basic Information</span>                  |                                                                          |                     |                                                                                                                                                                                                                                               |
| **SDMS ID**                                                          | number, automatically assigned on participant creation                   | Yes (also by range) |                                                                                                                                                                                                                                               |
| **Registration Status**                                              | *Incomplete* or *Complete*                                               | No                  | calculated by the web application depending on documentation, see [Registration Process](ipc-licensing-programme/registration-process.md)                                                                                                     |
| **Athlete/Guide**                                                    | *Athlete* or *Guide*                                                     | Yes (as *Type*)     | users set this in creation process, *cannot be changed later*, obligatory                                                                                                                                                                     |
| **Career Status**                                                    | *Active*, *Historical* or *Retired*                                      | Yes                 | always set to active on creation, must be changed at *Career Status Updates* tab                                                                                                                                                              |
| <span class="table-header">Personal Data</span>                      |                                                                          |                     |                                                                                                                                                                                                                                               |
| **NPC**                                                              | drop down [NPC]                                                          | Yes                 | obligatory                                                                                                                                                                                                                                    |
| **Family Name (passport)**                                           | text (30)                                                                | Yes                 | family name exactly as written in the passport (except for non-English characters).                                                                                                                                                           |
| **Given Name (passport)**                                            | text (30)                                                                | Yes                 | given name exactly as written in the passport. This is culturally dependent, but usually the name that appears second in the passport                                                                                                         |
| **no Family Name**                                                   | checkbox                                                                 | No                  | in some cultures, only the given name is used in the passport. This box may be ticked to allow entries of such athletes; if not ticked, then both family and given names are obligatory fields                                                |
| **Family name (preferred)**                                          | text (30)                                                                | Yes                 | the version of the family name that will be used in all SDMS output. May be left blank on entry, will then be identical to passport name                                                                                                      |
| **Given name (preferred)**                                           | text (30)                                                                | Yes                 | as above but with given name                                                                                                                                                                                                                  |
| **Gender**                                                           | radio buttons                                                            | Yes                 | obligatory                                                                                                                                                                                                                                    |
| **Date of Birth**                                                    | date (yyyy-mm-dd)                                                        | No                  | must be older than 10 years at date of modification                                                                                                                                                                                           |
| **Photo**                                                            | picture file                                                             | No                  | displays photo of athlete and allows of upload from user's hard drive or local network. For photo requirements, refer to [File Attachments](layout-and-functionalities/file-attachments.md)                                                  |
| <span class="table-header">Nationality Information</span>            |                                                                          |                     |                                                                                                                                                                                                                                               |
| **Nationality**                                                      | drop down [country demonym]                                              | No                  | obligatory, should be the same as NPC unless there can be made an exception for the athlete under the IPC Nationality Policy (see [IPC Athlete National Policy](ipc-licensing-programme/registration-process.md#ipc-athlete-national-policy)) |
| **Nationality Status**                                               | drop down, read-only                                                     | No                  | set by the system and/or IPC in special cases. If NPC and nationality agree, will read O.K.                                                                                                                                                   |
| **Validation Document**                                              | drop down [*Passport* or *ID Card*]                                      | No                  | type of referenced document, obligatory                                                                                                                                                                                                       |
| **Passport/ID Card No**                                              | alphanumeric (30)                                                        | Yes (as             | ID number of the referenced document, obligatory                                                                                                                                                                                              |
| **Date of Expiration**                                               | date (yyyy-mm-dd)                                                        | No                  | date this document stops being valid, as determined by the issuing authority. A checkbox may be ticked if the referenced document never expires                                                                                               |
| **Upload Document**                                                  | PDF file                                                                 | No                  | to upload a scan of the referenced document from user's hard drive or local network. A link to the document, upload time and timestamp will be displayed if available                                                                        |
| **Previous NPC**                                                     | drop down [NPC]                                                          | No                  | only applicable for athletes/guides who have previously competed for other NPCs                                                                                                                                                               |
| **Confirmation Document**                                            | PDF file                                                                 | No                  | uploaded by IPC after a nationality issue has been reviewed and confirmed                                                                                                                                                                     |
| <span class="table-header">Eligibility</span>                        |                                                                          |                     |                                                                                                                                                                                                                                               |
| **Eligibility Status**                                               | drop down, read-only [*Confirmed*, *Document Missing* or *Not Eligible*] | No                  | set by the system and/or IPC, depending on adherence to the IPC Eligibility Agreement (see [IPC Eligibility Agreement](ipc-licensing-programme/registration-process.md#ipc-eligibility-agreement))                                            |
| **IPC Eligibility Agreement**                                        | PDF file                                                                 | No                  | as with the nationality upload document, for uploading and access to the eligibility agreement stored for this athlete                                                                                                                        |
| **Personal Data (Research)**                                         | checkbox                                                                 | No                  | whether the athlete has given consent to usage of data for research purposes                                                                                                                                                                  |
| **Personal Data (Marketing)**                                        | checkbox                                                                 | No                  | or for marketing purposes                                                                                                                                                                                                                     |
| **Intellectual Impairment**                                          | checkbox                                                                 | No                  |                                                                                                                                                                                                                                               |
| **Inas**                                                             | alphanumeric (16)                                                        | No                  | if athlete has intellectual impairment, he or she must be registered with INAS ( [INAS Website](http://www.inas.org/) ) and have a classification number to be eligible for IPC events.                                                       |
| <span class="table-header">Sport and Sport Class Registration</span> |                                                                          |                     |                                                                                                                                                                                                                                               |
| **Sport**                                                            | drop down [sport]                                                        | Yes                 | obligatory, upon choosing a sport, the system will display available classes within this sport                                                                                                                                                |
| **1st Class**                                                        | drop down [class]                                                        | No                  | obligatory                                                                                                                                                                                                                                    |
| **2nd Class**                                                        | drop down [class]                                                        | No                  | for sports where classification depends on discipline (e.g. athletics, swimming)                                                                                                                                                              |
| **3rd Class**                                                        | drop down [class]                                                        | No                  |                                                                                                                                                                                                                                               |
| <span class="table-header">Comments</span>                           |                                                                          |                     |                                                                                                                                                                                                                                               |
| **NPC Comments**                                                     | text (200)                                                               | No                  |                                                                                                                                                                                                                                               |
| **IPC Comments**                                                     | text (200)                                                               | No                  |                                                                                                                                                                                                                                               |

The searchable column indicates whether this field is offered as a criterion on the search form. The family name and given name fields of the search form will match in either the passport or preferred name fields, but only display the preferred name, which may sometimes lead to unexpected search results.

<img src="_img/inline/delete-button.png" alt="Delete Button" class="center inline-button">

The **delete** button is accessible from the participant detail menu, but athletes may not be deleted from the database if they are assigned a sport class.

### How To: Register a New Athlete

<img src="_img/inline/new-button.png" alt="New Athlete/Guide Button" class="center inline-button">

1. Obtain a blank athlete detail form (Figure 4.1) by clicking the *New Athlete/Guide* button (from the search form) or the *New* button (from the details page).
   
2. Referring to the athlete details table, complete all fields to the best of your knowledge. Cross-check spelling and information with the uploaded documents; for example, the spelling of the passport name should be identical to that of the uploaded ID document, as far as the English alphabet allows.

<figure>
    <img src="_img/figures/4.1-athlete-registration-create.png" alt="A blank Participant form with some notes about special items" class="screenshot" >
    <figcaption>Figure 4.1: A blank participant form with some notes about special items</figcaption>
</figure>

1. Select the sport of the athlete or guide in from the drop down box *Sport*. For athletes, then enter the classification in the drop down box 1st Class, and possibly further classifications.
   
2. Click *Save* to create an SDMS ID for the participant. Note that the athlete or guide status of the participant can no longer be changed.
   
3. Upload a photo of the participant by clicking *Browse* and choosing a file from your local hard drive or network. The requirements for photos are described in [Assigning Items](layout-and-functionalities/assigning-items.md). For quick reference, the photo should be in passport size format, around 7:10 in aspect ratio, and saved as a JPG file smaller than 250 kB.
   
4. Obtain a valid copy of the [IPC Eligibility Agreement](ipc-licensing-programme/registration-process.md#ipc-eligibility-agreement) with a signature from the athlete and/or, if the athlete is younger than 18 years old, their parent or legal guardian. Scan this document, save it as a PDF file, and upload the PDF file under the *Upload Document* field.
   
5. If all the documents have been correctly uploaded, the responsible sport department will then review the registration for correctness. If there are documentation issues or other problems with the registration, IPC shall notify the user by using ‘IPC Comments’ and/or email.
   
6. To upload documentation relating to the athlete's medical condition, e.g. Medical Diagnostic Forms, please navigate to *Participants > Classification* and search for the athlete's classification profile.

After an athlete has been registered, there may be reason to change the details, for example because of errors or omissions in the data entry process, name changes due to change in marital status, etc.

### How To: Change Athlete Details

<figure>
    <img src="_img/figures/4.2-name-change-dialogue-box.png" alt="Name change dialogue box" class="screenshot center" >
    <figcaption>Figure 4.2: Name change dialogue box</figcaption>
</figure>

1. Search for the athlete in question from the Athlete Registration search form/table, and click the row in the search grid corresponding to the athlete to enter the athlete details’ page.
   
2. The data stored about the athlete will appear in the form. Edit the incorrect or missing details and click Save.

3. If you change the passport name and/or the NPC of the athlete, a dialogue box (Figure 4.2) appears to ask you to confirm the reason for the name change. Choose one of the three supplied reasons (error, marriage or nationality change) and, if applicable, enter the date from which the change should be effective.
   
4. If you change the name of the athlete, please bear in mind that changes only apply to the field you enter, i.e., a change of passport name will not change the preferred name,which is what the IPC will use in official result lists and rankings. Hence, in case of a name change, please change both fields unless there is a specific reason not to (the athlete wishes to be known under the old name but the passport issuing body will only recognise the new name, for example).

## Classification

This section is designed for non-classifier users who wish to have a quick overview of the classes the athlete is eligible for, as well as entering and removing the class of athletes which have not yet been classified by international panels (New class status). More detailed manipulation is possible from [Classification](classification.md).

<figure>
    <img class="screenshot" src="_img/figures/4.4-summary-of-athlete-classes.png" alt="Summary of athlete's classes">
    <figcaption>Figure 4.4: Summary of athlete's classes</figcaption>
</figure>

All current classifications, with sport and class, of the athlete are displayed on this menu, along with the status of the athlete within the class. The last row of the table allows for entering of a new sport and/or class; again, this will only be accepted if the athlete is not already classified by international panels. If the registering user does not know which class the athlete will compete in, they may enter the pseudo-class N/A and leave further classification to other users with competence in that field.

For any further classification specific issues, please refer to IF rules or the IPC Medical and Scientific department.

## Career Status Updates

This tab is for modification of the *career status* field from the athlete details page. As this is rarely modified and causes severe changes in the database treatment of the athlete, this is treated apart from the athletes’ other data. The change is performed through button clicks, and only those buttons where the status is not equal to that of the current athlete are clickable; e.g. an active athlete can only be changed to retired or historical.

All historic changes to status are also displayed here, along with time stamp and username of the responsible user.

> [!DANGER]
> If an athlete is set to the career status *Historical*, they will disappear to all NPC users from all outputs (such as classification data, licensing data, etc.) except result archives. However, NPC users can include historical athletes in their search parameters by clicking on the **include historical athletes** checkbox (in the Athlete Registration search table of the Athletes module). Athletes that have been *Retired* for at least four years will automatically be set to *Historical*.

## Biography

<figure>
    <img class="screenshot" src="_img/figures/4.3-biography-fields.png" alt="Biography fields">
    <figcaption>Figure 4.3: Biography fields</figcaption>
</figure>

This tab (Figure 4.3) is designed for adding, modifying and removing data about the athlete's life to date. This is particularly designed for media and fan interaction with the athletes, allowing them to get to know the athletes’ personality beyond a statement of their results. 

The biography tab is designed to be easily modifiable in case fields need to be added or removed, and should hopefully be self-explanatory.

Fields are labelled in the left-hand column and a more detailed explanation, if necessary, in the right-hand column.

## Data Sheet

From this tab, users may request a dynamically generated data sheet in PDF format for a quick overview of the participant's career and all information stored in SDMS. All fields included in the data sheet are also accessible from their respective menus. Therefore, they will not be described in this section, but only listed with a reference to the section where information may be found.

| **Section**             | **Included**                                                                                                                                                                                                                                                                                                                           |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Personal Data**       | Photo, passport name, preferred name, gender, date of birth, NPC, nationality, passport/id card number with expiry date. For privacy reasons, passport information can be removed by ticking a checkbox (*hide passport information*)                                                                                                  |
| **Registration Status** | All fields relevant to a complete registration: Nationality status, eligibility status, career status and photo status.                                                                                                                                                                                                                |
| **Classification**      | All historic and current classifications, with class, status and date. Current classifications are in bold                                                                                                                                                                                                                              |
| **Licenses**            | All historic and current licenses tabulated. <br>**Columns:** Season, Sport code, License number, Invoice or Package, Status, Validity date                                                                                                                                                                                            |
| **Records**             | All record breaking achievements tabulated. <br>**Columns:** Record type, date, event, class, performance, location                                                                                                                                                                                                                    |
| **Results**             | All achievements registered in SDMS tabulated and grouped by competition (in blue with name, location and date). <br>**Columns:** Date, event name, eligible classes, rank, performance(s), result status, class competed in, registered class at day of performance, registered class at end of season. Team results are also listed. |

## Equipment

This tab is available for athletes to register personal competition equipment they might use in Para sport competitions.

Under the equipment tab, manufacturer, product name and catalogue/module Number (if applicable) can be added. The Technical Description should include a basic description of the main components of the equipment set (Material, Weight, Size etc.). For example:

- **Racing Wheelchair:** Aluminium frame 9000(gr), 20" front wheel, 28" rear spoked wheels, Calliper front wheel brake and lever.

- **Throwing Frame:** Steel frame with steel vertical holding bar, height 72cm, square seat 28cmx28cm.

- **Prosthesis:** Above knee running prosthesis, 3S80 Fitness Knee, 1E90 Sprinter Foot, 682 g.

All currently updated equipment sets are displayed; to add further equipment sets, click *New Equipment Set* and choose the type of equipment and the sport for which it shall be used. The maximum number of equipment sets you can register is three (3).

Once the basic information has been saved, you may now add *images* or technical document of the equipment under *PDF Documents* (Maximum 5 Images or PDF). The photos should be clear and show the product specifications as described above.

<figure>
    <img class="screenshot" src="_img/figures/4.5-athlete-equipment-tab.png" alt="Equipment tab">
    <figcaption>Figure 4.5: Equipment tab</figcaption>
</figure>

Upon the registration and submission of equipment, the Para sport committee (e.g. World Para Athletics) shall review each set and may request further details of any registered equipment. If an athlete changes their equipment throughout the season, the new equipment must be registered to SDMS.