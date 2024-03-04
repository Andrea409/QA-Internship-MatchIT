1.Summary: Lack of Responsiveness on Web Page

Steps to Reproduce:

1.  Open the web page in a browser.

2.  Right-click on the page and select "Inspect" from the context menu.

3.  In the inspection panel, click on the device toolbar to toggle the
    > device mode.

4.  Check the responsiveness of the web page by selecting different
    > device presets.

Actual Results: The web page does not adjust its layout, images, and
functionalities according to the size of the device screen. This
indicates that the web page is not responsive.

Expected Results: The web page should be responsive. It should
automatically adjust its layout, images, and functionalities to offer a
seamless user experience across different devices and screen sizes. This
includes desktops, laptops, tablets, and mobile phones. The elements on
the page should resize and rearrange themselves to fit the screen size
of the device being used. This ensures that the content is always
visible and usable, regardless of the device.

![](vertopal_7bf9074c3c51451bb4d4b38ca6ba21f6/media/image2.png){width="4.557292213473316in"
height="3.3309109798775154in"}

2.Summary: Invalid Input Validation in Phone Number Field(Web App)

Preconditions: Log in as company user.

Steps to Reproduce:

1.Navigate to the profile page.

2.Select "Profil regrutera" from the available options.

3.In the recruiter's profile form, enter the name, last name.\
4.Fill in the phone number field with alphabet characters.

Actual Results: The phone number field accepts alphabetic characters,
allowing users to enter a phone number that contains letters.

Expected Results: The phone number field should only accept numeric
characters (0-9) and possibly special characters like '+' or '-'.
Alphabetic characters should not be allowed. If a user tries to enter a
letter, the system should either prevent the input or display an error
message indicating that the input is invalid.

![](vertopal_7bf9074c3c51451bb4d4b38ca6ba21f6/media/image4.png){width="3.7031255468066493in"
height="2.097617016622922in"}

3.Summary: Incorrect Counting of Selected Technologies in MatchIT Mobile
App

Preconditions: Android OS, Xaomi Redmi note11 lite

Steps to Reproduce:

1.  Open the MatchIT mobile application.

2.  Navigate to the profile page.

3.  Select the "Tehnologije" section.

4.  Start selecting the technologies you are familiar with.

Actual Results: The application allows you to select up to 20
technologies. However, when the first technology is selected, the
counter displays zero. The counting starts from the second selected
technology, allowing you to select a total of 21 technologies.

Expected Results: The application should correctly count the number of
selected technologies starting from the first one. If the limit is 20,
then users should only be able to select up to 20 technologies, not 21.

4.Summary: Disappearance of Name and Surname on Profile Page(MOB)\
Reproduced on:OS Android, XIaomi Redmi note11 lite.

Description: When a user accesses the "Profile" page, the name and last
name at the top of the page disappear after the phone is locked and
unlocked, or when the phone automatically locks.

Steps to Reproduce:

1.  Open the MatchIT application on a Xiaomi Redmi phone.

2.  Navigate to the profile page.

3.  Check if the name and surname are visible at the top of the page.

4.  Lock the phone.

5.  Unlock the phone.

6.  Check if the name and surname are still visible at the top of the
    > page.

Expected Behavior: The name and surname should remain visible at the top
of the profile page, regardless of whether the phone is locked or
unlocked.\
![](vertopal_7bf9074c3c51451bb4d4b38ca6ba21f6/media/image3.jpg){width="1.140625546806649in"
height="2.5237970253718287in"}

Actual Behavior: The name and surname disappear from the top of the
profile page after the phone is locked and unlocked.

![](vertopal_7bf9074c3c51451bb4d4b38ca6ba21f6/media/image1.jpg){width="1.1614588801399826in"
height="2.559948600174978in"}
