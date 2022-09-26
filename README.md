# Frontend Assessment

Build and deploy a very simple frontend app for paginated data, that does the following

1.  Fetches data from this [Postman Collection](https://www.getpostman.com/collections/823aff8bea948faf3d90) which can be paged by appending `&page=N&page_size=P` where N is the page you want to fetch and P is the page size of data. E.g appending `&page=1&page_size=10` retrieves the first page and 10 results, while `&page=4&page_size=20` retrieves the 4th page with 20 results.

2.  Displays the fetched data in a HTML table and allows the user to page next/previous with buttons in the UI

3.  Name, Email, Phone, Department, DOB are the available table heads and corresponding rows to be shown.

4.  Implement edit and delete buttons for each row. Use a modal for editing of (name, email and DOB)

5.  BONUS. Add a search input at the top of the table for server searching (optional)

#### Note

1.  You are to build this project with [Ant Design](https://ng.ant.design/) for handing the styling or UI. 
2.  This project duration is 1(One) Hour.

