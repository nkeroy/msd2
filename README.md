# msd2
Activity List Scenario 2

App.js can be found by src > js > components > app > App.js

There are total of 5 components in this application:
(1) App
(2) Form
(3) ActivityList
(4) Activity
(5) EditableFieldBox (not implemented)

(1) App functions by initialising Form on left hand side of page, and initialising ActivityList on right hand side of page.

(2) Form component allows user to input title, description and date, with a confirmation button to create the Activity component once details are confirmed. The Activity Component will then be added to the ActivityList.

(3) ActivityList component holds all the Activity components which are created.

(4) Activity component has title, description and date. There's also a delete button to remove the Activity from the ActivityList.

(5) EditableFieldBox component is not yet implemented, however it's supposed to allow user to edit title, description and date of Activity by clicking on the component itself. So every EditableFieldBox maps to a title/description/etc of the Activity. 

For addition/deletion of Activity component from the ActivityList, the rootReducer (part of Redux) is responsible (src > js > reducers > index.js > rootReducer).
