# SoccerDiffusion 
⚽ SoccerDiffusion: Modeling Football Possession Dynamics Using Fractional Brownian Motion
Welcome to the public repository for the SoccerDiffusion project. This work explores how ball movement patterns in football can be modeled using fractional Brownian motion (fBm) and characterized through the Hurst exponent (H) — a statistical measure of persistence in time series.

Our objective is to estimate the Hurst exponent from possession sequences and understand how it varies in response to match events such as goals, red cards, or defensive pressure. The project combines synthetic data generation, machine learning models, and real match analysis to provide new tactical insights for football analytics.

---

📁 Repository Structure
The contents of this repository are organized as follows:
├── data/ # CSV files used for model training and evaluation
├── notebooks/ # All Jupyter notebooks with code for data processing, modeling, and evaluation
├── information/ # Project documents and references
│ ├── StatsBomb PDFs/ # Official data documentation
│ ├── M1-SOCCERDIFFUSION.pdf; # Link to our initial presentation (milestone 1)
│ ├── M2-SOCCER DIFFUSION.pdf # Milestone 2 report
│ └── Final_report.pdf # Final project write-up
├── web/ # Full website code (HTML, CSS, Python backend)
└── README.md # This file 

Project Highlights
Synthetic Data Generation: We created 50,000 football possessions using fractional Brownian motion, each labeled with a known Hurst exponent.
Feature Engineering: Extracted movement features (speed, acceleration, angles, etc.) from possessions.
Machine Learning: Trained models (XGBoost, Random Forest, Linear Regression, MLP, LSTM) to predict the Hurst exponent based on possession features.
Event Analysis: Applied the best-performing model (XGBoost) to real FC Barcelona matches from the 2019/2020 LaLiga season and analyzed how $H$ changes in response to:
Goals
Red cards
Substitutions
Defensive pressure
Web Visualization: A lightweight website was built to showcase project results and interactive visualizations.

💻 How to Run the Project
1. Clone the repository:```bash
   git clone https://github.com/yourusername/SoccerDiffusion.git
   cd SoccerDiffusion
2. Install required dependencies:
   pip install -r requirements.txt
3. Explore the notebooks in /jupyter notebooks:
   trasteo
   trasteo2
   trasteo3
   artificial_data
   final_code

Run the website (optional, requires Flask):
cd web

🌐 Website
We also provide a public-facing website (code in Pagina web/) that allows users to explore:

The concept of the Hurst exponent in football

Interactive possession visualizations

Match-level insights based on estimated $H$ values

🔗 [Live demo link – to be inserted]
📘 Documentation
Detailed explanations, methodology, and evaluations can be found in:

/Information/M2_report.pdf

/Information/Final_report.pdf

For a quick overview, check our original Prezi presentation.

🎯 Goals and Impact
SDG 4 – Quality Education: Encourages interdisciplinary learning in data science, mathematics, and sport.

SDG 8 – Decent Work and Economic Growth: Opens new opportunities in sports analytics and innovation through open data.

📄 License
This project is licensed under the MIT License. Feel free to reuse and adapt for research or educational purposes.

📫 Contact
For any questions or collaboration ideas, feel free to reach out via the Issues tab or open a pull request.