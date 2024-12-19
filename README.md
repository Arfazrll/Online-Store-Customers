# 📚 Online Store Application

**Online Store Application** is a C++ program designed to simulate an online store system. It allows users to manage customers, products, and their relationships efficiently through interactive menus. The program provides hands-on learning for managing data structures and relational operations in real-world scenarios. 🚀

---

## ✨ Key Features

- **💼 Customer Management**  
  Add, update, or delete customer data with ease using linked list operations.

- **🛒 Product Management**  
  Manage product catalogs with support for insertion, deletion, and search operations.

- **🔗 Relational Data Management**  
  Establish relationships between users and products, enabling tracking of purchases and connections.

- **📊 Analytical Insights**  
  Generate insights such as the number of products purchased by a user or users associated with a product.

- **⚙️ Dynamic Data Structures**  
  Built with linked lists for managing users, products, and their connections effectively.

---

## 🛠️ Technologies Used

- **C++**: The programming language for the application.
- **Linked Lists**: The primary data structure for dynamic relationship management.
- **Text Files**: For persistent data storage.
- **Terminal-based Interface**: Simple and user-friendly for interaction.

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/Arfarzll/Online-Store-And-Customers.git
cd Online-Store-And-Customers
```

### 2. Compile the Program

Compile the program using a C++ compiler such as GCC:

```bash
g++ -o OnlineStore main.cpp SourceFile.cpp
./OnlineStore
```

### 3. Run the Program

The application provides an interactive menu with various operations. Follow the prompts to manage users, products, and their relationships.

---

## 🔌 Program Functionalities

### Menu Options

1. Add Users or Products.  
2. Display Users and Products.  
3. Link Users with Products (simulate purchases).  
4. View Relationships (purchases).  
5. Update or Delete Users/Products.  
6. Generate Reports: 
   - Count products bought by a user.
   - Identify users of a product.

---

## 📂 File Structure

- **`main.cpp`**: Manages the program's menu and interaction.
- **`SourceFile.cpp`**: Implements linked list operations and relational management.
- **`Header.h`**: Declares data structures, constants, and functions.
- **`User & Barang.txt`**: Stores persistent data for users and products.
- **`.gitignore`**: Configuration for ignoring unnecessary files.

---

## 📊 Example Code and Usage

### Adding a User

```cpp
infotypeUser newUser = {1, "Alice", "Jakarta"};
address_User user = createElmUser(newUser);
insertFirstUser(userList, user);
```

### Adding a Product

```cpp
infotypeBarang newProduct = {101, "Laptop", "Electronics"};
address_Barang product = createElmBarang(newProduct);
insertLastBarang(productList, product);
```

### Linking a User with a Product

```cpp
address_User user = findUser(userList, 1);
address_Barang product = findBarang(productList, 101);
address_Relasi relation = createElmRelasi();
connect(relationList, user, product, relation);
```

### Viewing Relationships

```cpp
showInfoRelation(userList, productList, relationList);
```

---

## 📝 Conclusion

The **Online Store Application** demonstrates the practical implementation of linked lists in managing dynamic data relationships. By incorporating relational management and analytical insights, it offers valuable experience for understanding data structures and their applications in solving real-world problems. This project is an excellent resource for learning and honing programming skills in C++.

---
