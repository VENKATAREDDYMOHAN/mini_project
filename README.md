Overview:

This project analyzes individual WhatsApp chats using Python and machine learning techniques to uncover meaningful insights about conversations. The system parses chat data and provides detailed analysis on:

1. Message frequency over time

2. Word usage patterns

3. Sentiment of messages (positive, negative, neutral)

4. Peak activity times

5. Emoji usage

6. User-specific activity

This helps in understanding communication habits, emotional tone, and participant dynamics.


Features:

1. Chat Parsing

  Reads WhatsApp chat exported as a .txt file.

  Splits messages and timestamps.

  Separates messages by user.

2. Time-Based Analysis

  Extracts year, month, day, hour, minute from timestamps.

  Generates monthly and daily message timelines.

  Detects peak messaging hours using a heatmap.

3. Message Analysis

  Counts total messages per user.

  Counts total words and most frequent words.

  Identifies group notifications vs individual messages.

4. Visualization

  Line plots for daily/monthly message activity.

  Heatmaps to show activity by day and hour.

  Pie charts showing message distribution per user.

5. Emoji Analysis

  Detects emojis in messages.

  Counts emoji frequency.

  Displays top 10 most used emojis.








Technologies Used:

Python

Pandas (data manipulation)

Matplotlib & Seaborn (visualization)

Regular Expressions (message parsing)

Collections.Counter (frequency counts)










OUTPUT:





outcomes:



Dataframe of parsed messages

Most common words

Monthly and daily timelines

Heatmap of messaging activity

Pie chart of message distribution by user

Top 10 most used emojis






After Preprocessing:


<img width="849" height="397" alt="image" src="https://github.com/user-attachments/assets/d7f0128c-0659-4f50-8feb-d834cf047b5f" />











Visualizations:


<img width="534" height="515" alt="image" src="https://github.com/user-attachments/assets/64e55abe-62a8-431e-9fdc-96912d64aad7" />




<img width="676" height="656" alt="image" src="https://github.com/user-attachments/assets/6368daea-2ec3-4c4a-ba9f-bab482331c3f" />






<img width="343" height="235" alt="image" src="https://github.com/user-attachments/assets/018b7ac5-ef77-480a-b31d-9713cf39d149" />

​

