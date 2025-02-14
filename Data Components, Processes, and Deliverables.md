# Data Components, Processes, and Deliverables - Data Science, Data Mining, Machine Learning, AI, Advanced Analytics, and Big Data

## Data Science Components and Considerations
- Data types
    + Structured data
    + Unstructured data
    + Semi-structured data
    + Streaming data
    + Batch data
- Analytic classes
    + Transforming analytics
        * Aggregation
        * Enrichment
        * Processing
    + Learning analytics
        * Regression
        * Clustering
        * Classification
        * Recommend
    + Predictive analytics
        * Simulation
        * Optimization
    + Descriptive analytics
    + Prescriptive analytics
- Learning models
    + Learning style
        * Supervised
        * Unsupervised
        * Semi-supervised
    + Training style
        * Reinforcement learning
        * Online learning
        * Offline learning
- Execution models
    + Sequencing
        * Serial execution
        * Parallel execution
    + Scheduling
        * Streaming execution
        * Batch execution
- Key considerations
    + Curse of dimensionality

## Data Science Process (non-linear, iterative, and cyclical)
- Domain discovery, goal identification, and question development
    + Understanding the goal of the project and define objectives
    + Drives mapping the problem space to the solution space
    + Typical data science goals
        * Turning data into actions
        * Build data products providing actionable information while abstracting away technical details, data, and analytics
        * Question discovery
        * Improving products for user benefit and experience
        * Driving business decisions and solutions
        * Automated decision making, predictions, recommendations, and insights
        * Inform strategic decisions
        * Inform product changes and drive company KPIs
        * Shift from HiPPO decision making to data-driven decision making
        * Competitive advantage, differentiation, future-proofing, and opportunity costs
        * Complement business intelligence functions
        * Predict and advise
        * Grow data economy wealth
        * Increase ROI and ROA
        * Shifting between deductive (hypothesis-based) and inductive (pattern- based) reasoning (ref. Booz, Allen, Hamilton)
            - Deductive
                + Formulate hypotheses about relationships and underlying models
                + Carry out experiments with the data to test hypotheses and models
            - Inductive
                + Exploratory data analysis to discover or refine hypotheses
                + Discover new relationships, insights and analytic paths from the data
- Determine the type of problem and type of solution required
- Data instrumentation, acquisition, collection, extraction, merging/joining, ETL, storage, and pipeline architecture/development
    + Data sources: raw data, real time measurement, events, IoT, and so on
    + Data warehouse or data lake
        * Data lake eliminates need for ETL according to Booz, Allen, and Hamilton
- Data munging/wrangling
    - Data parsing, cleaning, and tidying
    - Data processing, transformation, and aggregation
        + Includes feature scaling, normalization, and/or standardization
        + Categorical feature transformation and dummy variables
        + Deduplication
        + Format conversion
        + Frequency space
            * Fast fourier transform (FFT)
            * Discrete wavelet transform
        + Euclidian space
            * Coordinate transform
    - Data filtering
        + Outlier detection and removal
        + Exponential smoothing
        + Gaussian filter
        + Median filter
    - Imputation
        + Generate values for other observations in dataset
            * Random sampling
            * Markov chain monte carlo
        + Without other observations
            * Mean
            * Statistical distributions
            * Regression models
    - Data deletion
- Data consumption, exploratory data analysis (EDA), statistical analysis, descriptive analytics, and visualization
- Feature extraction, feature selection, and feature engineering
    + Wrapper methods
    + Sensitivity analysis
    + PCA
- Performance metric selection. Examples:
    + MSE and RMSE
    + R squared (aka explained variance)
    + Accuracy
    + Precision
    + Recall (aka sensitivity)
    + Receiver operator characteristic (ROC)
    + Area under the ROC curve (AUC)
    + F-score
- Data splitting
- Model selection, training, evaluation, validation, complexity reduction, and tuning
    + Iterative process and involves revisiting previous stages, including model selection
    + Model complexity reduction via subset selection, shrinkage methods, regularization (e.g., ridge regression and lasso), and dimensionality reduction
        * Dimensionality reduction
            - PCA
            - Factor analysis
            - K-means clustering
            - Canopy clustering
            - Feature hashing
            - Wrapper methods
            - Sensitivity analysis
            - Self organizing maps
            - Text data
                + Term frequency (TF)
                + Inverse document frequency (IDF)
    + Ensemble methods exploration and implementation as needed for performance goals (e.g., bagging, boosting, model averaging, weak learner theory, random forests, ...)
    + Model validation, resampling methods, and selection
        + Cross-validation
        + Bootstrap
        + Mallow’s Cp
        + Akaike information criterion (AIC)
        + Bayesian information criterion (BIC)
    + Bias variance tradeoff and model complexity
        * Validation curve
        * Learning curve
        * Residual sum of squares
        * Goodness-of-fit metrics
    + Error analysis and tradeoffs
        * Type 1
        * Type 2
- Deliverables, deployment, and results communication (see below)

## Data Science Deliverables
- Automated decision making, predictions, recommendations, and insights
- Deep and actionable insights
    + Story telling
    + Writing
    + Speaking
    + Reports
    + Dashboards
    + Visualizations
    + Presentation
- Statistical analysis
    + Sensitivity
    + Correlation
    + Variance and standard deviation
    + Mean, median, and mode
    + Skew and kurtosis
    + Quartiles
    + Distribution
    + Count
    + Range
    + Plots
- Asynchronous messaging, notifications, insights, and alerts
- Deployed batch and/or real-time solution (e.g., analytics models and algorithms), potentially including monitoring, performance measurement, analytics, dashboards, and reporting
- Analytics
    + Descriptive analytics - What happened and why?
    + Predictive analytics - What is the probability of something happening?
    + Prescriptive analytics - What specific recommendations will drive business decisions and help achieve business goals (i.e., what to do if 'X' happens)
- Machine learning and Artificial intelligence specific
    + Supervised learning and prediction
        * Classification
            - Binary (two class) and multi-class
        * Regression
            - Univariate and multivariate
        * Anomoly detection
    + Unsupervised learning
        * Clustering, grouping, and characterizations
        * Anomoly detection
    + Recommendation systems (aka recommendation engine)
    + Recognition
        * Image
        * Speech
        * Video
        * Text and optical character
        * Pattern
        * Audio
        * Facial    
        * Handwriting
    + Text analytics
        * Sentiment analysis
        * Word clouds
        * NLP, NLG, NLU
    + Reinforcement learning
    + Probability estimates and likelihoods
    + Graph analytics (e.g., social network analysis)
    + Health diagnosis
    + Process improvements
- Optimization
    + Minimum
    + Maximun
    + Optimal value or optimal combination
- Segmentation
- Targeted advertising
- Forecasts
- Risk analysis
- Optimization and response surface models (RSM) for design of experiments (DOE) projects

## Process Models
- [Ask, Get, Explore, Model, Communicate and visualize results](http://www.datascientists.net/what-is-data-science)
- [Sample, Explore, Modify, Model, and Assess - SEMMA](https://en.wikipedia.org/wiki/SEMMA)
- [Acquire, Prepare, Analyze, Act (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Analyze stage (iterate evaluation)
        * Setup
        * Try
        * Do
- [The Data Science Maturity Model: Collect, Describe, Discover, Predict, Advise (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
- [Balancing the Five Analytic Dimensions (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Speed
    + Analytic complexity
    + Accuracy and precision
    + Data size
    + Data complexity
- [Implementation Constraints (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Computational frequency
    + Solution timeliness
    + Implementation speed
    + Computational resource limitations
    + Data storage limitations
- [Fractal Analytic Model (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
    + Goal
        * Describe
        * Discover
        * Predict
        * Advise
    + Data
    + Computation
        * Aggregation
        * Enrichment
        * Clustering
        * Classification
    + Action
        * Productization
        * Data monetization
        * Insights and relationships
- [Cross Industry Standard Process for Data Mining - CRISP-DM](https://en.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)
    + [CRISP Visual Guide](https://exde.files.wordpress.com/2009/03/crisp_visualguide.pdf)
- [Knowledge Discovery in Databases - KDD](https://en.wikipedia.org/wiki/Data_mining#Process)
    + [Overview of the KDD Process](http://www2.cs.uregina.ca/~dbd/cs831/notes/kdd/1_kdd.html)
    + [From Data Mining to Knowledge Discovery in Databases](http://www.kdnuggets.com/gpspubs/aimag-kdd-overview-1996-Fayyad.pdf)
- [Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-process-overview) and [Interactive graphic](https://azure.microsoft.com/en-us/documentation/learning-paths/data-science-process/)
- [Acquire, Prepare, Analyze, Report, Act](https://www.coursera.org/learn/big-data-introduction/lecture/Fonq2/steps-in-the-data-science-process)
- [The REASON Method: Relating, Explaining, Selecting, Outlining, and Navigating](http://www.datasciencecentral.com/m/blogpost?id=6448529%3ABlogPost%3A369943)

## Statistics
Coming soon...

## References
- [The Field Guide to Data Science (Booz, Allen, Hamilton)](https://www.boozallen.com/content/dam/boozallen/documents/2015/12/2015-FIeld-Guide-To-Data-Science.pdf)
