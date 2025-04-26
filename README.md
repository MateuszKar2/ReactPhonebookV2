# PhonebookAppV2

**PhonebookAppV2** is an enhanced version of a simple phonebook application built with React. This application allows users to manage their contacts, add new entries, search for contacts, and edit or delete existing ones. It introduces additional features like local storage for data persistence, improved user interface, and enhanced search and filter capabilities.

## Features

- **Add New Contacts**: Easily add new contacts with a name and phone number.
- **Edit Contacts**: Update existing contact details such as name and phone number.
- **Delete Contacts**: Remove contacts from the phonebook.
- **Search & Filter**: Search contacts by name and filter results in real time.
- **Local Storage**: Store contacts in the browser's local storage to persist data even after a page refresh.
- **Responsive UI**: Optimized for use on both desktop and mobile devices.

## Technologies Used

- **React (v17+)**: A JavaScript library for building user interfaces.
- **JSX**: Syntax extension for writing HTML-like code in JavaScript.
- **CSS**: Styling for the application to ensure a responsive and modern look.
- **React Hooks**: Utilizing `useState`, `useEffect`, and other hooks for state management and lifecycle methods.
- **localStorage**: Storing data in the browser to persist contacts across sessions.

## Components

- **AddContactForm**: Form to add new contacts to the phonebook.
- **EditContactForm**: Form to edit existing contact details.
- **ContactList**: Displays the list of contacts.
- **ContactItem**: Represents each individual contact in the list.
- **SearchBar**: Search bar to filter contacts by name.


# Comparison: PhonebookApp vs PhonebookAppV2

Below is a comparison between the first version of the phonebook application (**PhonebookApp**) and the enhanced version (**PhonebookAppV2**), highlighting the key differences and new features introduced in the second version.

| **Feature**                    | **PhonebookApp (v1)**                                      | **PhonebookAppV2 (v2)**                                       |
|---------------------------------|------------------------------------------------------------|---------------------------------------------------------------|
| **Adding Contacts**             | Allows adding new contacts                                 | Same functionality, but with additional features like editing and searching |
| **Editing Contacts**            | No editing functionality                                   | Ability to edit existing contacts (edit form)                 |
| **Deleting Contacts**           | Allows deleting individual contacts                        | Same functionality, with the ability to delete multiple contacts at once |
| **Filtering and Searching**     | Simple search by name (if entered)                         | Real-time search with filtering by name and advanced sorting |
| **Local Storage**               | No local storage (data is lost after page refresh)         | Contacts stored in `localStorage` to persist data across sessions |
| **Data Validation**             | No form validation (no checks for data correctness)        | Form validation added, checking phone number format and required fields |
| **Responsiveness**              | Basic responsiveness for different resolutions             | Enhanced responsiveness, optimized for both mobile and desktop devices |
| **UI / UX**                     | Basic user interface                                       | Improved UI with better UX, dynamic forms, enhanced styling |
| **Data Persistence Between Sessions** | No (data is lost on refresh)                             | Data persisted in `localStorage`, no need to re-enter contacts after refresh |
| **Components**                   | Basic components for the form and contact list             | Additional components for editing contacts and searching, better code organization |
| **User Instructions (README)**  | Basic instructions without details                         | More detailed instructions with new features and version 2 changes |

### Key Differences and New Features in Version 2:
- **Editing Contacts**: Added the ability to edit existing contacts, which was not available in version 1.
- **Local Storage**: Introduced `localStorage` to store contacts, ensuring persistence even after page refreshes.
- **Form Validation**: Added form validation, preventing incorrect data input (e.g., phone number format).
- **Advanced Filtering and Searching**: Introduced live search and advanced filtering options.
- **UI and Responsiveness**: Improved user interface and responsiveness for both mobile and desktop devices.
- **User Instructions**: README has been enhanced with more detailed instructions on how to use the app and the new features introduced in version 2.

### Summary:
**PhonebookAppV2** is an enhanced version of the application, adding several new features such as contact editing, validation, filtering, and data persistence, making it more functional and user-friendly compared to the original **PhonebookApp** version.
