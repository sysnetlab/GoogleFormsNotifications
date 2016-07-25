# Google Forms Notifications Extended

*Form Notifications Extended* is a Google Forms add-on that was extended from 
Google's Form Notifications add-on available at 
[Github](https://github.com/googlesamples/apps-script-form-notifications-addon). 

The add-on allows owners of a Google form to send notifications to either the owners,
or the respondents, or both the owners and the respondents. 

The extension includes the support the expansion of a few *variables* that 
can be embedded in the e-mails to respondents. The variables include

* confirmation message
* url to view responses
* url to prefilled form
* url to edit form
* url to new submission

To use these variables, simply wrap the variables above in double curly braces, `{{`
        `}}`, e.g., 

* `{{confirmation message}}`
* `{{url to view responses}}`
* `{{url to prefilled form}}`
* `{{url to edit form}}`
* `{{url to new submission}}`

For the last four variables, you may also use the 
[Markdown Link](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#links) 
format to provide your own link texts, e.g., 

* `{{[Click to view submitted responses](url to view responses)}}`
* `{{[Click to submit prefilled form](url to prefilled form)}}`
* `{{[Click to edit your response](url to edit form)}}`
* `{{[Click to submit another response](url to new submission)}}`

The number of notifications this add-on produces are limited by the owner's
available email quota; it will not send email notifications if the owner's
daily email quota has been exceeded. Collaborators using this add-on on the
same form will be able to adjust the notification settings, but will not be
able to disable the notification triggers set by other collaborators.

You are welcome to request features by submitting issues here. 
