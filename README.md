# Big Data Performance Analysis

## Project Overview
This project conducts a comprehensive analysis of performance in big data environments, focusing on the impact of various cluster configurations on disk operations and network packet transfers. The study evaluates how factors such as batch size, repetitions, and cluster size influence computational efficiency, providing valuable insights into optimizing data processing in distributed systems.

## Contents
- **Notebooks**:
    - `BD_CW_Data_preprocessing_and_ML_training_v23_Questions.ipynb`: Data preprocessing and machine learning training pipeline.
- **Reports**:
    - `Big_Data_Coursework_.pdf`: Detailed report documenting the methodology, experiments, and findings.
- **Visualizations**:
    - `Images Batch Size.png`: Performance analysis for image processing tasks, showing how batch size affects throughput.
    - `TFRecords Batch Size.png`: Visualization of TFRecords processing efficiency relative to batch size.
    - `Maximal Cluster Network Packets Optimised.png`: Optimized network packet performance in a maximally scaled cluster.
    - `Meduim Cluster Disk Operations Optimised.png`: Disk operation performance in a medium-sized, optimized cluster configuration.

## Key Findings

### 1. Impact of Batch Size on Performance
- **Image Processing**: Larger batch sizes generally improve processing speed, but this comes with increased memory usage, which may not be sustainable for all systems.
    ![Images Batch Size](path/to/Images_Batch_Size.png)

- **TFRecords Processing**: Similarly, increasing batch sizes improves throughput for TFRecords, highlighting the importance of batch optimization in data pipeline design.
    ![TFRecords Batch Size](path/to/TFRecords_Batch_Size.png)

### 2. Cluster Configuration and Network Efficiency
- **Maximal Cluster Configuration**: When scaled to maximal cluster sizes, network packet handling becomes more efficient, reducing latency and improving overall system performance.
    ![Maximal Cluster Network Packets](path/to/Maximal_Cluster_Network_Packets_Optimised.png)

- **Medium Cluster Disk Operations**: Disk operations in a medium cluster configuration, when optimized, achieve a balance between speed and resource usage, making it a viable option for mid-sized datasets.
    ![Medium Cluster Disk Operations](path/to/Meduim_Cluster_Disk_Operations_Optimised.png)

## How to Run

1. **Clone the repository**:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Environment Setup**: 
   
   Set up the necessary environment by installing required packages. You can do this by running:

    ```bash
    pip install -r requirements.txt
    ```

3. **Execute the Notebooks**: 

   Open the provided Jupyter notebooks and run the cells to reproduce the analysis and generate the visualizations.

## Conclusion
This project underscores the significance of optimizing batch sizes and cluster configurations in big data processing. By carefully tuning these parameters, substantial improvements in computational efficiency and resource management can be achieved. The findings are crucial for designing scalable and efficient data processing pipelines in distributed environments.
