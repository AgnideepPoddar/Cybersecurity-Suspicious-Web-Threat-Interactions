# 🔒 Cybersecurity: Suspicious Web Threat Interactions  
Analyzing **web traffic records** to detect **suspicious activities and potential cyber threats** using **machine learning, SQL, and Python**.  

## 📂 Dataset  
This dataset contains **web traffic logs** collected from **AWS CloudWatch**, focusing on detecting **suspicious patterns and attack attempts**.  

📥 **[Download Dataset](https://drive.google.com/file/d/1zdnm7BMe_IHsKM0x_4BjApdYIEL2XbYV/view?usp=sharing)**  

### **Dataset Features**  
Each record represents web traffic interactions with a production web server.  

- **bytes_in**: Number of bytes received by the server  
- **bytes_out**: Number of bytes sent from the server  
- **creation_time**: Timestamp when the traffic record was created  
- **end_time**: Timestamp when the connection ended  
- **src_ip**: Source IP address  
- **src_ip_country_code**: Country code of the source IP  
- **protocol**: Protocol used in the connection  
- **response_code**: HTTP response code  
- **dst_port**: Destination port on the server  
- **dst_ip**: Destination IP address  
- **rule_names**: Name of the detection rule that flagged the traffic  
- **observation_name**: Observations related to the traffic  
- **source_meta**: Metadata related to the source  
- **source_name**: Name of the traffic source  
- **time**: Timestamp of the detected event  
- **detection_types**: Type of detection applied  

### **Use Cases**  
- **📊 Anomaly Detection**: Identify suspicious activities in web traffic  
- **🛡️ Cyber Threat Intelligence**: Detect attack attempts and malicious patterns  
- **🔍 Security Log Analysis**: Analyze network behavior to prevent threats  
- **🧠 Machine Learning for Threat Detection**: Train models to classify traffic as normal or suspicious  

## 🛠️ Tools & Technologies  
- **Python, Machine Learning, SQL, Excel**  
- **VS Code, Jupyter Notebook**  
- **Pandas & NumPy**: Data manipulation  
- **Matplotlib & Seaborn**: Data visualization  
- **Scikit-Learn & TensorFlow**: Machine learning models  
- **AWS CloudWatch Logs**: Log monitoring and analysis  

## 🚀 Project Workflow  
### **1. Data Preprocessing**  
✔ Handle missing values and remove irrelevant data  
✔ Convert timestamps and extract time-based features  
✔ Standardize and normalize numeric features  

### **2. Exploratory Data Analysis (EDA)**  
✔ Identify patterns in network traffic  
✔ Visualize attack patterns and suspicious activities  

### **3. Feature Engineering**  
✔ Extract key features from **IP addresses, timestamps, and response codes**  
✔ Encode categorical data for model training  

### **4. Model Building**  
✔ Train **classification models** to detect suspicious web interactions  
✔ Implement **anomaly detection models** (e.g., Isolation Forest, Autoencoders)  

### **5. Model Evaluation**  
✔ Evaluate models using accuracy, precision, recall, and F1-score  

### **6. Visualization & Reporting**  
✔ Build security dashboards to track threats  

## 📌 Project Difficulty Level  
**Advanced**  

## 📈 Results & Insights  
📊 Visualizations and findings from this project will be added in the **Results** section.  

## 🔧 Getting Started  
1. Clone the repository:  
   ```sh
   git clone https://github.com/AgnideepPoddar/Cybersecurity-Suspicious-Web-Threat-Interactions.git
   ```  
2. Run the analysis scripts to explore the dataset.  

## 🤝 Contributions  
Contributions are welcome! Feel free to open issues or submit pull requests.  

## 📜 License  
This project is for educational purposes and follows the **MIT License**.  
