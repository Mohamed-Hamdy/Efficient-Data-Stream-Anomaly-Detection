# Efficient-Data-Stream-Anomaly-Detection
**Project Overview**

Python implementation for detecting anomalies in a continuous data stream. The code simulates a real-time sequence of floating-point numbers, which can represent various metrics such as financial transactions or system metrics.

**Key Features**

- **Data Stream Simulation:** Generates a synthetic data stream with seasonal patterns, noise, and randomly injected anomalies.

- Anomaly Detection:

   Employs two robust methods:

  - Z-score method: Identifies outliers based on their distance from the mean and standard deviation within a rolling window.
  - Isolation Forest: A suitable algorithm for real-time anomaly detection, capable of handling concept drift.

- **Visualization:** Provides a clear visualization of the data stream and detected anomalies.

**Getting Started**

1. **Open in Google Colab:** Click the "[project link](https://colab.research.google.com/drive/1pGM-BrqyQY9Zu-ReLxSlSvfzMZXKu3NE)" or see "Efficient_Data_Stream_Anomaly_Detection.ipynb" in files.
2. **Run the Cells:** Execute the cells sequentially to simulate the data, perform anomaly detection, and visualize the results.

**Customization**

You can customize the simulation parameters (size, anomaly count, magnitude, noise level) to suit your specific needs. Modify the parameters in the `simulate_data_stream` function.

**Additional Notes**

- For more advanced visualizations or real-time analysis, consider exploring libraries like Plotly or Bokeh.
- This notebook serves as a starting point. Feel free to extend it with additional features or adapt it to your specific use cases.
