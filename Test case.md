**Test cases**
 
 **Test Case ID:** TC\_EDU\_01

**Test Case Name:** Adding a new education

**Description:** Verify if the user can successfully add a new education to their profile.

**Preconditions:** The user is logged in and is on their profile page.

|Steps|Data|Expected Results|
| - | - | - |
|1\.Click on the “Edukacija” section on the “Profil” page.||The “Edukacija” section is visible on the “Profil” page. User is redirected to “Edukacija” section|
|2\.Click on the “Dodaj edukaciju” button.||The form for adding a new education opens after clicking on the “Dodaj edukaciju” button|
|3\.Fill in the “Naziv univerziteta, fakulteta” field with a valid university.|ItAcademy|The providen value is entered and visible in the “Naziv univerziteta, fakulteta” field|
|4\.Fill in the “Smer” field with a valid course.|Software Tester|Providen value is displayed|
|5\.Click on the ‘od’ field|2 novembar 2023|A calendar appears. After selecting a date, the providen value is automatically set in the field.|
|Click on the “do” field|4 decembar 2023|A calendar appears.Once a date is chosen, it automatically populates the field.|
|6\.Click on the “Sačuvaj” button.||After clicking on the “Sačuvaj” button, the new education appears in the “Edukacija” section on the “Profil” page.|

**Test Case ID:** TC\_EDU\_02

**Test Case Name:** Deleting saved education

**Description:** Verify if the user can successfully delete a saved education from their profile.

**Preconditions:** The user is logged in, is on their profile page, and has at least one saved education.

|Steps|Expected Results:|
| - | - |
|1\.Click on the “Edukacija” section on the “Profil” page.|The “Edukacija” section is visible on the “Profil” page.All saved educations are listed and have a delete icon.|
|2\.Click on the option to delete, for the education from the preconditions|After clicking on the delete option, a pop-up appears asking for confirmation with “Yes” or “No” options.|
|Click “yes” on confirmation pop up|“After the user clicks on ‘Yes’, the pop-up closes and the selected education no longer appears in the ‘Education’ section on the ‘Profile’ page|

**Test Case ID:** TC\_EDU\_03

**Test Case Name:** Attempt to add education with empty fields

**Description:** Verify if the “Sačuvaj” button is disabled until all fields are filled in.

**Preconditions:** The user is logged in and is on their profile page.

|Steps|Expected Results:|
| - | - |
|Click on the “Edukacija” section on the “Profil” page.|The “Edukacija” section is visible on the “Profil” page.|
|Click on the “Dodaj edukaciju” button.|The form for adding a new education opens after clicking on the “Dodaj edukaciju” button.|
|Click on the “Sačuvaj” button.|<p>The “Save” button is disabled.</p><p>There are no changes on the page nor are any error messages displayed.</p>|

**Test Case ID:** TC\_EDU\_04

**Test Case Name:** Editing saved education

**Description:** Verify if the user can successfully edit a saved education on their profile.

**Preconditions:** The user is logged in, is on their profile page, and has at least one saved education.

|Steps|Data|Expected Results|
| - | - | - |
|Click on the “Edukacija” section on the “Profil” page.||The “Edukacija” section is visible on the profile page.|
|Click on the edit button||The form for editing education opens after clicking on the edit button.|
|Enter a new value||Providen value is displayed|
|Click on the “Sačuvaj” button.||After clicking on ‘Save’, the displayed values in the fields are updated to the entered values.|

**Test Case ID:** TC-001

**Test Case Title:** Verifying the Year of Experience Input Boundaries on the ‘Profil’ Page

**Description:** Testing the functionality of entering years of experience on the ‘Profile’ page. The goal is to check whether the system correctly prevents the entry of values below zero.

**Precondition:** The required technologies should be selected.

|Steps|Expected result|
| - | - |
|Click on the “Iskustvo” section on the ‘Profil’ page.|The “Iskustvo” section has successfully opened and displays a list of technologies and a field for selecting years of experience.|
|Reduce the number of years of experience below 0 using the “-” button.|The user is able to decrease the number of years of experience to a minimum of less <1.|

**Test Case ID:** TC-002

**Test Case Title:** Verifying the Year of Experience Input Boundaries on the ‘Profile’ Page

**Description:** Testing the functionality of entering years of experience on the “Profile” page.The goal is to verify whether the system correctly prevents the entry of values over 20 years.

**Precondition:** Technologies with less than 1 year of experience should be selected.

|Steps|Expected result|
| - | - |
|Click on the “Iskustvo” section on the ‘Profil’ page..|The “Iskustvo” section has successfully opened and displays a list of technologies and a field for selecting years of experience.|
|Click on the “+” button for any of the technologies 21 times.|The user is able to increase the number of years of experience to a maximum of more than 20.|

