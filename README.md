
#  Airport Surface Traffic Control System (ASTC)

## Overview
The **Airport Surface Traffic Control (ASTC)** project is a **Java-based simulation** designed to model and manage **ground operations at airports**.  
It simulates **aircraft movements**, **task scheduling**, **resource reservations**, and **shortest path calculations** between airport points, making it a practical platform for research and educational purposes.

---

## Features
- **Task Management**: Priority-based scheduling using a Task Engine with multi-threading.
- **Aircraft Simulation**: Landing, taxiing, and parking actions.
- **Ground Infrastructure**: Simulated **runways**, **taxiways**, and **gates** with reservation systems.
- **Network Links**: Manage occupied/available states for connections.
- **GUI**:
  - Login with password attempt lockout.
  - Plane data forms for starting/destination points.
  - Task details display.
- **Shortest Path Calculation**: Dijkstra’s Algorithm for optimal route planning.


---

## Setup Instructions

###  1. Clone the Repository
```bash
git clone https://github.com/your-username/Airport-Surface-Traffic-Control-System.git
cd Airport-Surface-Traffic-Control-System
````

---

###  2. Install Java

Make sure **Java JDK 8+** is installed.
Check your version:

```bash
java -version
```

If not installed, download it from: [Oracle Java Downloads](https://www.oracle.com/java/technologies/javase-downloads.html)

---

### 🛠 3. Open in IDE

* You can use **Eclipse**, **IntelliJ IDEA**, or **NetBeans**.
* Import the project as a **Java Project**.

---

###  4. Run the Application

* Locate the `Main.java` file (or the main GUI entry point).
* Run the program.
* The **Login Page** will appear.

---

###  5. Default Login

* **Username:** `admin` *(example — update if different)*
* **Password:** `1234` *(example — update if different)*

*(You can change login credentials in the Login class code.)*

---

## 📂 Project Structure

```
ASTC/
│
├── src/
│ ├── Airplane.java
│ ├── CurrentClock.java
│ ├── Gate.java
│ ├── GroundNetwork.java
│ ├── Link.java
│ ├── NetworkLink.java
│ ├── PathFinder.java
│ ├── Runway.java
│ ├── SystemClock.java
│ ├── SystemTime.java
│ ├── Task.java
│ ├── TaskDescription.java
│ ├── TaskEngine.java
│ ├── Tasks.java
│ ├── Taxiway.java
│ ├── Time.java
│ │
│ ├── GUI/
│ │ ├── LoginPage.java
│ │ ├── PlaneForm.java
│ │ ├── PlaneData.java
│ │ ├── DesiredAirplane.java
└── Project UML.pdf
└── README.md
```

---

## Flow Chart

<img width="975" height="541" alt="image" src="https://github.com/user-attachments/assets/431168dd-a32a-4c79-98d6-4a8dacf1eec9" />


---

##  Future Enhancements

* Integration of **weather conditions** for realistic simulation.
* Enhanced **aircraft movement algorithms**.
* Real-time **3D visualization** of ground operations.
* AI-powered **traffic optimization**.

---

