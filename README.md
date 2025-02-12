# 📱 Bluetooth Control App using MIT App Inventor

![Bluetooth App Banner](assets/bluetooth_app_banner.gif)

## 🚀 Procedure for Creating the Bluetooth Control App

### 🛠 **Step 1: Setup MIT App Inventor**
1️⃣ Open **[MIT App Inventor](https://ai2.appinventor.mit.edu/)** in your browser.  
2️⃣ Click **"Create Apps"** and **sign in** with your Google account.  
3️⃣ Click **"Start a new project"**, name it (e.g., `BluetoothControlApp`), and click **OK**.  

---

### 🎨 **Step 2: Design the App Layout (UI)**
📌 **Add UI Components** from the **Palette**:
- 🖲 Add a **Toggle Button** for switching modes.
- 🖲 **Buttons** (Connect)
- 🏷 **Labels** (for displaying status)
- 📜 **ListPicker** (for selecting Bluetooth devices)
- 🔤 **TextBox** (optional, for custom commands)

📌 **Organize Components** using:
- 📏 **Horizontal Arrangement** (for button groups)
- 📐 **Vertical Arrangement** (for status and controls)
- 📊 **Table Arrangement** (for structured layout)

🖼 **App Layout Example:**
```plaintext
---------------------------------
|  Bluetooth Device Picker ⚡️   |
---------------------------------
|  Connect Button 🔗           |
---------------------------------
|  ON Button  | OFF Button  🔘 |
---------------------------------
|  Status Label 📡             |
---------------------------------
```

---

### 📡 **Step 3: Add Bluetooth Functionality**
🔹 **Drag & Drop** `BluetoothClient` from **Connectivity** into the Viewer.  
🔹 Use **ListPicker** to scan and select paired Bluetooth devices.  
🔹 Add logic to **Connect / Disconnect** to the selected device.

---

### 🧩 **Step 4: Implement the App Logic (Blocks)**
🛠 Open the **Blocks** section and implement:

✅ **Bluetooth Connection Initialization** when the app starts.
✅ **ListPicker Selection** to show available devices.
✅ **Button Actions (ON/OFF/TOGGLE)** sending predefined commands.
✅ **Real-time Feedback** using `BluetoothClient.ReceiveText`.

📌 **Example Block Code:**
```plaintext
When ListPicker1.AfterPicking
   If BluetoothClient1.Connect(ListPicker1.Selection)
      Set Label_Status.Text to "Connected ✅"
   Else
      Set Label_Status.Text to "Failed to Connect ❌"
```

---

### 🧪 **Step 5: Test & Debug the App**
1️⃣ Install **MIT AI2 Companion** on your Android phone.  
2️⃣ Scan the **QR Code** or enter the code to test the app in real-time.  
3️⃣ Debug **Bluetooth connection issues** and verify ESP32 communication.  

---

### 📦 **Step 6: Export & Install the App**
📤 Click **"Build"** → **"Android App (.apk)"**.  
📥 Download & install the app on your **Android device**.  

---


## 🎥 **Demo & Tutorial**
![App Demo](assets/bluetooth_app_demo.gif)

🎬 Watch on **YouTube**: [![YouTube](https://cdn-icons-png.flaticon.com/512/1384/1384060.png)](https://www.youtube.com/@salmanarefinsardar)

---

## 📫 **Let's Connect!**

<p align="left">
<a href="https://www.linkedin.com/in/salman151397">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="40" height="40">
</a>
<span style="display:inline-block; width: 250px;"></span>
<a href="https://www.youtube.com/@SalmanArefinSardar">
    <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" width="40" height="40">
</a>
<span style="display:inline-block; width: 250px;"></span>
<a href="mailto:salman151397@gmail.com">
    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="40" height="40">
</a>
</p>

[![GitHub Stars](https://img.shields.io/github/stars/salman1397/Bluetooth_App.svg?style=social)](https://github.com/salman1397/Bluetooth_App_Development)
