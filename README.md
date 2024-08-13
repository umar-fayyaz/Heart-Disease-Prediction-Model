I’m excited to share my latest project where I explored the Framingham Heart Disease dataset from Kaggle, a valuable dataset for understanding heart disease risks. This project marks an important milestone in my data science journey, focusing on classification and predictive modeling.⁣
⁣
🛠️ 𝐓𝐨𝐨𝐥𝐬 & 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬 𝐔𝐬𝐞𝐝:⁣
For this project, I used several powerful tools and libraries.⁣
𝐏𝐚𝐧𝐝𝐚𝐬: For data manipulation and exploration.⁣
𝐍𝐮𝐦𝐏𝐲: For efficient numerical operations.⁣
𝐌𝐚𝐭𝐩𝐥𝐨𝐭𝐥𝐢𝐛 & 𝐒𝐞𝐚𝐛𝐨𝐫𝐧: To visualize data trends, correlations, and outliers.⁣
𝐒𝐜𝐢𝐏𝐲: Utilized for various statistical functions.⁣
𝐒𝐜𝐢𝐤𝐢𝐭-𝐥𝐞𝐚𝐫𝐧: The backbone for implementing machine learning models, data preprocessing, and validation techniques.⁣
⁣
📊 𝐃𝐚𝐭𝐚 𝐏𝐫𝐞𝐩𝐚𝐫𝐚𝐭𝐢𝐨𝐧:⁣
I began by loading the dataset (a CSV file) and performing basic data exploration to understand its structure. I identified missing values, visualized them, and handled these effectively. Additionally, I checked and removed duplicate entries to ensure data quality, transforming and filtering the data to make it suitable for analysis.⁣
⁣
🔍 𝐄𝐱𝐩𝐥𝐨𝐫𝐚𝐭𝐨𝐫𝐲 𝐃𝐚𝐭𝐚 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬 (𝐄𝐃𝐀):⁣
In the EDA phase, I conducted a thorough examination using various plots and graphs to uncover insights. This included analyzing correlations between features and the target variable and detecting and addressing outliers to refine the dataset further.⁣
⁣
🧠 𝐌𝐚𝐜𝐡𝐢𝐧𝐞 𝐋𝐞𝐚𝐫𝐧𝐢𝐧𝐠 𝐌𝐨𝐝𝐞𝐥𝐬:⁣
𝐋𝐨𝐠𝐢𝐬𝐭𝐢𝐜 𝐑𝐞𝐠𝐫𝐞𝐬𝐬𝐢𝐨𝐧:⁣
Since the dataset was imbalanced, I used SMOTE (Synthetic Minority Over-sampling Technique) to balance it.⁣
After splitting the balanced dataset into training and test sets, I applied feature scaling and trained the Logistic Regression model.⁣
Accuracy: ~72% on test data, ~71% on training data.⁣
Cross-validation using K-Fold resulted in an average accuracy of ~72%.⁣
I also analyzed the feature contributions to model performance.⁣
⁣
𝐗𝐆𝐁𝐨𝐨𝐬𝐭:⁣
I explored XGBoost, another powerful classification technique, to compare results.⁣
Accuracy: A significant boost with an average of ~84%.⁣
Performed cross-validation on XGBoost for further evaluation.⁣
⁣
🖥️ 𝐈𝐧𝐭𝐞𝐫𝐚𝐜𝐭𝐢𝐯𝐞 𝐏𝐫𝐞𝐝𝐢𝐜𝐭𝐢𝐨𝐧:⁣
To make the project more interactive, I developed a simple console input function that predicts heart disease risk based on user inputs. This model provides real-time predictions, making it a practical tool for learning.

This project was an excellent opportunity to strengthen my understanding of classification models and data science workflows. I'm looking forward to further refining my skills and tackling more complex datasets in the future!
