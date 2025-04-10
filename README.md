# Hotel Management System (Java + MySQL CLI)

A command-line based **Hotel Management System** built using **Java** and **MySQL**, designed to handle hotel room reservations with features to **create**, **view**, **update**, and **delete** reservations.

---

## 🚀 Features

- 🏨 **Room Reservation**: Add a new reservation by entering guest details.
- 📋 **View Reservations**: View all current reservations in a tabular format.
- 🔍 **Get Room Number**: Fetch room number using guest name and reservation ID.
- ✏️ **Update Reservation**: Modify an existing reservation’s details.
- ❌ **Delete Reservation**: Remove a reservation by ID.
- ✅ **Reservation Validation**: Ensures operations only proceed on valid entries.
- ⏳ **Graceful Exit**: Animated system exit for better UX.

---

## 🛠️ Tech Stack Used

| Layer       | Technology         |
|-------------|--------------------|
| Language    | Java (JDK 8+)      |
| Database    | MySQL              |
| Connector   | JDBC (MySQL Driver)|
| IDE         | IntelliJ / VS Code |

---

## 💾 Database Schema

### Database: `hotel_db`

#### Table: `reservation`
```sql
CREATE TABLE reservation (
  reservation_id INT AUTO_INCREMENT PRIMARY KEY,
  guest_name VARCHAR(100) NOT NULL,
  room_number INT NOT NULL,
  contact_number VARCHAR(15) NOT NULL,
  reservation_date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);


## 📂 How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/hotel-management-system.git
```

2. Import into your preferred Java IDE.

3. Set up your MySQL database and run the schema script above.

4. Make sure your `url`, `user`, and `password` in the Java file match your local MySQL setup.

5. Run the `Main` class.

---

## 📸 Demo
```bash
HOTEL MANAGEMENT SYSTEM

1. Reserve a Room
2. View Reservation
3. Get Room Number
4. Update Reservation
5. Delete Reservation
0. Exit
```


