<h1 align="center">AI and Data Jobs Tweets Sentiment Analysis</h1>

<div style="text-align:center;">
    <img src="https://i.imgur.com/4yRKIg2.jpg" alt="project-banner">
</div>

---
- [Introduction](#introduction)
- [Aim of this analysis](#aim-of-this-analysis)
- [Data](#data)
- [Conclusion](#conclusion)
  - [Findings Summary](#findings-summary)
- [Acknowledgments](#acknowledgments)


# Introduction 

AI is significantly impacting data jobs, such as data science, analysis, and engineering. With AI, these jobs are becoming more efficient and effective, leading to faster and more accurate analysis. However, as AI continues to develop rapidly with the emergence of new tools and implementations, some individuals may struggle to adapt to the changes. This may result in a scarcity of professionals, particularly as the new AI tools replace some jobs, leading to layoffs and unemployment.

---

# Aim of this analysis

- The goal of this project is to analyze the sentiment and public opinion surrounding AI and data jobs on Twitter.

---

# Data

The data was scrapped by the [snscrape](https://pypi.org/project/snscrape/) python module, the scrapping code is on a google colab notebook, for some reason i keep getting network errors when i run the code inside a kaggle notebook. Please leave a comment below if you know how to address this issue.

### [Scrapping Twitter Data - Notebook](https://colab.research.google.com/drive/1UCfnbtno2Bvhz3Xh0S9L6HJ285_lADZK?usp=sharing)<!-- omit in toc -->

### [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1UCfnbtno2Bvhz3Xh0S9L6HJ285_lADZK?usp=sharing)<!-- omit in toc -->

---

# Conclusion

The sentiment analysis showed that most tweets' sentiments were neutral. However, after six months of decline, the sentiment score spiked following the release of ChatGPT. The analysis also revealed that the topic of AI and its tools is still relatively new, with people unsure of what to think about these emerging technologies. As AI continues to evolve, it will undoubtedly impact the data professions and jobs landscape, leading to significant changes in the field.

## Findings Summary

- Most of the tweets sentiments labels are Neutral by **~69%**.
    <details>
    <summary>Click to View Visulaization.</summary>

    ![Alt text](Assets/percentage%20of%20sentiment%20labels.png)
    </details>

****

- The topic of AI related to data jobs has seen a decline in the sentiment score from the **beginning of July to December**. 
    <details>
    <summary>Click to View Visulaization.</summary>

    ![Alt text](Assets/sentiment%20score%20trend.png)
    </details>

****

- The release of Chat-GPT on November 30, 2022 **spiked** the sentiment score up again.

    <details>
    <summary>Click to View Visulaization.</summary>

    ![Alt text](Assets/Chat-GPT%20release%20effect%20on%20sentiment%20score%20trend.png)
    </details>

****

- Data analysis has the most **steady and consistent** sentiment trend ***COMPARED*** to data science and data engineering.

    <details>
    <summary>Click to View Visulaization.</summary>
    
    ![Alt text](Assets/data%20analysis%20trend.png)
    </details>

****

- Data engineering sentiment score didn't increase like the other job titles on the release date of chat-GPT, but a **significant increase on the month of February**.

    <details>
    <summary>Click to View Visulaization.</summary>

    ![Alt text](Assets/de%20trend.png)
    </details>

# Acknowledgments

- [Chat-GPT](https://chat.openai.com/) - Editing and modifying visualizations.

- [Rob Mulla Video about scrapping Twitter using snscrape.](https://www.youtube.com/watch?v=PUMMCLrVn8A&pp=ygUIc25zY3JhcGU%3D) - Scrapping Twitter.

- [Canva](https://www.canva.com/) - Banner design.

