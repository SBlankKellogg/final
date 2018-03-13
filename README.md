# Final Project (Project #3)
### KIEI-924 Winter 2018

Design and build your own mobile company MVP. The subject matter is completely up to you; it can be as simple or as complex as you like. You will not be graded on the viability of your idea – only the execution – but get creative!

Any idea that fits into the "to-do list" or "voting" paradigm will work for this assignment. Examples:

- To-do list or one of the many derivatives (tacos to try, movies to watch)
- Shopping list or similar
- "Reddit" style app

**Back-end database using Airtable (9 points)**

1. If you haven't already, sign-up for a free account at Airtable (airtable.com).
2. After creating an account, click the "Account" icon in the upper-right corner, and choose the "Account" menu option. Generate a new API key – you'll need this to access the Airtable API.
3. Databases in Airtable are called "bases"; create a new base by clicking "Add a base". Call it whatever you want.
4. Create your data (use a single table only) following these guidelines:
  - Field names in lowercase
  - The "field type" should reflect what the data actually is; if it's numeric, make it a Number, if it's a date, make it a Date, etc.
5. A new table is named Table 1, 2, 3, etc. by default. Give it an actual name (e.g. ideas) by clicking on the drop-down next to the table on the tab on top.
6. Use the "Help" menu -> API documentation to see the automatically generated API documentation for your database!

**Mobile application using React Native (9 points)**

1. Create a new React Native application in your code folder. Name it `final`.

`create-react-native-app final`

2. Add the NativeBase UI framework - https://nativebase.io/

`yarn add native-base`

3. Add your newly created `final` project to GitHub.

4. Build your application. Using this project – https://github.com/kiei924-winter18/stinder-native – as a guideline, It should implement functionality that includes:
  - Retrieves all data from your Airtable back-end
  - Upvotes AND/OR deletes individual records. 

*Feel free to use any NativeBase components you want, beyond the ones already used in the sample project. This is completely optional though – a React Native project that looks and behaves like the sample project is sufficient for full credit on this assignment.*

**Submit your project (2 points)**

1. Hit the "Publish" button in XDE. You may be prompted to make your project publicly accessible; say yes.
2. Wait for it to build your project (this takes a while). If successful, it will yield a URL – something like: "Published to https://exp.host/@eng/stinder-native". Replace the contents of the `README.md` file in the root of your project with this URL.
3. Commit and sync your project to GitHub; if successful, it should live at `https://github.com/your-username/final`
