# Assignment 01: Heuristic Evaluation - Joy Hsieh, DH110
## Tentative Title: Senior Stories
Throughout the years, I've heard tidbits of stories from my grandparents and their siblings. My grandma got into college by going on a hunger strike to pressure her parents into letting her attend. My grandpa grew up in Taiwan during the martial law period and performed mandatory military service. My great aunt was a single mother and a flight attendant, at a time when not many women supported themselves and their children independently.

As my grandparents have gotten older, I've felt a great desire to capture as many stories from their lives as I can so that they may be preserved and retold to future generations of our family. I want to contribute with this UX project by creating a website or app that people like my grandparents can go to and record their life stories.

In this assignment, I will conduct a heuristic evaluation of two websites with goals similar to the ones of this project. The first, TimeSlips, allows seniors to write creative stories. The second, The Life Writer, provides a way for seniors to write a memoir book. The evaluation will discuss each site's adherence to the [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/) and provide [Severity Ratings for Usability Problems](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) with consideration for the target users, senior citizens.


## Competitor A: TimeSlips
![TimeSlips homepage](timeslips-screenshot.png)
View the full site here: [TimeSlips](http://timeslips.org)
#### Background Information
TimeSlips is an organization with a mission to help seniors to write creative stories. To do this, users can make an account, go to their "Creativity Center", and select a prompt to follow. From there, users can type their story in a text box or upload a photo of a written response. The website also has extensive information on what TimeSlips is, services that they provide, resources, news, and ways to get involved with the organization.
#### Heuristic Evaluation
_Overall Evaluation_: The website is not tailored for a senior citizen to use themselves, but for someone such as a younger family member or a caretaker to navigate for them. There are many issues that make it hard for users to navigate the site, such as poor visibility of system status and an overload of information. It is also hard for users to perform the primary function of the site: write a story. This is because the storytelling page has weak word processing power and no error prevention measures.

| Heuristic & Description                                                                                                                                                     | Evaluation                                                                                                                                                                                                                                                                                                                                                                                                                                           | Recommendation for "Bad" Element(s)                                                                                                                                                    | Severity of "Bad" Element(s) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| **1\. Visibility of system status**<br>The website clearly informs the user about its current status                                                                            | **Good**: The site gives a pop up message to tell the user when they have successfully signed in or out, when their story has been successfully saved, etc.<br>**Good**: The site clearly lets the user know if they are logged in or logged out in the upper right corner.<br>**Bad**: The site lets the user know where they are on the site by highlighting the menu option, but it isn't always obvious becuase some menu options are nestled within others. | Highlight both the main menu option and sub-menu option so users can easily know exactly where on the site they are.                                                                | 2                         |
| **2\. Match between system and the real world**<br>The website uses language that is familiar to the user and presents information in a way that is analogous to the real world | **Good**: The site uses terms like "My Dashboard", "My Training", "My Tasks", "My Stories"<br>**Bad**: The page for writing stories is called the "Creativity Center" which may not be intuitive to all users.                                                                                                                                                                                                                                                         | Rename the "Creativity Center" to the "Writing Center" or give it another more intuitive name.                                                                                      | 1                         |
| **3\. User control and freedom**<br>The website gives users a way to easily undo an unwanted action                                                                             | **Good**: The text input box for stories allows the user to undo an action by using the "ctrl+z" keys<br>**Bad**: The only way to undo an action in the text box is with "ctrl+z", there are no buttons for the user to use.                                                                                                                                                                                                                                   | Add a reverse arrow and a forward arrow that the users can click on to undo and redo their work.                                                                                    | 2                         |
| **4\. Consistency and standards**<br>The website follows conventions followed by similar websites                                                                               | **Good**: The site has menu option listed at both the top and bottom of the screen. These menu options collapse into a sidebar with three lines when the window width is narrow.<br>**Good**: Clicking on "TimeSlips" on the top of any page takes the user back to the home page.<br>**Bad**: The sidebar menu is a standard convention, but may be more difficult for seniors to navigate than having options available at the top of the page.                 | Leave the menu options at the top no matter what the screen width is or replace the three lines that indicate menu say "Menu" instead.                                              | 3                         |
| **5\. Error prevention**<br>The website prevents errors by reducing error-prone conditions or checking for them and notifying the user                                          | **Bad**: The text input box for storytelling does not have spelling and grammar check options.<br>**Bad**: On the storytelling page, the site lets me navigate to a new page without saving my work.                                                                                                                                                                                                                                                         | Have a pop-up message appear to let the user know that they have not saved their work before navigating to a new page.                                                              | 3                         |
| **6\. Recognition rather than recall**<br>The website makes information needed to navigate the website visible or easily accessible                                             | **Good**: The site's search bar labels results by "Page", "News", "FAQ" and "Story", allowing the user to easily select what they are looking for. <br>**Bad**: Each menu option has several sub-menu options nestled within it, forcing the user to recall the organization of the site.                                                                                                                                                                     | Consolidate sub-menu options to reduce the cognitive load placed on users.                                                                                                          | 3                         |
| **7\. Flexibility and efficiency of use**<br>The website allows processes to be tailored to all users from novice to expert                                                     | **Good**: The storytelling page gives users different options to input their story, allowing them to type, upload a photo, or audio record a response.<br>**Bad**: The text input box doesn't allow users to use text editing shortcuts like "ctrl+B" to make text bold.                                                                                                                                                                                      | Give the text input box shortcut functionalities for Bold, Italic, Underline, and Hyperlink (the functions that are available in the text editing menu bar).                        | 2                         |
| **8\. Aesthetic and minimalist design**<br>The website only contains information that is relevant and is designed to highlight the essentials                                   | **Good**: The site has 3 text size options for users to choose from.<br>**Bad**: "Creativity Center", the place to go to write stories, is not easily findable. There is a lot of "extra" information that pertains to the organization that makes it hard to find the information that is for the storytelling.                                                                                                                                              | Make the "Creativity Center" a main menu option.                                                                                                                                    | 3                         |
| **9\. Help users recognize, diagnose, and recover from errors**<br>The website provides clear error messages that state the problem and potential solutions                     | **Good**: If the user provides incorrect sign in information, the site tells the user that they have "Invalid Email or password"<br>**Bad**: The site does not specify which input is invalid and leaves the email address provided filled in, even if it is incorrect.                                                                                                                                                                                       | Let the user know if the email isn't recognized or if the password is incorrect, and provide users with ways to resolve both errors.                                                | 2                         |
| **10\. Help and documentation**<br>The website has resources to help users understand how to complete tasks                                                                     | **Good**: The site has a "FAQ" page and a "Contact Us" button that leads to a Contact page within the site.<br>**Bad**: The "FAQ" page is hidden within the "About" menu options and is hard to find.<br>**Bad**: The "FAQ" page does not have a section dedicated to the storytelling dashboard.                                                                                                                                                                 | Make the "FAQ" page it's own menu option, at least at the bottom of the page to make it easier to find.<br>Add a section to the "FAQ" page dedicated to the storytelling dashboard. | 3                         |

## Competitor B: The Life Writer
![TheLifeWriter homepage](TheLifeWriter-screenshot.png)
View the full site here: [The Life Writer](https://www.thelifewriter.com)
#### Background Information
The Life Writer is a website with a mission to helps seniors author an autobiographical memoir. To do this, users can make an account and answer some basic life questions. Based on these responses, The Life Writer will create "chapters" that the users can use as a guide to write their stories and add related photos. When the user is done, the book can be downloaded or printed. This website also feautures a background on The Life Writer, an example book, blog, and testimonials.
#### Heuristic Evaluation
_Overall Evaluation_: The website is well tailored for a senior citizen to use themselves because it is aesthetically simple and provides only the essential information needed to perform the primary function of the site: write a story. However, some major updates are needed in user freedom, error prevention, and help & documentation.

| Heuristic & Description                                                                                                                                                     | Evaluation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Recommendation for "Bad" Element(s)                                                                                                                                                                                    | Severity of "Bad" Element(s) |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| **1\. Visibility of system status**<br>The website clearly informs the user about its current status                                                                            | **Good**: The site underlines or highlights the menu option of the page the user is currently on.<br>**Good**: The site clearly lets the user know if they are logged in or logged out in the upper right corner.<br>**Good**: The site gives a pop-up notification to let the user know when their work has been saved.                                                                                                                                                                                                                                                                                                          | No recommendations for improvement.                                                                                                                                                                                 | 0                         |
| **2\. Match between system and the real world**<br>The website uses language that is familiar to the user and presents information in a way that is analogous to the real world | **Good**: The site uses terms analagous to books like "Title", "Dedication", and "Chapters" to let users know exactly what they are editing.<br>**Bad**: The menu option "Pearls" is not familiar language or intuitive.                                                                                                                                                                                                                                                                                                                                                                                                      | Change the menu option titled "Pearls" to it's full name, "Pearls of Wisdom". Maybe change the name to "Words of Wisdom".                                                                                           | 1                         |
| **3\. User control and freedom**<br>The website gives users a way to easily undo an unwanted action                                                                             | **Good**: The text input box for stories allows the user to undo an action by using the "ctrl+z" keys.<br>**Bad**: The site doesn't let the user change answers to the life questions or remove chapters from the book.                                                                                                                                                                                                                                                                                                                                                                                                       | Allow users to change answers to the life questions or remove chapters from the book. Warn users about removing chapters if they have already written content for those sections.                                   | 3                         |
| **4\. Consistency and standards**<br>The website follows conventions followed by similar websites                                                                               | **Good**:The site has menu option listed at both the top and bottom of the screen.<br>**Good**: Clicking on "The Life Writer" on the top of any page takes the user back to the home page.                                                                                                                                                                                                                                                                                                                                                                                                                                    | No recommendations for improvement.                                                                                                                                                                                 | 0                         |
| **5\. Error prevention**<br>The website prevents errors by reducing error-prone conditions or checking for them and notifying the user                                          | Bad: The text input box for storytelling does not have spelling and grammar check options.<br>**Bad**: On the storytelling page, the site lets me navigate to a new page without saving my work.                                                                                                                                                                                                                                                                                                                                                                                                                          | Have a pop-up message appear to let the user know that they have not saved their work before navigating to a new page.                                                                                              | 3                         |
| **6\. Recognition rather than recall**<br>The website makes information needed to navigate the website visible or easily accessible                                             | **Good**: Hovering over a button in the text editing box provides a description of the action and tells the user what keys serve as a shortcut for the action.<br>**Bad**: To see the chapters, the user has to go to "Book Overview" then "Save Content". Some users may think that "Preview Book" will lead them to the chapters page but this leads to a PDF of what is written so far, not the chapter editing page.<br>**Bad**: Within each chapter, each section has specific questions for the user to answer but there is no preview of the questions on the chapter page. They show up as "Section 1", "Section 2", etc. | Reduce the number of clicks needed to get to the chapter preview and eliminate confusing alternatives because it is the main page for editing the book.<br>Add a preview of the questions below each section title. | 3                         |
| **7\. Flexibility and efficiency of use**<br>The website allows processes to be tailored to all users from novice to expert                                                     | **Good**: The text editing box has buttons and allows shortcuts for modifying text (can use the "B" button or "ctrl+B" shortcut to make text bold).<br>**Bad**: There are limited options for entering story information.                                                                                                                                                                                                                                                                                                                                                                                                     | Add other ways for stories to be submitted, like with a text-to-voice option.                                                                                                                                       | 1                         |
| **8\. Aesthetic and minimalist design**<br>The website only contains information that is relevant and is designed to highlight the essentials                                   | **Good**: Most of the information on the website is essential to the book writing process or addresses user concerns about the product (Example Book).                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | No recommendations for improvement.                                                                                                                                                                                 | 0                         |
| **9\. Help users recognize, diagnose, and recover from errors**<br>The website provides clear error messages that state the problem and potential solutions                     | **Good**: If the user provides incorrect sign in information, the site tells the user that they have "Invalid Email or password"<br>**Bad**: The site does not specify which input is invalid and leaves the email address provided filled in, even if it is incorrect.                                                                                                                                                                                                                                                                                                                                                        | Let the user know if the email isn't recognized or if the password is incorrect, and provide users with ways to resolve both errors.                                                                                | 2                         |
| **10\. Help and documentation**<br>The website has resources to help users understand how to complete tasks                                                                     | **Good**: There is a support phone number shown on each page and a "Contact" page easily located in the menu bar that lets users send a message with a form, with contact emails, or to a mailing address.<br>**Bad**: The "FAQ" page is hidden within the "Create a Book" page and there is no way to navigate to it directly from other pages.                                                                                                                                                                                                                                                                              | Make the FAQ page easily accessible from other pages. Provide a link to it on the "Contact" page so users can look at it before submitting a question that may have already been answered.                          | 3                         |


## Credits
Websites that I went to for information or inspiration!

10 Usability Heuristics for User Interface Design (https://www.nngroup.com/articles/ten-usability-heuristics/)
<br>Severity Ratings for Usability Problems (https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)
<br>How to conduct a heuristic evaluation (https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/)
<br>10 tips on how to conduct heuristic evaluation (https://medium.muz.li/10-tips-on-how-to-conduct-a-perfect-heuristic-evaluation-ae5f8f4b3257)
<br>Making School and Weather More Accessible (https://github.com/emdipressi/DH150-DiPressi#ccle-mobile)
