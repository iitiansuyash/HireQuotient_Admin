# Admin UI HireQuotient

This project is a web-based user interface for administrators to manage users. The UI is designed to meet specific requirements, providing functionalities such as viewing, filtering, editing, deleting, and selecting users with ease.

## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Deployment](#deployment)
- [API Endpoint](#api-endpoint)
- [Screenshots](#screenshots)
- [Contributing](#contributing)

## Demo
Visit the live demo [here](https://hire-quotient-admin.vercel.app/)

## Features
1. **Column Titles Stand Out**: The column titles are designed to stand out from the entries, ensuring clarity and easy identification.

2. **Search Bar**: A search bar allows administrators to filter users based on any property, providing a quick and efficient way to find specific records.

3. **Edit and Delete In Place**: Users can be edited or deleted in place. Note that these changes are only in memory and not persistent.

4. **Pagination**: The interface implements pagination with 10 rows per page. Buttons for the first page, previous page, next page, last page, and specific page numbers are provided. Pagination dynamically updates based on search/filtering results.

5. **Row Selection**: Users can select one or more rows. Selected rows are highlighted with a grayish background color. Multiple selected rows can be deleted simultaneously using the 'Delete Selected' button at the bottom left side.

6. **Checkbox Shortcut**: A checkbox at the top left provides a shortcut to select or deselect all displayed rows on the current page, not affecting all records.

7. **Search Box Placeholder Text**: The search box has a placeholder text starting with "Search" for user guidance.

8. **Search Icon/Button**: Users can trigger a search by clicking the search icon.

9. **Action Elements**: Action elements, such as edit, delete, and save, are implemented as buttons with specific class names for easy styling and customization.

10. **Navigation Elements**: Navigation elements are designed as div/buttons with class names first-page, previous-page, next-page, last-page, and specific page numbers.

11. **Inline Editing**: Clicking on the 'Edit' action in a row enables inline editing within the row itself.

## Getting Started
1. Clone this repository to your local machine.
2. Install dependencies using `npm install`.
3. Run the development server using `npm start`.
4. Open the application in your web browser at `http://localhost:3000`.

## Dependencies
This project utilizes the following libraries:
- React
- Axios
- Prop-types

## Usage
1. Access the deployed application.
2. Explore the user interface and functionalities described above.
3. Perform actions such as searching, editing, deleting, and selecting users.

## Deployment
The application is deployed on Vercel. Visit [deployed URL](https://hire-quotient-admin.vercel.app/) to access the live demo.

## API Endpoint
The user data is retrieved from the following API endpoint:
- **Request Type:** GET
- **Endpoint:** https://geektrust.s3-ap-southeast-1.amazonaws.com/adminui-problem/members.json

## Screenshots
![Screenshot 5](/public/5.png)
![Screenshot 1](/public/1live.png)
![Screenshot 2](/public/2.png)
![Screenshot 3](/public/3.png)
![Screenshot 4](/public/4.png)

## Contributing
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.
