# VB.NET-Lib - POS for .NET  
Point of Sale (POS) Library for .NET with Easy Integration for Retail and Transaction Systems. <Br>
Seamless interaction with OPOS devices using POS for .NET library. 
can run silently in the background like a service. 

BONUS FEATURE <br>
can run a local WebSocket server to expose OPOS devices to a web application! no longer are you locked in to out-dated UI libraries! 


---

## 📦 What It Is

This library provides an **easy-to-integrate POS (Point of Sale)** solution for .NET, specifically designed to interact with **OPOS devices** (like Cash Drawers, Magnetic Swipe Readers (MSR), etc.) through the **POSfor.NET** library. 

It introduces a unique feature to **expose POS peripherals to a web application** via a **WebSocket server**, 

Additionally, it runs silently in the background as a service, listening for device calls, while offering real-time bidirectional communication with web apps for device statuses and transactions.

---

## 🚀 Features

✅ **OPOS Device Integration** via **POSfor.NET** library (receipt printers, scanners, etc.)  
✅ **WebSocket Server** for real-time, bidirectional communication with web apps (no need for outdated UI)  
✅ Exposes device actions (e.g., printing, scanning) to a **modern web interface**  
✅ **MiniWebApp** included for testing OPOS devices over WebSocket in real-time  
✅ Fully **configurable settings** for device access and communication  
✅ Runs **silently as a background service** listening for device calls  
✅ **Real-time updates** for device status and activity via WebSocket  
✅ Easy to integrate into **any VB.NET project**, providing a simple interface to control complex hardware operations  

---

## 🧰 What’s Included

### `OPOSManager.vb` (Class)
- Manages interactions with OPOS devices via POSfor.NET library  
- Encapsulates the POSfor.NET library for interacting with OPOS peripherals (e.g., printers, scanners)  
- Manages peripheral operations and device statuses

### `OPOSWebSocketServer.vb` (Class)
- Exposes OPOS device operations via **WebSocket**, enabling real-time communication with web applications  
- Supports **real-time WebSocket communication** for device access  
- Supports bidirectional data flow for device statuses, actions, and updates

### `MiniWebApp.html` (sinlge-file HTML Web Application)
- A **built-in web app** to test and interact with OPOS devices over WebSocket  
- Includes simple device control UI for scanning, printing, etc.  

---

## 🧩 Use Cases

- **Retail POS systems** with web-based frontends  
- **Web-based inventory management** integrated with OPOS devices  
- **Web apps** that need to interact with hardware peripherals in real time  
- **Portable class** for seamless integration into **any VB.NET project** needing OPOS device support  
- Ideal for businesses seeking **modern UIs** while retaining legacy hardware support  

---

## ⚙️ Requirements

- **.NET Framework 4.7.2 or higher**  
- POSfor.NET library (for interacting with OPOS devices)  

---

<img width="834" height="606" alt="image" src="https://github.com/user-attachments/assets/f7387326-db11-4daa-860a-f9736a7bb9b0" />

settings: <br>
<img width="852" height="627" alt="image" src="https://github.com/user-attachments/assets/e9fc4fbe-3142-4b98-ac4f-0169b6860630" />


Open, Claim, and Enable Cash Drawer - then Kick it: <br>
<img width="1459" height="623" alt="image" src="https://github.com/user-attachments/assets/c719aca2-8a3a-4350-a7e1-1f2f724dad5a" />


Open, Claim, and Enable MSR (Magnetic Swipe Reader): <br>
<img width="1382" height="632" alt="image" src="https://github.com/user-attachments/assets/5969a8b7-7816-4cf0-a9b8-6c55ac0c122d" />

Start WebSocket Server: <br>
<img width="860" height="623" alt="image" src="https://github.com/user-attachments/assets/016c8a89-150a-47d2-9a83-e3b38eb56407" />

Launch Test Web App: <br>
<img width="1303" height="602" alt="image" src="https://github.com/user-attachments/assets/6e4d693f-14c9-44a9-826d-09a0894bd3f4" />

Web App connected to EPOS Core: <br>
<img width="1566" height="858" alt="image" src="https://github.com/user-attachments/assets/a4e8de52-afa9-4cba-ae3c-90795481481f" />




