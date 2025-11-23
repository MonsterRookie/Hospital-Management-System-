# Hospital Management System (Java – Console Application)

A **console-based Hospital Management System** developed using **pure Core Java**.  
Runs completely in **CMD / Terminal**, uses **file storage**, and features **auto-increment ID generation**.

---

## Features

### **1. Patient Management**
- Add new patient  
- View all patients  
- Search patient  
- Auto-generated patient IDs  
- Data saved in `patients.txt`

### **2. Doctor Management**
- Add doctor  
- View doctors  
- Auto-generated doctor IDs  

### **3. Appointment Management**
- Book appointments  
- View all appointments  
- Auto-generated appointment IDs  
- Data saved in `appointments.txt`

### **4. Medical Records**
- Add medical records  
- View records  
- Auto-generated record IDs  

### **5. Billing**
- Generate patient bills  
- View bills  
- Auto-generated bill IDs  

---

## 📁 Project Structure

```text
Hospital-Management/
│
├── Main.java
├── Utils.java
│
├── Patient.java
├── Doctor.java
├── Appointment.java
├── MedicalRecord.java
├── Bill.java
│
├── PatientService.java
├── DoctorService.java
├── AppointmentService.java
├── MedicalRecordService.java
├── BillingService.java
│
├── patients.txt
├── doctors.txt
├── appointments.txt
├── records.txt
└── bills.txt
```
---

## 🧠 OOP Concepts Used

- Class & Object  
- Constructors  
- Encapsulation  
- Modular OOP architecture  
- Service Layer pattern  
- File Handling (I/O Streams)  
- Auto-ID generator
