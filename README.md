# UM Admin User Profile Update Email
An email template for sending an email to the site admin when an UM User Profile is updated either by the User or a Site Admin both from WP User -> Edit and the UM Profile Form.

Profile fields updated via the UM Account page's existing or optional tabs are not supported by this plugin and will not send an Admin email.

## UM Settings -> Email -> Profile is updated email 
1. Profile is updated email -> Include these UM Profile Forms - Multiple selection of UM Profile Forms for admin email when profile is updated by the User, none selected send emails always.
2. Admin Email Profile Update - Backend UM Profile "Form" - Select UM Profile "Form" for mapping of backend submitted WP fields. No selection disable backend emails.
3. Admin Email Profile Update - CC: email to User - Click for a CC: email to the profile owner address.
4. Admin Email Profile Update - Admin User email - Select UM or WP Admin User email address.
5. Customize the email template "Profile is updated email" if required.
6. Extra Email placeholders: {profile_url}, {current_date}, {updating_user}

## Updates
1. Initial Release

## Installation
1. Install by downloading the plugin ZIP file and install as a new Plugin, which you upload in WordPress -> Plugins -> Add New -> Upload Plugin.
2. Activate the Plugin: Ultimate Member - Admin Email Profile Update
3. Email Template autoinstalls when you go to UM Settings Email
