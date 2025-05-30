
## 📊 Real-Time Forex Trading Dashboard

Track major currency exchange rates against INR in real-time using a powerful analytics dashboard! 🚀
Built with **Python**, **Google BigQuery**, **Power BI**, and the **TwelveData API**, this project supports:

* 📈 Trend analysis
* 🚨 Threshold-based alerts
* 🕰️ Historical data modeling
* 🧊 OLAP operations (slice, dice, drill-down, pivot)


## 🔧 How to Load the Data

1. Clone this repo and install dependencies.
2. Set up your Google BigQuery credentials.
3. Run the Flask app:

   ```bash
   python app.py
   ```
4. Access the following URL in your browser to fetch and store Forex data:

   ```
   http://localhost:5000/fetch
   ```


## 🗂️ Setting Up Google BigQuery

* Use the Python script provided to load currency exchange data into your BigQuery project.
* The data is structured using a **star schema** (fact and dimension tables).
* This data will serve as the backend source for Power BI.


## 📊 Loading Data into Power BI

1. Open Power BI Desktop.
2. Connect to **Google BigQuery** using your credentials.
3. Use the **DirectQuery** mode to import data.
4. Enable **auto-refresh** to keep the dashboard updated in real-time.


