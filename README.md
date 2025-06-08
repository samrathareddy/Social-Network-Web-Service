🌐 Social Network Web Service – by Samratha Reddy

This project is a web-based social network analyzer that models user interactions and relationships as a graph, uncovering key insights such as influential users, communities, and network centrality. Built using Python, Flask, and NetworkX, the platform offers RESTful endpoints for data analysis and interactive visualizations.

GitHub Repository: Social Network Web Service

🔧 Technologies Used

Backend: Python, Flask

Graph Analytics: NetworkX

Visualization: D3.js (JavaScript)

Deployment: Docker, GitHub Actions (Optional CI/CD)

Data Storage: JSON, CSV

📊 Key Features

Upload social interaction data via CSV or JSON

Construct dynamic social graphs with nodes and edges

Identify influential users using centrality metrics

Detect communities using modularity-based algorithms

Visualize network with interactive, browser-based D3.js

REST API to fetch analytics on demand

🚀 Quick Start

# Clone repository
https://github.com/samrathareddy/Social-Network-Web-Service.git
cd Social-Network-Web-Service

# Create virtual environment & install dependencies
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt

# Run Flask app
python app.py

Navigate to: http://localhost:5000

📁 Folder Structure

├── app.py                 # Flask application
├── static/                # D3.js and CSS files for visualization
├── templates/             # HTML templates
├── data/                  # Sample input data files
├── graph/                 # Graph analysis logic using NetworkX
├── api/                   # REST API endpoints
├── requirements.txt       # Python dependencies

🌍 Use Cases

Analyzing social media networks

Visualizing email or messaging interaction graphs

Detecting leaders and communities in enterprise networks

Educational demos of social graph analysis

👨‍💻 About the Author

Samratha Reddy is a data engineering enthusiast and graduate student at Cleveland State University. This project showcases skills in backend development, graph theory, data visualization, and full-stack integration.

🔗 LinkedIn Profile

⭐ Star this repo if you found it helpful, and feel free to contribute or extend it!
