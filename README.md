# FleaMart

A mock e-commerce platform built for school businesses to manage products, track deliveries, and interact with customers built as a group project with three other team members.

<!-- ## Demo -->

<!-- Add your video demo here — see the note below for how to embed it -->

## About

FleaMart provides two sides to the same platform:

- **Vendor side:** manage product listings and track deliveries for a school business.
- **Customer side:** sign up or log in, browse available products, and place orders.

The application was built in **NetBeans IDE**, using its drag-and-drop GUI builder for the interface, with **MySQL** as the backing database.

## Tech Stack

- **Language:** Java
- **IDE / GUI Builder:** NetBeans (Swing GUI, built via drag-and-drop)
- **Database:** MySQL
- **DB Connectivity:** JDBC, via the MySQL Connector/J driver

## Getting Started

### Prerequisites

- [NetBeans IDE](https://netbeans.apache.org/) (any recent version with Java support)
- A running MySQL server
- MySQL Connector/J (JDBC driver)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/WTavasi/FleaMart.git
   ```
2. Unzip `FleaMart.zip`, found in the repository root, to extract the actual NetBeans project source.
3. Open the extracted project folder in NetBeans (`File > Open Project`).
4. Set up a MySQL database matching the schema the application expects, and update the connection details (host, database name, username, password) in the project's database config to point to your local MySQL instance.
5. Add the MySQL Connector/J JDBC driver to the project's libraries in NetBeans if it isn't already resolved (`Project Properties > Libraries > Add Library / Add JAR/Folder`).
6. Build and run the project from NetBeans.

> **Note:** The JDBC driver jar is not tracked in this repository — it's a build dependency rather than source code. Download the appropriate MySQL Connector/J version separately if your local build doesn't already resolve it.

## Contributors

Built collaboratively with three other team members as a group project.
