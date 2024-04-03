# PFP Emails
<img src="./assets/images/PFP_Emails.svg" alt="Grid of PFP emails and their aliases.">

## ZoHo-Gmail integration process

*Transcribed from https://bluroot.ca/step_by_step/how-to-use-zoho-mail-in-gmail/*

1. Open Gmail settings
  - Login to Gmail
  - Open settings in gmail (gear icon)
  - Choose 'See all settings'
  - Navigate to the 'Accounts and Import' tab
  - Choose 'Add an mail account' under 'Check mail from other accounts'
2. Generate ZoHo Application password
  - Login to ZoHo account you want to integrate
  - Go to 'My Account' settings
  - Choose 'Security' Tab
  - Scroll down to 'Application-Specific Passwords'
  - Generate one for 'Gmail', don't close the pop-up until step (6)
3. Setup receiving
  - Return to the Gmail yellow dialog box and follow its instructions
  - Email is ####@purduefirst.org (#### = subteam)
  - Import using 'POP3'
  - Enter the ZoHo email
  - Enter ZoHo Application password
  - POP server: `pop.zoho.com` port: `995`
  - Check 'use an SLL connection' box
4. Setup sending
  - Continue the directions in the yellow dialog box
  - 'Yes' to being able to send
  - SMTP (IMAP) server: `smtp.zoho.com` port: `465`
  - Enter the ZoHo email
  - Enter ZoHo Application password
5. Send test emails to confirm connection
  - May have to unflag the connection on ZoHo side
6. Enjoy

