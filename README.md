
## Project Planning

> The Project Planning section should be completed for your project pitch with instructors.
>
> To ensure correct Markdown, I recommend cloning this wiki and copy/pasting the raw template code.

<br>

### Overview

_**EveryCent** is a personal expense tracker. Everycent allow users to track their expenses and to analyze them. The core functionality here is adding records of the cash flow. Expenses will be divided by categories and the users will be able to create and delete expenses.
<br>

### Wireframes

> Use the Wireframes section to display desktop, tablet and mobile views.

![Dummy Link](url)

- Desktop Home page

![Dummy Link](url)

- Desktop Add Expense Page

![Dummy Link](url)

- Tablet Home page

![Dummy Link](url)

- Tablet Add Expense Page

![Dummy Link](url)

- Mobile Home page

![Dummy Link](url)

- Mobile Add Expense Page

<br>

### MVP

>_**Every Cent** Mvp will include a homepage that contains the users current balance and a list of expenses. And will be a add page that will allow you to add new expenses to you portfolio_

<br>

#### Goals

- _Display and update balance data_
- _Retrieve and display new expenses_
- _Update and delete expenses_
- _Responsive accross all screen sizes_

<br>

#### Libraries

> Use this section to list all supporting libraries and their role in the project.

|     Library      | Description                                |
| :--------------: | :----------------------------------------- |
|   React Router   | _To navigate between pages._ |
|  Axios | _To get/update/delete data from airtable._ |


<br>

#### Data

> Use the Data Section to define the API(s) you will be consuming for your project, inluding sample URL queries.

|    API     | Quality Docs? | Website       | Sample Query                            |
| :--------: | :-----------: | :------------ | :-------------------------------------- |
| AirtableAPI |      yes      | https://airtable.com/api | _https://airtable.com/appqyiVOvBv6WBtX3/api/docs#curl/authentication_ |

<br>

#### Component Hierarchy

> Use this section to define your React components and the data architecture of your app.

```
|__ src/
      |__ App.css
      |__ App.js
      |__ Index.css
      |__ index.html
      |__ AddExpense.js
      |__ Nav.js
      |__ Balance.js
      |__ Home.js
      |__ Show.js
|__ .env
|__ .gitignore
|__ package.json
|__ package-lock.json
|__ README.md
```

<br>

#### Component Breakdown

> Use this section to go into further depth regarding your components, including breaking down the components as stateless or stateful, and considering the passing of data between those components.

|  Component   |    Type    | state | props | Description                                                      |
| :----------: | :--------: | :---: | :---: | :--------------------------------------------------------------- |
|    App    | functional |   y   |   y   | _The App will interact with api._               |
|    Nav    | functional |   y   |   n   | _The Nav has components reused to link routes and update state._               |
|  Add  | functional |   y   |   y   | _The add component will retrieve and add expenses to show component._       |
|   Balance    |   functional    |   y   |   y   | _This will keep a total of the users balance._      |
|    Show      | functional |   n   |   y   | _Show will display the users expenses by category._                 |


<br>

#### Component Estimates

> Use this section to estimate the time necessary to build out each of the components you've described above. 
>
> Time frames are key to the development cycle. You have limited time to code your app, and your estimates can then be used to evalute possibilities of your MVP and post-MVP based on time needed. It's best you assume an additional hour for each component, as well as a few hours added to the total time, to play it safe.

| Task                | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------- | :------: | :------------: | :-----------: | :---------: |
| Set-up Database    |    H     |     3 hrs      |     0 hrs     |    0 hrs    |
| Create CRUD Actions |    H     |     8 hrs      |     0 hrs     |     0 hrs     |
| Show page    |    H     |     6 hrs      |     0 hrs     |    0 hrs    |
| Balance page |    H     |     4 hrs      |     0 hrs     |     0 hrs     |
| Media Queries    |    M     |     3 hrs      |     0 hrs     |    0 hrs    |
| CSS |    M     |     3 hrs      |     0 hrs     |     0 hrs     |
| TOTAL               |          |     33 hrs      |     0 hrs     |     0 hrs     |

<br>

#### Helper Functions

> Use this section to document all helper functions– generic functions that can be reused in other applications.

|  Function  | Description                                |
| :--------: | :----------------------------------------- |
| Capitalize | _Lorem ipsum dolor sit amet, consectetur._ |

<br>

### Post-MVP

> Use this section to document ideas you've had that would be fun (or necessary) for your Post-MVP. This will be helpful when you return to your project after graduation!

- _Add user account and auth capabilities._
- _Add graph to display categorys._
- _Add low balance warning._
- _Add redirect from expense page._

<br>

***

## Project Delivery

### Code Showcase

> Use this section to include a brief code snippet of functionality that you are proud of and a brief description.

### Code Issues & Resolutions

> Use this section to list of all major issues encountered and their resolution, if you'd like.
