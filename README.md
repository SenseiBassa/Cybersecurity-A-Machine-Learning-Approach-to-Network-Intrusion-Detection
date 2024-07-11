# Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection
![856d6ed0bd41adf613fadc1f3b8b7e87](https://github.com/SenseiBassa/Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection/assets/98027992/9598ec1b-17af-4e8a-90fc-988b1e68c856)

Presenteby: Bassa, Joshua Samuel.

Project introduction:

 Learning Opportunities:
Fortify your computer systems against network intrusion and ransomware attacks through the strategic application of advanced machine learning techniques. This project will provide you with an in-depth understanding of how to harness the power of Python libraries like NumPy. Pandas. Matplotlib, Seaborn, PySpark, and Sci-kit Learn. Enabling you to not only detect and prevent network but also bolster your overall cybersecurity measures.

• Learning Skills

• Exploratory Data Analysis (EDA)

• Feature Selection

• Model Selection

Specialization:
• Predictive Analytics

• Supervised Machine Learning.

Business Focus:
• Cybersecurity

Tools:
• Python
![6f06f467424256a98d2ede1c965b8c6e](https://github.com/SenseiBassa/Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection/assets/98027992/2881fe4d-776d-47c0-a2da-a7d5b1411817)

Business Introduction:
SecureTech Solutions Inc. stands at the forefront of the cybersecurity industry, distinguishing itself through a dedicated focus on delivering state-of-the-art solutions that shield businesses from the ever-evolving landscape of cyber threats. Backed by a cadre of exceptionally proficient professionals, SecureTech is driven by an unwavering dedication to pioneering advancements in the field. This steadfast commitment has forged a robust legacy, positioning the company as an unparalleled guardian of clients' invaluable data and vital systems, capable of warding off an extensive array of cyber assaults.

![23bb13f0aff0ea92d7b5300f018fd036](https://github.com/SenseiBassa/Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection/assets/98027992/0efdb289-3b79-4bcf-8112-8bfdeec8f267)

Business Problem: 
This surge in ransomware attacks targeting SecureTech Solutions Inc.'s clients underscores concerning trend in cybersecurity. The attackers have demonstrated a worrisome level of adaptability, deploying increasingly sophisticated tactics that outpace traditional security measures. Beyond the immediate financial implications, these assaults carry the weighty consequence of eroding the trust and reputation that SecureTech has painstakingly built As the company continues to grapple with this evolving threat landscape, its unwavering commitment to innovation and expertise remains paramount in safeguarding clients' critical assets and preserving their confidence in the face of such challenges.

Why Network Intrusion Detection: 
In this age, a lot of crime involves malicious actors infiltrating a system. encrypting critical data, and demanding a ransom for its release. This necessitates the ability to detect ransomware and network intrusion. Here are several key reasons why ransomware detection is crucial.

Preventing Financial Losses: Network intrusion almost always precede ransomware attacks, which can lead to substantial financial losses, not only from the ransom payment itself but also from the potential downtime, lass of productivity, and the costs associated with recovery and restoration efforts.

Safeguarding Sensitive Data: 
Many organizations store highly sensitive and confidential information. Intrusive attacks can result in the exposure or theft of this data, which can have severe legal, financial, and reputational consequences.

Preserving Business Continuity: 
Ransomware attacks can disrupt operations, leading to downtime that can be detrimental to an organization's productivity and profitability. Effective detection enables swift response, minimizing disruption and ensuring continuity.

Aim of Project:
Develop an Effective Ransomware Detection System: Create a machine learning model capable of accurately detect cyberattack in real-time.

Minimize False Positives and False Negatives: Implement algorithms and techniques to reduce false alarms and improve the efficiency of security projections.

Ensure explainable predictions: Develop a machine learning model which is explainable and can give insights to cyber analysts as regards the fundamentals underlying malware attacks.

![856d6ed0bd41adf613fadc1f3b8b7e87](https://github.com/SenseiBassa/Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection/assets/98027992/8c11be0b-aa64-4dd0-a350-7a2af55150b6)

Data Description:

The features present in the dataset are numerous. They can however, be grouped as follows: Traffic information: Information about internet traffic, such as subnet masks, IP masks, IP addresses. etcetera. Extra data. Features describing filetypes, file access patterns, etcetera,

Data Description II: 
Src_Port: Originating port for connection

Dst Port: Destination port for connection

Protocol: Connection protocol (HTTP, HTTPS, UDP, TCP etcetera)

Flow_Duration: Duration of connection

Tot_Fwd_Pkts: Total number of packets transmitted forward over connection lifetime

Tot_Bwd_Pkts: Total number of packets transmitted backward over connection lifetime

TotLen_Fwd_Pkts: Total size of packets transmitted forward over connection lifetime TotLen_Bwd_Pkts: Total size of packets transmitted backward over connection lifetime

Fwd_Pkt_Len_Max: Size of largest packet transmitted forward over connection lifetime

Fwd_Pkt_Len_Min: Size of smallest packet transmitted forward over connection lifetime.

Data Description III
Fwd_Pkt_Len_Mean: Mean size of packets transmitted forward over connection lifetime

Fwd_Pkt_Len_Std: Standard deviation of size of packets transmitted forward over connection lifetime

Bwd_Pkt_Len_Max: Size of largest pocket transmitted backward over connection lifetime.

Bwd_Pkt_Len_Min: Size of smallest packet transmitted backward over connection lifetime.

Bwd_Pkt_Len_Mean: Mean size of packets transmitted backward over connection lifetime.

Bwd_Pkt_Len_Std: Standard deviation of size of packets transmitted backward over connection lifetime.

Flow_Byts/s: Overall connection speed in bytes per second.

Flow_Pkts/s: Overall connection speed in number of packets per second.

Data Description IV: 
Flow_IAT_Mean: Average flow interarrival time.

Flow_IAT_Std: Standard deviation of flow interarrival time.

Flow_IAT_Max: Maximum interarrival time recorded for flow.

Flow_IAT_Min: Minimum interarrival time recorded for flow.

Fwd_IAT_Tot: Total interarrival time recorded for forward flow.

Fwd_IAT_Mean: Average flow interarrival time for forward flow.

Fwd_IAT_Std: Standard deviation of flow interarrival time for forward flow.

Fwd_IAT_Max: Maximum interarrival time recorded for forward flow.

Fwd_IAT Min: Minimum interarrival time recorded for forward flow.

Data Description VI
Pkt_Len Min: Size of smallest packet transmitted over connection lifetime.

Pkt_Len_Max: Size of largest packet transmitted over connection lifetime.

Pkt_Len_Mean: Mean packet size over connection lifetime.

Pkt_Len Std: Standard deviation of packet sizes over connection lifetime.

Pkt_Len_Var: Variance of packet sizes over connection lifetime.

FIN_Flag_Cnt: Number of FIN flags raised over connection lifetime.

SYN_Flag Cnt: Number of SYN flags raised over connection lifetime.

RST_Flag_Cnt: Number of RST flags raised over connection lifetime.

PSH_Flag_Cnt: Number of PSH flags raised over connection lifetime.

ACK Flag Cnt: Number of ACK flags raised over connection lifetime.

Data Description VII
Down/Up Ratio: Ratio of download to upload.

Pkt_Size Avg: Average packet size over entire connection lifetime.

Fwd Seg Size Avg: Average size of forward packet segments over connection lifetime.

Bwd_Seg Size_Avg: Average size of backward packet segments over connection lifetime.

Subflow_Fwd_Pkts: Number of forward packets in connection subflow.

Subflow_Fwd_Byts: Number of forward bytes in connection subflow.

Subflow_Bwd_Pkts: Number of backward packets in connection subflow.

Subflow_Bwd_Byts: Number of backward bytes in connection subflow.

Init_Bwd_Win_Byts: Number of backward packets sent in initial connection window.

Fwd_Act Data_Pkts: Number of packets with at least 1 byte of TCP data payload in the forward direction.

Tech Stack: 
The programming language of use, as in most of ML, is Python. The Python libraries of interest for this project are:

NumPy: Numerical computation.

Pandas: Data munging and manipulation

Matplotlib and Seaborn: Data Visualization

PySpark: Parallelized and Distributed Machine Learning.

Project Scope: 

I.    Exploratory Data Analysis: 
The data is thoroughly explored and analysed to gain insights and understand its characteristics. This involves statistical analysis, data visualization, and other exploratory techniques to identify patterns, correlations, anomalies, and potential issues in the data.

II.    Feature Selection: 
Not all features provided in data may be of relevance to the target. Feature selection is the process by which we can select the most appropriate of these according to a specified set of criteria.

III.    Model Development: 
Various modeling techniques are applied to the prepared data in this stage to build predictive or descriptive models. This can include machine learning algorithms, statistical models, or other analytical approaches. The models are trained, validated, and fine-tuned to optimize their performance.

IV.    Model Evaluation and Selection: 
Once validation techniques. This involves assessing their performance, generalizability, and robustness. The best-performing model(s) are selected for further deployment tor refinement.

1.0  Network Intrusion Detection with ML
This project aims to successfully classify the ransomware and network intrusion attacks observed during the day-to-day operations of a popular tech firm.

The observed attacks may be classified as either one of:

DFA (differential fault analysis attacks, attacks based on specific understanding of system particulars),

DDoS (Distributed denial of service).

DoS (Denial of service).

Normal (normal computer operations).

Probe (probing attacks), or

U2R (user-to-root)

2.0 Methodology

This project will be carried out using the CRISP-DM methodology. This is one of the more popular data science methodologies and is characterized by six important which are as follows:

Business Understanding,
Data Understanding.
Data Preparation,
Data Modelling.
Model Evaluation, and
Model Deployment.
It should be noted that these phases are usually recurrent in nature (i.e, some phases may be repeated). As such, they do not necessarily follow a linear progression.

3.0 Tools: 
The tools of use for this project include:

Pandas

NumPy

Matplotlib & Seabom

PySpark

3.1. Pandas & NumPy: Pandas is a Python library built upon the NumPy library. The idea behind Pandas is to be able to operate on text data, where NumPy is best suited for numerical operations, irrespective of the fact that it can represent text to some degree.

3.2. Matplotlib & Seaborn Matplotlib and Seaborn are Python libraries for train visualization. Other alternatives include Bokeh and Plotly.

3.3. PySpark PySpark is a Python API that acts as a wrapper around the original Spark API written in Scala. It is used for optimized, large-scale train science. The main advantage offered by PySpark over other ML libraries like Pandas and Sci-kit Learn would be:

Distributed and parallelized operations for big data, and

Optimized ML. algorithms.

![a9c4004023509ab13b17f7ba539832ff](https://github.com/SenseiBassa/Cybersecurity-A-Machine-Learning-Approach-to-Network-Intrusion-Detection/assets/98027992/30027362-ec61-4a6b-8885-253f30bdf3ce)


  Project Implementation via CRISP-DM
01. Business Understanding
Secure Tech is a cybersecurity firm with a strong foothold in cyberspace. They are presently interested in beefing up their cybersecurity protocols, but for this, they need to be able to detect network attacks efficiently and timely. As such, you have been employed with the goal of building a machine learning model that can do this.

This would be an immense boon to them in the following ways:

Provide legitimate use for their accumulated operational data
Accurately detect network attacks before or while they occur.
In order to train the needed machine learning models, the IT team at Secure Tech will need data that records and describes the conditions and state of their network. Some of this information would include source and destination ports, connection speed in forward and backward directions, sizes of information packets transmitted, etcetera.

    02. Data Understanding
With the Business Understanding out of the way, the next step is to understand the data to be obtained and used for the task. This will involve the process of Exploratory Data Analysis (EDA).

EDA is the process of sifting through data with the goal of extracting insights. These insights allow a better understanding of the available data and what can be done with it. They can also be used for guided preparation of the dataset in the appropriate manner. Just like regular analysis, EDA begins with a set of questions and/or hypotheses. The EDA process will then prove or disprove these hypotheses, and hopefully, reveal other points of inquiry along the way.

The required libraries and packages are imported first. The EDA process is carried out here as shown below. The high-level steps to follow are;

Import the required libraries
Load in the dataset
Analyze and observe its properties. Missing data
Outliers
Inconsistent values
Low categorical cardinality
Data imbalance
Report on these properties and how they might affect our final solution.
Data Implications
Implied by our findings above, we can say the following:

Missing values and outliers. There are no missing values in the trainset. As regards outliers, there are quite a few.
Data imbalance. The dataset is strongly imbalanced with respect to the instance labels. This implies that regular classification metrics like accuracy would not be good enough for evaluating the final del
Sealing: Depending on the final learning algorithm used, there might be a need for feature scaling with a good number of the variables in the data. This would discourage the model from assigning undue degrees of importance (ie, weights) to a variable simply due to average magnitude.
Correlation: There is low multicollinearity within the dataset. Some features exhibit strong correlations with one another. Some of these features might need to be eliminated or combined somehow to maintain feature independence.
Date dimensionality. There are around - 84 different features in the dataset. Although the number of observations (-0.14 million) will offset the curse of dimensionality, the need to reduce the data dimensionality might still arise.
Large number of records. The large number of records (-0.14 million) is characteristic of the amount of data generated from the day-to-day operations of the computer networks. As such, optimized algorithms would be required for effective computation.
Irrelevant columns: Some columns are irrelevant since they have a variance of zero. These columns need to be eliminated.
03. Data Preparation: 
Based on the Data Implications discovered prior, the following steps will be experimented upon for the data preparation stage.

Remove invariant and irrelevant columns. The invariant and irrelevant columns will be eliminated.
Feature Scaling: The data will be scaled using the Standard Scaler implementation provided by Sci-kit Learn.
Feature Selection: The non-numerical features of the dataset are filtered out, and the numerical features are retained. This is done in order to avoid complicated feature engineering.
Distributed Computing: In order to satisfy the need for optimal computation, most of (if not all) the algorithms used will be obtained from PySpark. All these steps are implemented as below:


