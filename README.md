**Project Descriptions**:

This app is build for Visualization of Phonepe Pulse Data
In this project that visualizes transaction and user data to provide insights and trends of the PhonePe platform. It utilizes various data visualization techniques to present the data in an interactive and informative manner.

**Data Sources**:

The data used in the PhonePe Pulse project is sourced from PhonePe's transaction and user records. The data is stored in CSV format and preprocessed before visualisations are used.

Dataset Link for Download

**To run this app**

    python -m streamlit run app.py or streamlit run app.py

**NOTE :- provide your sql user, database name, password.**

    Basic Requirements:
    Python 3.10
    mysql_connector
    Pandas
    Streamlit
    Numpy
    streamlit-option-menu

**Local Setup:**

**1. Clone the Repository**:

        git clone git@github.com:AJIN-B/Phonepe_Pulse_Data_Visualization.git
        cd Phonepe_Pulse_Data_Visualization
   
**2. Set Up a Virtual Environment (Optional but Recommended):**

      # For macOS and Linux:
      python3 -m venv venv

      # For Windows:
      python -m venv venv
      
**3. Activate the Virtual Environment:**

      # For macOS and Linux:
      source venv/bin/activate

      # For Windows:
      .\venv\Scripts\activate
      
**4. Install Required Dependencies:**

      pip install -r requirements.txt
      
**5. Set up the Environment Variables:**

    # add the following Keys

    HOST="Your HOST ID"
    
    USER="Your USER ID"
    
    PASSWORD="Your PASSWORD"
    
    PORT="Your PORT"
    
    DATABASE_NAME="Your DATABASE NAME"
    
**6. Run:**

    python -m streamlit run app.py 
    or 
    streamlit run app.py
    
After running the command, Streamlit will provide a local URL (usually http://localhost:8501/) which you can open in your web browser to access application.
