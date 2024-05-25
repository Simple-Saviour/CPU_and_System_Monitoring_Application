# CPU and SYSTEM MONITORING APPLICATION

The CPU and System Utilization Application is a comprehensive solution designed to monitor and optimize system resources. Leveraging a powerful tech stack, this project provides real-time insights into CPU performance, memory usage, and other critical metrics.

## Key Components

### Backend (Python):
The backend, written in Python, collects system data using libraries like psutil.
It continuously tracks CPU load and memory consumption.

### Frontend (HTML, CSS, JavaScript):
The user-friendly frontend, built with HTML, CSS, and JavaScript, offers an intuitive interface.

### Containerization (Docker):
The entire application is containerized using Docker.
Docker ensures consistent deployment across different environments.

### Orchestration (Kubernetes):
Hosted on a Kubernetes cluster, the application benefits from scalability, load balancing, and fault tolerance.


## **Deploying the application locally**

### **Step 1: Clone the code**

Clone the code from the repository:

```
git clone <repository_url>
```

### **Step 2: Install dependencies**

The application uses the **`psutil`** and **`Flask`, Plotly, boto3** libraries. Install them using pip:

```
pip3 install -r requirements.txt
```

### **Step 3: Run the application**

To run the application, navigate to the root directory of the project and execute the following command:

```
python3 app.py
```

This will start the Flask server on **`localhost:5000`**. Navigate to [http://localhost:5000/](http://localhost:5000/) on your browser to access the application.
