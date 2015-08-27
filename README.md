### Sending emails directly from your app or using a developer service like Mailgun?

For an API like [Mailgun](http://www.mailgun.com)  you need to put the CSS inline. You can use [Premailer](http://premailer.dialect.ca/) to do this automatically.

* Copy all of email.html
* Paste the HTML as the source into Premailer
* Copy the HTML results and use them in your email view/template

### Sending test emails

You can use [Litmus Push Mail](https://putsmail.com/).

* Enter your email address you would like to send it to send the email initially to
* Click the Add button
* Give the email a subject line
* Copy and paste all of email.html
* Check the "Move my CSS inline when I click Send Email" checkbox
* Click Send!
