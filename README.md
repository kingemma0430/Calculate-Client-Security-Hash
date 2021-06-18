# Develop Environment
UiPath Studio Comunity, Profile is UiPath Studio Pro
Chrome browser
ACME URL (need register firstly): https://acme-test.uipath.com
Sha1-online: http://www.sha1-online.com

# Calculate-Client-Security-Hash
RPA Developer Advance Practice 1

# Requirement
Generate the Security Hash for each Client hased on their personal information.

# FYI
If the Client has been Update to "Completed", will be skipped, but you can change it in "Filter Data Table With Type and Status" sequence in ExtractWorkItems.xaml

# Step Short Description
1.1 Open the ACME System 1 Web Application.
1.2 Log in to System 1. Required input data: email and password.
1.3 Access the Dashboard - the central location, where the user can pick a specific menu item.
1.4 Access the Work Items listing to view all the available tasks to be performed (Output data: Work Items).
1.5 For each activity of the WI5 type, perform the following steps:
1.5.A Open the Details page of the selected activity to retrieve the Client Details.
1.5.B Open the SHA1 Online webpage - http://www.sha1-online.com , and provide the following input: ClientID ClientCountry. Replace all the variables with                  the corresponding values. Use dashes between each item and the above.
1.5.C Retrieve the Client Security Hash value from the webpage. 
1.5.D Go back to Work Item Details and open Update Work Item.
1.5.E Set the status to “Completed”. Add a comment with the obtained SecurityHash.
1.6 Continue with the next WI5 Activity.
1.7 Logout and Close all website (ACME and sha1-online)


# Author
Zhen (Evan) Wang, Tel:18901599114, WeChat: 18901599114, EmaiL: 18901599114@163.com

MIT
