# GitHub Users in Delhi 📊

Dive into this dataset capturing the thriving GitHub community in Delhi! We’ve gathered data on Delhi-based users with over 100 followers and their public repositories, creating a powerful dataset for exploration and insights.

## 📁 What's Inside?

1. **`users.csv`** – 422 GitHub profiles from Delhi with detailed user data.
2. **`repositories.csv`** – 29,760 repositories recently pushed by these users, showcasing projects, languages, and popularity metrics.
3. **`gitscrap.py`** – The Python script that scrapes user and repo data straight from the GitHub API.

## 🛠 Data Collection Details

- **API Used:** GitHub API
- **Collection Date:** 2024-10-23
- **Filters Applied:** Users with 100+ followers
- **Repo Limit:** Up to 500 of the latest pushed repositories per user

## Intresting findings 

- **Language Preferences**:
  - JavaScript is the most widely used language among developers.
  - For users registered after 2020, HTML is the most popular language.
  - Svelte, while niche, has the highest average star rating per repository, indicating strong community interest in content-focused and documentation-driven projects.

- **Follower and Repository Trends**:
  - There is a very weak negative correlation between the number of followers and public repositories, suggesting that creating more repositories does not significantly impact follower count.
  - Regression analysis shows that adding more repositories has a minimal effect on attracting additional followers.

- **Feature Enablement Patterns**:
  - A slight negative correlation exists between enabling projects and wikis within repositories, indicating that developers don’t typically activate both features together.
  
- **Key Takeaways**:
  - Developer activity shows varying interests, with strong engagement in content-centric languages like HTML and Svelte.
  - Patterns reveal that while certain features are available, they may not be utilized in tandem, reflecting specific user behaviors in repository management.

