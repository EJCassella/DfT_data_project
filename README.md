# DfT_data_project

---

## Project aim:

- Use the Casualty and Collision data from the Department for Transport (2018 - 2022) to classify accidents in South Yorkshire as less serious (0, 'Slight') or serious (1, including 'Serious' and 'Fatal' crashes).

- Identify which conditions lead to the most serious incidents.

---

## Project Progress:

1. Data downloaded from the DfT repository, categories decoded, and 'Casualty' and 'Collision' data joined.

2. Data cleaned to remove missing data. Shapely geometry points calculated for GIS mapping purposes (to remove before modelling).

3. Exploratory data analysis - Who is involved in crashes? Where do they happen? When do they happen? What factors seem to be contributing to the most serious events?

4. Baseline models - dummy classifier and a baseline R.F. with no feature selection / engineering.

5. Feature selection and engineering Episode I.

6. Data modelling Episode I.

7. (to do) Feature selection and engineering Episode II.

---

### To-do (maybe)

- PCA analysis shows there is still a lot of feature bloat. Let's trim some fat.

- Casualty_type is clearly an important indicator, but we're adding a lot of features with the One-Hot Encoding. Can we enforce the importance of this feature by target encoding each category?

- This would be cool data for a dashboard.

- Re-dig into the EDA to look a bit more closely at which features are related to the seriousness of the crash (and combine the Serious and Fatal categories sooner)
