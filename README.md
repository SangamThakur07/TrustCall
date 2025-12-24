# SYS-call-interface-
its a userfriendly system call interface 
🔐 TrustCall
User-Friendly System Call Interface for Enhanced Security

TrustCall is a simple Operating System project that provides a secure and easy way to access system calls.
It improves OS security by adding authentication, access control, and logging.

🚀 Features ==>

Secure user authentication

Role-based access control

Activity logging

Simple command-based interface

🛠 Tech Stack ==>

C / C++

Linux

System Calls

📌 Purpose==>

This project helps in understanding OS internals, system calls, and security mechanisms.

🔮 Future Scope ==>

More system calls

GUI interface

Improved security


📖 Detailed Explanation

In modern operating systems, system calls are the only controlled way through which user-level programs can request services from the kernel. These services include file operations, process management, memory allocation, and inter-process communication. While system calls are powerful, they can also become a security risk if misused or accessed without proper control.

The TrustCall project is designed to address this problem by introducing a user-friendly and secure system call interface. Instead of allowing direct and unrestricted access to system calls, TrustCall acts as a protective layer between the user and the operating system kernel.

🔐 Security Aspect

TrustCall enforces authentication before executing any system call. Only verified users are allowed to proceed. Once authenticated, the system checks the user’s role and permissions using role-based access control (RBAC). This ensures that sensitive system calls are accessible only to authorized users, reducing the risk of unauthorized access and malicious activity.

🧑‍💻 Usability Aspect

Traditional system calls can be complex and difficult for beginners to use correctly. TrustCall simplifies this by providing a command-based interface that abstracts low-level details. Users can interact with the operating system in a more intuitive and structured way without directly handling kernel-level complexities.

📋 Logging and Monitoring

Every system call executed through TrustCall is recorded in a log file. These logs help in monitoring system activities, detecting suspicious behavior, and performing audits. Logging is an essential security feature as it provides accountability and traceability of user actions.

⚙️ Working Flow

The user interacts with the TrustCall interface.

Authentication verifies the user’s identity.

Access control validates permissions.

The requested system call is executed safely.

The activity is logged for future reference.

🎓 Learning Outcomes

This project helped in understanding:

How system calls work internally

The importance of security in OS design

Access control mechanisms

Practical implementation of OS-level concepts






👤 Author ==>

Sangam Thakur
GitHub: https://github.com/SangamThakur07
