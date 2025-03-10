# 🔹 LinkedIn Automation - Power Automate Desktop  

## 📌 Overview  
This project automates the extraction of candidate information from LinkedIn using **Power Automate Desktop (PAD)**. It reads LinkedIn profile URLs from an **Excel file**, extracts relevant details (**Name, Current Position, and Description**), downloads the **CV (if available)**, and saves it in a structured folder.  

---

## 🎯 **Objective**  
This automation was developed as part of a **technical test** to evaluate skills in:  
- **Power Automate Desktop (PAD)** workflow automation.  
- **Web scraping techniques** for extracting structured data.  
- **Data handling** with Excel files.  
- **File manipulation** for storing downloaded CVs.  

## ⚙️ **Automation Workflow**  

### **1️⃣ Read Excel Input**  
- Load an **Excel file** with a list of LinkedIn profile URLs.  

### **2️⃣ Open LinkedIn Profiles**  
- Open each profile in **Microsoft Edge (or another compatible browser)**.  

### **3️⃣ Extract Profile Information**  
- Capture the **Name, Current Position, and Description** using **XPath selectors**.  

### **4️⃣ Download CV (if available)**  
- Click the **"More" button**, then **select "Save as PDF"**.  
- Wait for the **file to download** and rename it based on the candidate's name.  

### **5️⃣ Save Data in Excel & Organize Files**  
- Store the extracted data in **the same Excel file**.  
- Save **CVs in a predefined folder**, naming them appropriately.  

---

## 📑 **Delivery Format**  

### **Uploaded Files in GitHub:**  
✔️ **`Automation_Summary.pdf`** → Includes:  
   - 📸 Screenshots of the automation in **Power Automate Desktop**  
   - 📝 **Flowchart** explaining the logic  
   - 📋 **Written explanation** addressing the use case and assumptions  

✔️ **`LinkedIn_Profiles.xlsx`** → Input Excel file containing LinkedIn URLs.  

✔️ **`/CVs/` Folder** → Contains downloaded CVs with structured filenames.  

✔️ **`README.md`** → This documentation.  

---

## 🛠 **Installation & Setup**  

### **🔹 Requirements:**  
✅ **Power Automate Desktop** - [Download Here](https://flow.microsoft.com/en-us/desktop/)  
✅ **Microsoft Excel** (For reading/writing candidate data)  
✅ **Edge/Chrome Extension for Web Automation** - [Install Here](https://chrome.google.com/webstore/)  

### **🔹 How to Run the Automation:**  
1. **Open Power Automate Desktop (PAD)**  
2. **Import the provided automation flow**  
3. **Modify paths if needed (Excel file location, CV folder)**  
4. **Run the automation** and monitor execution  
5. **Review the extracted data in Excel and CV folder**  

---

## ❓ **Questions & Business Considerations**  
The following section answers key questions regarding **monitoring, potential issues, and future improvements**:  

### **1️⃣ How can the solution be monitored and maintained?**  
✅ **Logging** - The automation includes logs that track execution and errors.  
✅ **Error Handling** - If LinkedIn changes its structure, error messages help in debugging.  
✅ **Scheduled Maintenance** - Regular checks ensure automation is up to date.  

### **2️⃣ What could disrupt the automation, and how to prevent it?**  
❌ **LinkedIn UI Changes** → **Solution:** Use dynamic **XPath selectors**.  
❌ **LinkedIn Blocking Requests** → **Solution:** Introduce **random delays** to mimic human behavior.  
❌ **CV Not Available** → **Solution:** Use **"If element exists"** before clicking the download button.  

### **3️⃣ What future improvements can be made?**  
🚀 **AI-Powered Resume Analysis** - Extract key insights from CVs.  
🚀 **Direct ATS Integration** - Send extracted data to **HR systems (e.g., Greenhouse, Workday)**.  
🚀 **Automated Candidate Ranking** - Use **NLP models** to score candidates.  
🚀 **Cloud Storage for CVs** - Save files directly to **Google Drive or OneDrive**.  

---

## 📩 **Submission**  
The final project has been uploaded to this GitHub repository and submitted via:  
🔗 **[Microsoft Forms Submission Link](https://forms.microsoft.com/r/2Q6iZpYvPT)**  

---

## 📞 **Contact**  
For any questions, reach out to:  
📧 [Your Email]  
🔗 [Your LinkedIn Profile]  

---

**🚀 Thank you for reviewing this automation! Looking forward to discussing it. 🚀**
