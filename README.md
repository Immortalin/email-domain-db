# email-domain-db

###Overview
This list was created for a client who had thousands of people signing up to get a demonstration of their B2B SaaS offering. As each demonstration was done 1-on-1 with a sales representative they needed a way of prioritising the demo requests that were more likely to be from a business vs an individual for private use.

###How to use this list in Google Sheets:
* First create a new sheet with just the email addresses you want to classify.
* Sort the sheet by the email column to make sure you have no missing email addresses that will stop the autofill working.
* Create a new tab called emaildomaindb
* Copy and paste the raw emaildomaindb from https://docs.google.com/spreadsheets/d/1tNJ_o22CuTLOJCPLZjbwP569SGeSy36uy22aRNombCA/edit#gid=0 to the emaildomaindb tab on your sheet.
* Now in the cell next to your first email address (B2) copy and paste the formula shown in cells B2 to F2 at https://docs.google.com/spreadsheets/d/1tNJ_o22CuTLOJCPLZjbwP569SGeSy36uy22aRNombCA/edit#gid=568501970
* Use the auto fill button to fill down all the rows.
* If some of your emails contain multiple @@ like user@@gmail.com it will muck up the email split formula so do a find replace on @@ to @ until you have removed all multiple @@.

###Why release this publicly?:
We have made this list freely available to our clients for a while now so thought others might also find it useful. Personally I use it in Google Sheets to do a quick scrub of a contact list to split the business email accounts from the personal ones.

###Explanation of field names:
- Domain = the email domain.
- Classification = the classification of the email domain. (see below)
- Company Name = the company that own the domain.
- Company Website = the website of the company that owns the domain.

###Explanation of classifications:
- Disposable = domain is a disposable email domain where email accounts have a temporary lifespan or are throwaway. (user@armyspy.com)
- Education = very likely to be a student email but could also be a faculty member. (user@email.arizona.edu)
- Fake = domains that are sometimes real domains but are more often used by people typing in a fake email. (blah@khaskdjhs.com)
- ISP = ISP provided paid or free email accounts. (user@att.com)
- Paid = paid webmail accounts. (user@fastmail.com)
- Typo = common typo domains. (user@gmail.cmo)
- Webmail = free webmail accounts. (user@gmail.com)

###Questions:
Email adam@leadstage.com

###Issues:
If you notice an incorrect classification please create an issue so we can fix it at https://github.com/leadstage/email-domain-db/issues or email adam@leadstage.com
