# 🔐 Password Cracking with John the Ripper Lab

> A hands-on cybersecurity laboratory focused on understanding password security and password recovery using John the Ripper (JTR) and Johnny GUI in a controlled and authorized Windows environment.

---

## 📌 Project Overview

This project documents my hands-on experience using **John the Ripper (JTR)** and **Johnny GUI** to recover the password of a protected PDF file in an authorized cybersecurity training environment.

The purpose of this lab was not simply to recover a password. It was designed to help me understand how password-protected files are processed, how password hashes can be prepared for password recovery tools, and why strong passwords are essential for protecting sensitive information.

During the exercise, I worked with a protected training PDF, prepared its password hash for analysis, and used John the Ripper through the Johnny graphical interface to perform the password recovery process.

This project forms part of my practical cybersecurity learning journey and focuses on developing foundational skills in:

* 🔐 Password security
* 🧩 Password hash preparation
* 🖥️ Windows-based cybersecurity tools
* 🛠️ John the Ripper
* 🖱️ Johnny GUI
* 📄 Password-protected document analysis
* 🧪 Controlled security testing
* 📝 Documentation and reporting

> ⚠️ **Ethical Use Notice:** All activities documented in this repository were performed as part of an authorized cybersecurity training exercise using a designated training file. Password recovery techniques should only be used on files, systems, and accounts that you own or have explicit permission to test.

---

# 🎯 Project Objectives

The main objectives of this project were to:

* Understand the purpose and functionality of John the Ripper.
* Explore the Johnny graphical interface for John the Ripper.
* Configure John the Ripper for use on a Windows system.
* Work with a password-protected PDF file in a controlled lab environment.
* Prepare a PDF password hash for password recovery.
* Load the prepared hash into Johnny.
* Perform a password recovery attack against the authorized training file.
* Recover and verify the password.
* Understand the relationship between password complexity and cracking difficulty.
* Develop practical documentation skills for cybersecurity projects.

---

# 🧰 Tools and Technologies

| Tool / Technology           | Purpose                                      |
| --------------------------- | -------------------------------------------- |
| 🪟 Windows PC               | Primary lab environment                      |
| 🔐 John the Ripper          | Password recovery and security testing tool  |
| 🖱️ Johnny                  | Graphical user interface for John the Ripper |
| 📄 Password-Protected PDF   | Authorized training target                   |
| 📝 Text Editor              | Used to save the extracted password hash     |
| 🔎 PDF Hash Extraction Tool | Used to prepare the PDF hash for analysis    |

---

# 🏗️ Laboratory Architecture

```text
                    ┌─────────────────────┐
                    │    Windows PC       │
                    │                     │
                    │  Cybersecurity Lab  │
                    └──────────┬──────────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │ Password-Protected PDF │
                  │   Authorized Target    │
                  └──────────┬─────────────┘
                             │
                             │ Hash Preparation
                             ▼
                  ┌────────────────────────┐
                  │     PDF Password Hash  │
                  │       hash1.txt        │
                  └──────────┬─────────────┘
                             │
                             ▼
                  ┌────────────────────────┐
                  │       Johnny GUI       │
                  │                        │
                  │  Graphical Interface   │
                  └──────────┬─────────────┘
                             │
                             ▼
                  ┌────────────────────────┐
                  │   John the Ripper      │
                  │                        │
                  │ Password Recovery Engine│
                  └──────────┬─────────────┘
                             │
                             ▼
                  ┌────────────────────────┐
                  │ Recovered Password     │
                  └──────────┬─────────────┘
                             │
                             ▼
                  ┌────────────────────────┐
                  │ Password Verification  │
                  │ Open Authorized PDF    │
                  └────────────────────────┘
```

---

# 📚 Understanding John the Ripper

**John the Ripper (JTR)** is a password security and password recovery tool commonly used in cybersecurity assessments, penetration testing, password auditing, and training laboratories.

It supports a wide range of password hash formats and can be used to test the strength of passwords protecting different systems and file types.

In this project, John the Ripper was used to analyze the password protection associated with an authorized PDF training file.

The exercise demonstrated an important cybersecurity principle:

> **The strength of a security control is heavily influenced by the strength of the password protecting it.**

Weak or predictable passwords may be recovered more easily, while long and complex passwords significantly increase the resources and time required for password recovery.

---

# 🖱️ Understanding Johnny

**Johnny** is a graphical user interface designed to make John the Ripper easier to use.

Instead of interacting entirely through the command line, Johnny provides a graphical environment where users can:

* Load password hash files.
* Select and configure attacks.
* Start and monitor password recovery attempts.
* View recovered passwords.
* Manage John the Ripper from a beginner-friendly interface.

For this project, Johnny was used as the primary interface for interacting with John the Ripper.

---

# 🧪 Lab Methodology

The project was completed using the following structured workflow:

```text
1. Prepare the Windows Lab Environment
              │
              ▼
2. Install John the Ripper
              │
              ▼
3. Install and Configure Johnny
              │
              ▼
4. Obtain the Authorized Protected PDF
              │
              ▼
5. Prepare the PDF Password Hash
              │
              ▼
6. Save the Hash to a Text File
              │
              ▼
7. Load the Hash into Johnny
              │
              ▼
8. Start the Password Recovery Process
              │
              ▼
9. Recover the Password
              │
              ▼
10. Verify the Password
              │
              ▼
11. Document Findings and Lessons Learned
```

---

# ⚙️ Phase 1: Lab Environment Preparation

The first phase involved preparing the Windows environment for the password recovery exercise.

The required tools included:

* John the Ripper
* Johnny GUI
* The authorized password-protected PDF file

Johnny was configured to locate and use the appropriate `john.exe` executable.

This connection is important because Johnny acts as the graphical interface while John the Ripper performs the underlying password recovery operations.

---

# 📄 Phase 2: Preparing the Protected PDF

The authorized training PDF was used as the target for this exercise.

Because John the Ripper works with password hash data rather than simply opening a protected file directly through the GUI workflow used in this lab, the password protection information from the PDF was prepared in a format suitable for analysis.

The resulting hash was saved into a text file:

```text
hash1.txt
```

The prepared hash was then used as the input for the password recovery process.

---

# 🔑 Phase 3: Loading the Hash into Johnny

After preparing the hash file, Johnny was opened.

The password file option was used to load:

```text
hash1.txt
```

Once loaded, the hash became available for password recovery analysis through John the Ripper.

This stage connected the prepared target data to the password recovery engine.

---

# 🚀 Phase 4: Password Recovery

A new password recovery attack was initiated through Johnny.

Johnny passed the password recovery task to the underlying John the Ripper engine.

The time required for password recovery can depend on several factors, including:

* Password length
* Password complexity
* Character combinations
* Password predictability
* Available wordlists or rules
* Hardware performance
* Processing power

For this authorized training exercise, the password was successfully recovered.

---

# ✅ Phase 5: Password Verification

After the password recovery process was completed, the recovered password was used to open the protected PDF.

Successful access to the document confirmed that the recovered password was correct.

This final verification step was important because it demonstrated that the password recovery result was valid.

---

# 📊 Project Results

The following objectives were successfully completed:

| Objective                          | Status      |
| ---------------------------------- | ----------- |
| Set up Windows lab environment     | ✅ Completed |
| Install John the Ripper            | ✅ Completed |
| Install Johnny GUI                 | ✅ Completed |
| Configure Johnny with John         | ✅ Completed |
| Work with authorized protected PDF | ✅ Completed |
| Prepare password hash              | ✅ Completed |
| Save hash to text file             | ✅ Completed |
| Load hash into Johnny              | ✅ Completed |
| Execute password recovery          | ✅ Completed |
| Recover the training password      | ✅ Completed |
| Verify recovered password          | ✅ Completed |
| Document the lab process           | ✅ Completed |

---

# 🔍 Key Findings

This project demonstrated several important cybersecurity concepts.

### 🔐 1. Password Strength Matters

Password-protected files are only as secure as the password protecting them.

Weak, predictable, or commonly used passwords may be more vulnerable to password recovery attacks.

---

### 🧩 2. Password Recovery is a Process

Password recovery involves more than simply pressing a button.

The workflow includes:

* Understanding the target format.
* Preparing the password hash correctly.
* Selecting an appropriate recovery method.
* Monitoring the recovery process.
* Verifying the result.

---

### 🖥️ 3. GUI Tools Can Improve Accessibility

Johnny makes John the Ripper more accessible for beginners by providing a graphical interface.

However, understanding the underlying functionality of John the Ripper remains important for developing deeper cybersecurity skills.

---

### ⏱️ 4. Password Complexity Affects Recovery Difficulty

Password recovery time is influenced by the complexity of the password.

Generally, stronger passwords can significantly increase the computational effort required to recover them.

---

# 🧠 Skills Demonstrated

Through this project, I practiced and developed skills in:

* 🔐 Password security fundamentals
* 🛠️ John the Ripper
* 🖱️ Johnny GUI
* 🪟 Windows cybersecurity environments
* 📄 Protected document analysis
* 🧩 Password hash preparation
* 🧪 Controlled password recovery testing
* 🔍 Security tool configuration
* 📊 Result validation
* 📝 Technical documentation
* ⚖️ Ethical cybersecurity practices

---

# ⚠️ Challenges and Lessons Learned

During password recovery labs, several issues can affect the process.

### Challenge: Tool Configuration

Johnny must be correctly connected to the appropriate `john.exe` executable.

**Lesson:**
Always verify tool paths and configurations before beginning an assessment.

---

### Challenge: Hash Formatting

Password recovery tools depend on correctly formatted hash data.

Extra or incorrect characters can prevent the tool from recognizing the hash.

**Lesson:**
Always validate the extracted hash format before starting an attack.

---

### Challenge: Recovery Time

Password recovery speed depends on password complexity and available computing resources.

**Lesson:**
A successful password recovery process is not always immediate. Password strength and computational limitations play an important role.

---

# 🛡️ Security Recommendations

Based on the concepts demonstrated in this lab, the following password security practices are recommended:

* Use long passwords or passphrases.
* Avoid predictable passwords.
* Avoid reusing passwords across multiple systems.
* Use unique passwords for sensitive accounts and documents.
* Combine password protection with additional security controls where possible.
* Use password managers to generate and store strong passwords.
* Regularly review password security practices.
* Conduct authorized password security assessments to identify weak credentials before attackers do.

---

# 📁 Repository Structure

```text
Password-Cracking-with-John-the-Ripper-Lab/
│
├── README.md
│
├── screenshots/
│   ├── 01-john-installation.png
│   ├── 02-johnny-installation.png
│   ├── 03-johnny-configuration.png
│   ├── 04-pdf-hash-extraction.png
│   ├── 05-hash-file-created.png
│   ├── 06-hash-loaded-into-johnny.png
│   ├── 07-password-recovery-process.png
│   └── 08-password-verification.png
│
├── documentation/
│   ├── project-task.pdf
│   └── lab-notes.md
│
└── .gitignore
```

> 🔒 **Note:** Do not upload real passwords, sensitive hashes, private documents, credentials, or unauthorized target data to a public repository.

---

# 📸 Evidence and Screenshots

The following screenshots can be added to this repository to document the project:

### 1️⃣ John the Ripper Installation

```text
screenshots/01-john-installation.png
```

### 2️⃣ Johnny GUI Installation

```text
screenshots/02-johnny-installation.png
```

### 3️⃣ Johnny Configuration

```text
screenshots/03-johnny-configuration.png
```

### 4️⃣ PDF Hash Preparation

```text
screenshots/04-pdf-hash-extraction.png
```

### 5️⃣ Hash File Creation

```text
screenshots/05-hash-file-created.png
```

### 6️⃣ Loading the Hash into Johnny

```text
screenshots/06-hash-loaded-into-johnny.png
```

### 7️⃣ Password Recovery Process

```text
screenshots/07-password-recovery-process.png
```

### 8️⃣ Password Verification

```text
screenshots/08-password-verification.png
```

---

# 🎓 Key Takeaways

This project helped me understand that password cracking tools are not simply "hacking tools." In an authorized cybersecurity environment, they can be used to evaluate password strength and identify weak security practices.

My key takeaways from this project include:

* Password strength is an important security control.
* Weak passwords can expose protected information.
* John the Ripper is a powerful password auditing and recovery tool.
* Johnny provides a beginner-friendly interface for working with John the Ripper.
* Correct hash preparation is essential.
* Password recovery should always be performed within an authorized scope.
* Technical findings should be validated before conclusions are made.
* Proper documentation is an important part of cybersecurity work.

---

# 🚀 Future Improvements

Future versions of this lab may include:

* 🔹 Command-line password recovery using John the Ripper directly.
* 🔹 Testing different password recovery modes in an authorized lab.
* 🔹 Comparing weak and strong password recovery times.
* 🔹 Working with additional authorized file formats such as ZIP archives.
* 🔹 Exploring wordlist-based password auditing in a controlled environment.
* 🔹 Exploring rule-based password auditing.
* 🔹 Comparing CPU and GPU-based password recovery tools in a lab environment.
* 🔹 Automating lab documentation and result collection.
* 🔹 Building a broader password security assessment laboratory.

---

# ⚖️ Ethical Disclaimer

This repository was created for **educational and authorized cybersecurity training purposes only**.

All password recovery activities documented in this project were performed against a designated training file in a controlled environment.

The techniques and tools discussed here should only be used against:

* Systems you own.
* Files you own.
* Intentionally vulnerable training environments.
* Cybersecurity laboratories.
* Targets for which you have explicit authorization.

Unauthorized access to passwords, files, systems, or accounts may be illegal and unethical.

---

# 👨‍💻 Author

**Olawale Sogbesan**

Cybersecurity Learner | Vulnerability Assessment | Ethical Hacking | Security Research


---

# ⭐ Conclusion

This project provided practical experience with **John the Ripper and Johnny GUI** in an authorized password recovery laboratory.

The exercise demonstrated how password security can be assessed through controlled password recovery techniques and reinforced the importance of strong, unique, and properly managed passwords.

This repository represents another step in my cybersecurity learning journey as I continue developing practical skills in:

**🔐 Password Security | 🛡️ Vulnerability Assessment | 🌐 Ethical Hacking | 🔎 Security Research | 🧪 Hands-On Cybersecurity Labs**
