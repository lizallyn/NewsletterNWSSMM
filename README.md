# NewsletterNWSSMM

Files to create the bi-annual NWSSMM newsletters using google form responses submitted by group members.

1. Open NWSSMM_newsletter.Rmd and edit the spreadsheet links as needed.

2. Run the chunk about Google Sheets authorization. Make sure the authorization runs and is connecting properly to the nwssmm.leaders account. When it gives you a pop-up in the browser to authenticate, make sure you click the box to enable sheet reading writing and editing access. Otherwise it will say you don't have access.

3. If you have problems with authentication or forgot to click the box, try running gs4_deauth() to force it to give you the pop-ups again.

4 Knit the doc and cross your fingers!
