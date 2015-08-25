# mailAppChallenge

The Challenge: Email Client

For XYZ Company employees, we have decided to write our own e-mail client, as the current solutions available don't fit our specific needs. Back-end developers have supplied us with a data-format, and a rough mockup to investigate if we can build this on the client-side. Your task will be to write an e-mail client with the following functionality:

- List e-mails (see data-source/JSON file) on the lef-hand side.
- The list is grouped by date
- The list is filterable by "unread e-mails", or "read & unread e-mails". Grouping still applied.
- After clicking on an e-mail in the list, details are shown in the panel on the right hand side.

You are free to choose any framework or library for this task, but would recommend to keep it simple. We are looking for good JavaScript developers, not good [insert framework] developers. If you have time left, feel free to make the interfact attractive with enter/exit animations when applying filters, or when selecting an e-email to show in the main content panel.

Delivery
Please work in a publicly accessible Git repository. Commit as often as you feel is appropriate for us to follow your reasoning, and the way you iterate. When you're done please share the link.

My Solution:

This application is a quick and dirty JavaScript challenge to create a JS email client application. Due to time constraints there are some additional notes in with the JS about decisions made and additional potential future issues to address, such as HTML enriched "body" or "content" data. Additionally, the decision to use iFrame was a quick solution but ultimately the display should dynamically adapt to screen size. I made the look of the application to module after the MS outlook online mail application since the mockup design looked very close to that. I would also like to consolidate the code into more of a MVC framework but this is also the result of cutting corners due to time constraints. Same with only developing and testing in the Chrome browser. I also only used jQuery as there were similar tutorials online for Anguluar.js and other libraries, which defeats the purpose of the JS challenge. Lastly, I did not group/order the emails based on date as requested since the image/mockup shows dates but the test JSON data provided by the backend team is just junk data and not real date/timestamp information. Therefore grouping by a randomized number is not possible. Thanks.
