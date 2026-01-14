# VB.NET-Lib - POS for .NET  
Point of Sale (POS) Library for .NET with Easy Integration for Retail and Transaction Systems.
Seamless interaction with OPOS devices using POS for .NET library. 
can run silently in the background like a service. 

BONUS FEATURE
can run a local WebSocket server to expose OPOS devices to a web application! no longer are you locked in to out-dated UI libraries! 


---

## 📦 What It Is

This library provides an **easy-to-integrate POS (Point of Sale)** solution for .NET, specifically designed to interact with **OPOS devices** (like receipt printers, barcode scanners, etc.) through the **POSfor.NET** library. 

It introduces a unique feature to **expose POS peripherals to a web application** via a **WebSocket server**, something that's traditionally difficult or impossible with web technologies. 

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

### `POSController.vb` (Class)
- Handles all core POS functions (sales, refunds, partial payments)  
- Manages interactions with OPOS devices via POSfor.NET library  
- Supports **real-time WebSocket communication** for device access  

### `OPOSDeviceManager.vb` (Class)
- Encapsulates the POSfor.NET library for interacting with OPOS peripherals (e.g., printers, scanners)  
- Manages peripheral operations and device statuses

### `WebSocketServer.vb` (Class)
- Exposes OPOS device operations via **WebSocket**, enabling real-time communication with web applications  
- Supports bidirectional data flow for device statuses, actions, and updates  

### `MiniWebApp.vb` (Web Interface)
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

- **.NET Framework 4.5.1 or higher**  
- **VB.Net-based application**  
- Visual Studio 2015 or later recommended  
- POSfor.NET library (for interacting with OPOS devices)  

---
