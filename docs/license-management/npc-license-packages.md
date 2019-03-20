# NPC License Packages

For the five summer sports, license packages will be issued by IPC at the start of each season. The cost of the package depends on the number of athletes licensed in previous seasons. Users can restrict the list by NPC, season, sport, status and invoice number.

| **Field**                     | **Format**                                     | **Comments**                                                                              |
|-------------------------------|------------------------------------------------|-------------------------------------------------------------------------------------------|
| **Include obsolete packages** | Checkbox                                       | displays packages from past seasons                                                       |
| **Package Number**            | Code                                           | same as invoice number                                                                    |
| **Season**                    | Read-only text field                           | drop down box on package purchase form                                                    |
| **NPC**                       | Read-only text field                           | drop down box on package purchase form                                                    |
| **Sport**                     | Read-only text field                           | set by database administrator on special request                                          |
| **Status**                    | Read-only text field                           | confirmed by IPC Finance                                                                  |
| **Invoice Recipient**         | Read-only text area [specified on application] | not viewable from search form                                                             |
| **Package Price**             | Read-only integer                              |                                                                                           |
| **Package Name**              | Read-only text field                           |                                                                                           |
| **Package Licenses**          | Read-only integers                             | available and total licenses in the package                                               |
| **Total Amount**              | Read-only number (2 decimals)                  |                                                                                           |
| **Bonus Licenses**            | Read-only integer                              | Bonus licenses awarded                                                                    |
| **Bonus License Expiry**      | date                                           | if package has a special bonus license expiry date for any reason, please enter this here |
| **Comments**                  | text area                                      | editable for any comments from NPC side                                                   |

Before completing the invoice, the buyer must enter their address in the fields, as described in the table below, before clicking Save to obtain a completed invoice.

| **Field**              | **Format** | **Comments**    |
|------------------------|------------|-----------------|
| **Organisation**       | Text field | Postal name     |
| **Street / P.O Box**   | Text field | Address         |
| **Postal Code & City** | Text field |                 |
| **Country**            | Text field | Name in English |

For countries in the European Union, VAT (value added tax) information must also be included, as a VAT is levied on the licenses. Please indicate whether the invoiced organization is a taxable person, and if so, your VAT number; this will be checked against the [European Commission’s VIES database](http://ec.europa.eu/taxation_customs/vies/).

Once the order is submitted, the user processes the invoice and bank payments, and then waits for IPC Finance Department to confirm the payment. The package is listed as ‘Pending’ from the search form until this confirmation is obtained, and the package can not be used to license further athletes until payment is confirmed and the status is changed to ‘Paid’.


