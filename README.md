# VB.NET-Lib - POS for .NET  
Point of Sale (POS) Library for .NET with Easy Integration for Retail and Transaction Systems

---

## 📦 What It Is

This is a **flexible and easy-to-integrate Point of Sale (POS) library** for .NET, designed for retail and transaction systems. It provides essential functionality to manage sales, products, and transactions in a customizable way, including:

- Sales transactions (sale, refund, partial payment)
- Inventory management
- Receipt generation
- Payment gateway integration

---

## 🚀 Features

✅ **Transaction management** (sale, refund, partial payments)  
✅ **Inventory tracking** with product quantities and pricing  
✅ **Receipt generation** in customizable formats  
✅ **Payment gateway integration** for credit/debit card processing  
✅ **Easy integration** into any .NET-based application  
✅ Built-in **error handling** for seamless operations  
✅ Supports both **cash** and **digital payment** methods  

---

## 🧰 What’s Included

### `POSController.vb` (Class)
- Handles all core POS functions (sales, refunds, partial payments)  
- Manages product data, pricing, and discounts  
- Supports receipt printing and export  

### `POSProduct.vb` (Class)
- Manages product data including SKU, name, description, and price  
- Tracks stock levels and updates inventory  
- Supports barcode generation and scanning  

### `PaymentGateway.vb` (Class)
- Integration with popular payment gateways (e.g., Stripe, PayPal)  
- Handles card transactions and payment confirmations  

---

## 🧩 Use Cases

- Retail point-of-sale systems  
- Small business transaction management  
- Inventory tracking and management  
- Customizable POS for kiosks, mobile apps, or in-store applications  

---

## ⚙️ Requirements

- **.NET Framework 4.5.1 or higher**  
- **VB.Net-based application**  
- Visual Studio 2015 or later recommended  

---

## 🔌 Getting Started

1. Add `POSController.vb`, `POSProduct.vb`, and `PaymentGateway.vb` to your project.

2. Initialize the POS controller:

   ```vb
   Dim pos As New POSController()
