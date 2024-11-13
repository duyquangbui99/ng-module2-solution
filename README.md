# Module 2 Solution - CheckOffList

## Overview
The **CheckOffList** is a shopping list management application built using **AngularJS (1.8.2)**. This app helps users keep track of items they need to buy by allowing them to "check off" items as they purchase them. Items move from a "To Buy" list to an "Already Bought" list once they are marked as bought. The application provides real-time updates and displays messages based on the state of each list.
## Technologies Used
- **HTML5**
- **CSS3**
- **AngularJS (1.8.2)**
- **JavaScript**

## Feature
Two Separate Lists:
 - To Buy: Initially populated with a set list of items, including names and quantities.
 - Already Bought: Initially empty, this list updates as items are bought from the "To Buy" list.
Real-Time List Management:
 - Each item in the "To Buy" list has a "Bought" button. Clicking this button moves the item to the "Already Bought" list.
 - Displays messages depending on the state of each list:
    - **If the "To Buy"** list is empty: Shows the message "Everything is bought!"
    - **If the "Already Bought"** list is empty: Shows the message "Nothing bought yet."
      
## Usage
- **View To Buy List**: The "To Buy" list shows items (e.g., 10 cookies) with a "Bought" button next to each.
- **Mark Item as Bought**:
      Click the "Bought" button next to an item to move it to the "Already Bought" list.
- **View Already Bought List**: Items you mark as bought will appear here, with the message "Nothing bought yet" disappearing once an item is added.

## Code Highlights

**Modular AngularJS Design**:
 - Separate Controllers for each list (ToBuyController and AlreadyBoughtController) to manage list-specific data and actions.
 - Service-Based Data Sharing with ShoppingListCheckOffService for managing item movement between lists and maintaining list state.
   
**Dynamic Directives**:
 - ng-if for conditional messages based on the list’s state.
 - ng-repeat to dynamically display items in each list.
 - ng-click to trigger item transfers from "To Buy" to "Already Bought".
<img width="896" alt="0" src="https://github.com/user-attachments/assets/23066b27-43c1-4a77-989a-893bd07f95ac">
<img width="881" alt="1" src="https://github.com/user-attachments/assets/9990faba-a37b-418c-b060-1076abe96181">
<img width="881" alt="2" src="https://github.com/user-attachments/assets/8b0d7e24-8fff-4974-ac82-499e86b78b2a">

## Author
Created by Quang Bui.

