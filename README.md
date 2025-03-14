# AZURE-Network-Setup

## **Project Overview**
This project focuses on setting up an **Azure Virtual Machine (VM)** using a free-tier Azure account. The goal is to create a functional cloud-based Windows Server with essential network and storage configurations. All resources are managed under a single **Resource Group**, ensuring proper organization and easy cleanup.

---

## **Steps Followed**

### **1. Created a Resource Group**
- Set up a **Resource Group** to keep all resources organized.

### **2. Configured a Virtual Network**
- Created a **Virtual Network** with a **default subnet** to allow communication between resources.

### **3. Deployed a Windows Virtual Machine**
- Selected a **free-tier eligible Windows Server**.
- Assigned a **Public IP** to enable RDP (Remote Desktop) access.
- Ensured the VM was placed inside the configured **Virtual Network**.

### **4. Added a Data Disk**
- Attached a **32 GB Data Disk** to the VM for additional storage.

### **5. Established RDP Connection**
- Used the assigned **Public IP Address** to connect to the VM via **Remote Desktop Protocol (RDP)**.

### **6. Captured Screenshots for Documentation**
- Screenshots include:
  - **VM Overview**
  - **Virtual Network Configuration**
  - **Attached Data Disk**
  - **Windows Server Desktop via RDP**

### **7. Deleted All Resources**
- Removed the **Resource Group** to avoid unnecessary charges and free up resources.

---

## **Included Files**
The following files are included in this repository:
- `VM_Overview.png` – Screenshot of VM configuration.
- `VNet_Configuration.png` – Virtual Network settings.
- `VM_Disk.png` – Data Disk attached.
- `Windows_Desktop.png` – Successfully connected via RDP.

This project successfully demonstrates a basic Azure VM deployment. 🚀
