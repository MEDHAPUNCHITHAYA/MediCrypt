### **📄 Hospital File Exchange System**
A secure web-based system for hospitals to enable doctors to exchange patient files securely using encryption and OpenStack containers.

## **🚀 Features**
- **Doctor Authentication:** Secure login system for doctors.
- **File Upload & Management:** Doctors can upload files to their OpenStack containers.
- **Secure File Transfer:** Files are encrypted before transfer and decrypted upon receipt.
- **File Requests:** Doctors can request files from other doctors.
- **Role-Based Access:** Each doctor can only access their own files unless shared.

## **🔒 Security Features**
- **AES Encryption:** Files are encrypted before transfer.
- **Diffie-Hellman Key Exchange:** Secure key sharing for decryption.
 
## **🛠️ Technologies Used**
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Django (Python)
- **Database:** SQLite (Django default)
- **Cloud Storage:** OpenStack Swift
- **Encryption:** AES with PBKDF2 key derivation

## **⚙️ Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Misbhaaa/HospitalFileExchange.git
cd HospitalFileExchange
```

### **2️⃣ Set Up a Virtual Environment**
```bash
python3 -m venv venv
source venv/bin/activate  # (Linux/Mac)
venv\Scripts\activate  # (Windows)
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **4️⃣ Set Up OpenStack Connection**
Ensure OpenStack is configured by sourcing the authentication file:
```bash
source ~/devstack/openrc admin admin
```

### **5️⃣ Run the Django Server**
```bash
python manage.py runserver
```
Now, visit **http://127.0.0.1:8000/** to access the system.


## **📝 License**
This project is open-source and available under the **MIT License**.

