# Shopping List Application

This is a full-stack shopping list application that allows users to manage their shopping items. The application is built with **Angular** for the front end and **Spring Boot** for the back end.

## Project Structure

- **Front End**: Located in the `shopping-list` folder, built using Angular.
- **Back End**: Located in the `shopping-spring` folder, built using Spring Boot.

## Features

### Front End (Angular)

- **View all shopping items**: Displays the complete list of items.
- **Add new items to the shopping list**: Allows users to add new items.
- **Edit existing items**: Update item details directly in the list.
- **Delete items from the list**: Remove items that are no longer needed.
- **Filter items by category**: Allows filtering items based on categories.
- **Mark items as purchased**: Track items that have been bought.

### Back End (Spring Boot)

- **RESTful API**: Manages shopping items and handles requests from the front end.
- **CRUD operations**: Supports Create, Read, Update, and Delete operations for shopping items.
- **Category Filtering Endpoint**: Filters items by category.
- **Update Purchased Status**: Allows updating of an item’s purchased status.

## Installation

### Clone the repository

```bash
git clone <repository-url>
cd <repository-name>

## Set up the Front End

1. **Navigate to the front-end directory**:

    ```bash
    cd shopping-list
    ```

2. **Install dependencies**:

    ```bash
    npm install
    ```

3. **Run the front end**:

    ```bash
    ng serve
    ```

   The front end will be available at [http://localhost:4200](http://localhost:4200).

## Set up the Back End

1. **Navigate to the back-end directory**:

    ```bash
    cd shopping-spring
    ```

2. **Run the Spring Boot application**:

    ```bash
    mvn spring-boot:run
    ```

   The back end will be available at [http://localhost:8080](http://localhost:8080).

