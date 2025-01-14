# nextjs-dashboard
The App is like the main playroom where all the action happens. Its where the LEGO sets are divided into smallar parts.

- dashboard is a section of the app. Think of it like a room in the hous, it has the dashboard, where you can see things like recent activities or numbers
    Customers: this room has files to show details about customers
    Invoices: this part shows the Invoices, like a list of bills or receipts

- Layout.tsx: has the lego base, where all my pieces sits. It decides how the rooms (pages) look, like walls, flooors, ceilings.
- page.tsx: has the welcome sign at the enterance. Its the first thing you see when you open the app. 
- loading.tsx: if something takes time to load, this file makes sure you see a spinning wheel or a "wait a moment" message

2. Lib 
 - data.ts: a file that holds impotant facts. like numbers or name, its like a big book of information
 - utils.ts: a file with little helpers that do smart things for the app, like sorting a list or fixing errors.

 3. query: this is the messengers in my LEGO world, they go outside, grab data from somewhere and bring it back to the app

 4. seed: this is like planting seeds in a garden. Its where i can put informations to grow my app

 5. Ui
    This is my decoration box. It has all the pretty lego pieces, like buttons, forms, tables and chats - each file add something useful to the app
    - dashboard: its where we make dashboard look cool, like charts
    - invoices: pieces that make the invoices works, like buttons
