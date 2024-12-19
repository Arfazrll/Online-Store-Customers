# 📚 Online Store And Customers Application

**Online Store Application** is a C++ program designed to simulate an online store system. It allows users to manage customers, products, and their relationships efficiently through interactive menus. The program provides hands-on learning for managing data structures and relational operations in real-world scenarios. 🚀

---

## ✨ Key Features

- **💼 Customer Management**  
  Add, update, or delete customer data with ease.

- **🛒 Product Management**  
  Maintain a product catalog, including adding, deleting, and updating product details.

- **🔗 Relational Data Management**  
  Link customers to their purchased products, view relationships, and explore connections between entities.

- **📊 Analytical Insights**  
  Generate and display reports on customer activity and product purchases.

- **⚙️ Dynamic Data Structures**  
  Uses linked lists for managing users, products, and their connections effectively.

---

## 🛠️ Technologies Used

- **C++**: The core language for the application.
- **Linked Lists**: For managing dynamic data relationships.
- **Text Files**: To store data persistently across sessions.
- **Terminal-based Interface**: For an intuitive and user-friendly interaction.

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/Arfarzll/Online-Store-And-Customers.git
cd Online-Store-And-Customers
```

### 2. Compile the Program

Use a C++ compiler like GCC to build the application:

```bash
g++ -o OnlineStore main.cpp SourceFile.cpp
./OnlineStore
```

### 3. Run the Program

Follow the on-screen prompts to navigate through the menu and perform various operations, such as managing users, products, and transactions.

---

## 🔌 Program Functionalities

### Interactive Menu Options

1. Add new users or products.
2. Link products to customers.
3. Display users, products, or their relationships.
4. Generate analytical reports on sales and user activity.
5. Update or delete existing data.
6. Explore specific relationships between users and products.

---

## 📂 File Structure

- **`main.cpp`**: Handles the program’s interactive menu and user input.
- **`SourceFile.cpp`**: Contains the core functions for managing users, products, and relationships.
- **`Header.h`**: Declares data structures, constants, and function prototypes.
- **`User & Barang.txt`**: Stores data for persistence between sessions.
- **`.gitignore`**: Ensures unnecessary files are excluded from version control.

---

## 📊 Example Data Usage

### Operations and Examples

- **Add a User**: Insert user details like ID, name, and location into the linked list.
  ```cpp
  User user = {1, "John Doe", "New York"};
  insertFirstUser(userList, createElmUser(user));
  ```
- **Add a Product**: Add product details such as ID, name, and type into the catalog.
  ```cpp
  Product product = {101, "Laptop", "Electronics"};
  insertLastBarang(productList, createElmBarang(product));
  ```
- **Link User and Product**: Connect a user with a product to simulate a purchase.
  ```cpp
  connect(relasiList, findUser(userList, 1), findBarang(productList, 101), createElmRelasi());
  ```
- **View Relationships**: Display all purchases made by users.
  ```cpp
  showInfoRelation(userList, productList, relasiList);
  ```
- **Generate Reports**: Count and display users who bought a specific product.
  ```cpp
  int count = countJumlahParentFromSpecificChild(relasiList, 101);
  cout << "Number of users who bought product 101: " << count << endl;
  ```

---

## 📝 Conclusion

**Online Store Application** simplifies understanding data structures and their practical applications. By integrating linked lists and relational operations, this project provides valuable experience in solving real-world problems programmatically. With an intuitive menu and robust functionalities, it’s an excellent learning tool for developers and students alike.

---
