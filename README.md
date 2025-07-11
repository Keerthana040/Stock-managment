#  Stock Management 

 Stock Management is a web application designed to help manage warehouse and shop stock efficiently. The application provides features for searching, sorting, updating, and transferring stock items between the warehouse and shops. 



## Features & Usage

### User Authentication

- **Login/Logout**: Users can log in and log out of the application.
- **User Status**: Displays the logged-in user's status.

### Stock Management

- **Warehouse Stock**: View and manage items in the warehouse.
- **Shop Stock**: View items available in the shop.
- **Transfers Pending**: View and manage pending stock transfers.
- **Download Stock Data**: Both warehouse and shop stock data may be downloaded as an excel spreadsheet.
- **Upload Stock Data**: Both warehouse and shop stock data may be uploaded as an excel spreadsheet and ingested into the database.
- **Cusotmise Pagination**: Change displayed rows per table though the system admin page.

### Search and Sort

- **Search**: Search for items in the warehouse and shop by SKU, description, or other attributes.
- **Sort**: Sort items by SKU, description, retail price, or quantity. SKU field uses a natural sort algorithm.

### Warehouse Maintenance

- **Toggle Warehouse Maintenance Mode**: Managers can toggle 'maintenance mode', during which transfers by shop users are paused.
- **Add, Update & Delete Stock**: Managers can add new stock items, update stock item descriptions, retail prices, and quantities, and delete items. All updates occur immedately the field is edited - no need to click any additional buttons.

### Transfer Items

- **Transfer Items**: Shop users can request to transfer items from the warehouse to the shop by simply entering how many units they require into the input field. 
- **Email Notifications**: Email notifications may be activated, which sends an email to all warehouse managers in the 'receive_mail'.
- **Complete Transfers**


Warehouse manager login:

- Username: demo_manager
- Password: Gui7u6QxWEdZwq

Shop user login:

- Username: demo_shop_user
- Password: Gui7u6QxWEdZwq



### Warehouse manager's view


<img width="1318" height="1514" alt="warehouse" src="https://github.com/user-attachments/assets/6d474e45-e11d-47ee-9559-2015947d3af9" />







