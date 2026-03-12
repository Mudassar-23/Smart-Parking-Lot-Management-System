
# 🚗 Smart Parking Lot Management System 
A simple console-based Smart Parking Lot Management System implemented in Python.
This program simulates a parking lot where vehicles can be parked, removed, and monitored using Python data structures such as tuples, dictionaries, lists, and functions.

The system manages 5 parking slots (s1–s5) and tracks vehicle entries.


## Features

- Park a vehicle in an available slot
- Remove a vehicle from a slot
- Display current parking slot status
- Show parking summary (name, slots, vehicles parked)
- Track vehicle numbers entering the parking lot
- Menu-driven console interface




## 🧠 Data Structures Used

### 1️⃣ Tuple – Parking Information

Stores fixed information about the parking lot.

```bash
  parking_info = ("Fast Parking", 5)
```
- parking_info[0] → Parking Name
- parking_info[1] → Total number of slots
    
### 2️⃣ Dictionary – Parking Slots

Stores the status of each parking slot.
```bash
parking_slots = {
    's1': "empty",
    's2': "empty",
    's3': "empty",
    's4': "empty",
    's5': "empty"
}   
```
### 3️⃣ List – Vehicle Numbers

Stores all vehicle numbers that enter the parking lot.
```bash
vehicleslist = []
```
#### Example:

['ABC-678', 'LEA-452']




## ⚙️ Installation

#### Clone the project

```bash
  git clone https://github.com/Mudassar-23/smart-parking-system.git
```

#### Go to the project directory

```bash
  cd smart-parking-system
```

#### Ensure Python is Installed

```bash
  python --version
```

