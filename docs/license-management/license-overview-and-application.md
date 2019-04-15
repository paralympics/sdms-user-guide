# License Overview & Application

The licensing of individual athletes and guides is completed from this screen, which is designed as a step-by-step process to guide NPC users through the process of licensing. Several participants within the same sport may be licensed at once; however, only within one particular sport in one license process. The licensing of guides of blind athletes is determined by the rules in each particular sport, but in principle guides are licensed using the same process and for the same fees as for licensing Paralympic athletes, and the word athlete will be used for simplicity from here on.

This screen also functions as a search form for already existing licenses, in case users want an overview of an NPC’s licensed athletes within a sport or needs information about the status of one particular participant or application.

## Available Athletes, Status and Process

Not all athletes registered in SDMS are available to be licensed immediately, in order to restrict NPCs from licensing athletes that are not eligible to compete in IPC competitions. However, the fact that an athlete is listed in this section does not mean they are licensed. Athletes are added to this section in one of two ways:

<figure>
<img class="center" src="_img/figures/5.1-license-status-flowchart.svg" alt="License Status Flowchart">
    <figcaption>Figure 5.1: Possible license statuses and paths</figcaption>
</figure>

1. Carried over from previous season. This applies to all athletes that were available in the previous season, as long as they are still listed with *Active* career status.

2. Added from the License Renewal screen as a new registration. Whether an athlete is registered as licensed within SDMS or not is shown by the license *status*.

At the beginning of the season, all athletes carried over from the previous season are assigned the license status *New*, and when the licensing process is complete for that athlete, the status changes to *Licensed*. All possible statuses, and how they can be changed by the respectively authorised users, are shown in Figure 5.1.

Within a season, athletes are not removed from this section. If the athlete is for some reason not eligible to compete, they should be moved into the frozen path. Their license status will then depend on where they were in the licensing process before the freezing occurred. The athlete can also be unfrozen if the issue causing ineligibility is resolved. E.g., athletes with incomplete registration would be frozen, but can be unfrozen again and receive status *New* if correct documents are uploaded.

## License Search Form

The following criteria are available from the section's search form:

| **Field**            | **Format**                       | **Comments**                                                                                                            |
| -------------------- | -------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **License Category** | drop-down box [License Category] | obligatory, to distinguish between the type of license you apply for                                                    |
| **Season**           | drop-down box [Season]           | obligatory, currently active seasons listed on top. Seasons with read-only status can be selected for archive purposes. |
| **NPC**              | drop-down box [NPC]              | obligatory, automatically restricted by user rights                                                                     |
| **Sport**            | drop-down box [Sport]            | obligatory, populated upon season and license category choice                                                           |
| **License Status**   | drop-down box                    | the license status reflects the progress of the application                                                             |
| **SDMS ID**          | integer                          | search for a particular ID                                                                                              |
| **Family Name**      | text field                       | case independent, matches from the start of the input                                                                   |
| **Given Name**       | text field                       |                                                                                                                         |
| **License No**       | text field                       | code of issued license (printed on license card)                                                                        |
| **Invoice No**       | text field                       | code of invoice for license or license package                                                                          |

After completing the search from and clicking Search, the matching athletes appear in the search grid of Athlete Licenses. In addition to information about their current license status, the date of validity (for licensed athletes) and any comments from IPC are displayed.

<figure>
    <img class="screenshot" src="_img/figures/5.2-license-overview-buttons.png" alt="License search form action buttons">
    <figcaption>Figure 5.2: License search form action buttons</figcaption>
</figure>

With this search, users can perform a number of actions relating to the license status of the searched athletes. NPCs and IPC sport officers (if an NPC requests assistance) can begin the application process by selecting athletes. The application process will be described in detail in [License Renewal](license-management/license-renewal.md). Also, the *License History* button allows for access to a page with all status changes of a particular athlete, with date and the username responsible for each change listed.

Additionally, IPC sport officers have three extra buttons available to change the status of a license application: *Freeze*, *Unfreeze* and *Update*. These can all be applied to several athletes at a time. The Freezing and Unfreezing buttons are for moving athletes between the frozen and regular paths of license application: on clicking, a dialogue box is brought up showing the changes between the paths and with a text area for entering any comments.

The date of validity of the license can be changed by clicking the *Update* button: again, a comment field is provided for entry of reasons for the update, if necessary.

## Selecting and Controlling Teams

This section describes steps 2-4 in the license application process. After obtaining a list of athletes by choosing the correct criteria (category, sport, and season), users select the athletes to be licensed by clicking anywhere in the athlete's search row and then clicking the *Add to My Team* button (step 2). This updates the counter of athletes in the *Control Your Team* section (step 3 and colours all selected athletes in red. There is also a *Clear My Team* button, which removes all selected athletes and returns to the start of step 2; another option to remove athletes is described in the following section, License Application Completion.

### Notes on Adding Athletes

1. Adding athletes from several different search grids with one click is currently not supported. Users from countries with many athletes can change the number of athletes displayed on each page (default 10).
   
2. All athletes in the search grid may be selected for licensing by checking the box in the upper left corner.
   
3. Athletes already licensed may be selected from the grid, but will not be added to the team by the *Add to My Team* functionality.

Once the user has selected all athletes to license, they can complete step 4 by clicking the *License My Team* button. The user is then taken to the *License Application Completion* screen for steps 5 through 7, which are different depending on whether the sport uses packages or individual licensing.

## License Application Completion - License Package Sports

Step 5 is a control step to ensure that the correct athletes have been transferred from the previous screen. All athletes selected in the previous process are displayed in a table, with ID, family name, given name and type (athlete or guide). The NPC, season, sport, and license category are also shown here.

Step 6, shown in Figure 5.4, asks the user to select the license package for this application. All packages with free licenses are displayed and can be selected by clicking the associated row in the grid.

<figure>
    <img class="screenshot" src="_img/figures/5.3-license-before-selection.png" alt="Step 6 - before selection of available packages">
    <figcaption>Figure 5.3: Step 6, before selection of available packages</figcaption>
</figure>

Clicking the row updates the counter of Licenses from selected packages. If enough licenses are available through the selected package, the required licenses counter changes colour to green, as shown below. If more packages are required to complete the application, the colour stays red and the counter is updated to show the remaining number required.

<figure>
    <img class="screenshot" src="_img/figures/5.4-license-after-selection.png" alt="Step 6 - sufficient packages have been selected">
    <figcaption>Figure 5.4: Step 6, sufficient packages have been selected</figcaption>
</figure>

The final step of the process is completed by clicking the *Confirm & License* button. As long as enough packages have been selected to cover the required amount, the licenses will then be allotted by SDMS automatically. Each license is assigned an ID for use on the license card, with season, sport, nation and a random 8-digit number. The license is also associated with the correct license package, and the current date is stored as the license's validity date.

> [!DANGER]
> Assigning a license from a package to an athlete is binding – it is not possible to cancel an athlete's license afterwards.

## License Application Completion - Sports with Individual Licensing

In sports with individual licensing, the payment must be organized through this screen, and so step 6 consists of invoice creation instead of using a license package.

By default, the invoice is issued to the official name of the NPC registered in SDMS. If a different organisation is to be invoiced or a postal address is required on the invoice, the user may supply the name and address in four lines provided on this form.

The license application is completed and an invoice produced by clicking the *Confirm Application* button. The program then adds the details of the athlete's license and payment information into SDMS’ data repository, and a confirmation message is displayed to the user.

The user can then print off the invoice and process the payment with their bank if necessary. The status of the license is set to *Pending* until IPC Finance confirms the payment from the *Invoices / Payment History* screen, where they will change the status to *Active*.