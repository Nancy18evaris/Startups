Startup Failure Dataset: Post-Mortem Analysis of 48 Startups
This dataset, sourced from Kaggle. "Startup Failure Post-Mortem" (last updated May 29, 2024), provides insights into why 48 startups failed across various industries, spanning from 2002–2023.

Key Features:
Name: The startup’s name.
Sector: Industry classification (all "Information" here, NAICS 51).
Years of Operation: Lifespan in years, with founding and shutdown years (e.g., "3 (2010-2013)").
What They Did: Brief overview of the startup’s product or service.
How Much They Raised: Funding amount in millions ($M) or tied to parent totals (e.g., "$1.7B (Dropbox)").
Why They Failed: Reason the startup ceased or faded as a standalone entity.
Takeaway: Key lesson derived from the failure.
Giants: 1 if lost to tech giants (e.g., Google, Amazon), 0 if not.
No Budget: 1 if ran out of cash or was underfunded, 0 if not.
Competition: 1 if outpaced by direct rivals (not just giants), 0 if not.
Poor Market Fit: 1 if product lacked demand or user interest, 0 if not.
Acquisition Stagnation: 1 if stagnated or faded after acquisition, 0 if not.
Platform Dependency: 1 if overly reliant on another platform (e.g., Twitter), 0 if not.
Monetization Failure: 1 if couldn’t turn users into revenue, 0 if not.
Niche Limits: 1 if too niche to scale broadly, 0 if not.
Execution Flaws: 1 if mismanagement or tech failures contributed, 0 if not.
Trend Shifts: 1 if market or user trends shifted away, 0 if not.
Toxicity/Trust Issues: 1 if user toxicity or trust breaches hurt, 0 if not.
Regulatory Pressure: 1 if legal or regulatory issues forced closure, 0 if not.
Overhype: 1 if hype exceeded deliverable results, 0 if not.

ALGORITHMS AND TECHNOLOGIES:
Supervised Machine Learning (Categorical from Giants.... to Overhype)  Each column is a categorical column 1=Yes, 0=No,
Programming Languages: Python,
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,
Algorithms: Logistic regression, Decision Trees, Random Forests,
Tools: Jupyter Notebooks, Streamlit for visualization and interactive dashboards.

Use Cases:
Supervised Learning: Predict reasons for failure using classification models (e.g., logistic regression, decision trees).
Exploratory Data Analysis (EDA): Visualize failure causes, sector trends, and funding impacts.
Entrepreneurial Insights: Learn from past mistakes and optimize future startup strategies.



