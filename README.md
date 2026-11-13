https://spendwiseweek7.netlify.app

# SpendWise - Smart Interactive Budgeting

## Description
SpendWise helps users track their money. Users can set a monthly budget, add daily expenses, see how much they have spent, and see their remaining balance.

## Features
- Set total budget in KES
- Add expense with name, amount and category
- Shows Total Budget, Total Spent and Balance automatically
- Shows message if within budget or over budget
- Delete a single expense
- Clear All button to reset everything

## Technologies Used
- HTML, CSS, JavaScript
- GitHub for version control
- Netlify for deployment

## How To Use
1. Open the live site
2. Enter budget e.g. 8005 and click Set Budget
3. Enter expense e.g. Rent, 2000, choose category and click Add Expense
4. Check Total Spent and Balance

## Deployment Process Summary
1. I built the project locally using HTML, CSS, and JavaScript, with index.html as the main file.
2. I created a public GitHub repository named spendwiseweek7 and pushed all files to it.
3. I logged into Netlify and selected Import from GitHub, then chose spendwiseweek7.
4. I left build settings as default for a static site - Build command: empty, Publish directory: root folder.
5. I clicked Deploy and Netlify published the site at https://spendwiseweek7.netlify.app
6. I tested the live site by setting a budget of KES 8005 and adding KES 2000 for Rent. It correctly showed Total Spent: KES 2000 and Balance: KES 6005.
7. I updated the README on GitHub and confirmed Netlify automatically redeployed the site.

## Challenges Encountered During Deployment
- Site showed KES 0 after typing budget: At first Total Budget stayed at KES 0 after typing 8005. I realised I had not clicked the Set Budget button yet. After clicking it, it updated correctly.
- Confusion between Netlify Private vs GitHub Public: Netlify first showed Private which worried me. I learned the important thing is that the GitHub repo is Public and the Netlify link is live.
- Understanding auto-deployment: I tested it by editing the README and checking Netlify - it redeployed automatically.

## Lessons Learned
- A website is not finished until it is deployed and tested live, not just working on my laptop.
- Connecting GitHub to Netlify saves time because every push updates the live site.
- Testing is important - testing Set Budget, Add Expense, Delete, and Clear All proved the logic works.
- A good README explains what the project does and how it was deployed, not just the code.
