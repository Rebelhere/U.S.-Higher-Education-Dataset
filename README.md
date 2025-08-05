#  U.S. College Dataset (6,429 Institutions)

This repository hosts a curated and structured dataset containing comprehensive information about 6,429 U.S. colleges. The main aim of this project was to collect, clean, and organize institutional data to publish a high-quality dataset on [Kaggle](https://www.kaggle.com/). The dataset is ideal for data science, machine learning, and statistical analysis projects related to education in the United States.

---
## Repository Contents

* `U.S._College_information_Real_dataset.csv`
  → Final processed dataset ready for use
* `US_College_dataset.ipynb`
  → Jupyter Notebook used to explore, clean, and prepare the data
* `README.md`
  → Project description and dataset documentation

---

##  Dataset Overview

| Column                              | Description                                                                      |
| ----------------------------------- |

| `zip`                               | ZIP code of the institution                                                      |

| `city`                              | City where the college is located                                                |

| `name`                              | Official name of the college                                                     |

| `alias`                             | Alternate or abbreviated names (if any)                                          |

| `state`                             | U.S. state abbreviation (e.g., NY, CA)                                           |

| `locale`                            | Location classification (urban, suburban, rural)                                 |

| `address`                           | Full street address of the college                                               |

| `dolflag`                           | Department of Labor identifier flag (binary)                                     |

| `branches`                          | Number of branch campuses                                                        |

| `ownership`                         | Type of institution (0 = Public, 1 = Private Non-Profit, 2 = Private For-Profit) |

| `main_campus`                       | Flag for main campus (1 = Yes, 0 = No)                                           |

| `state_fips`                        | FIPS code representing the U.S. state                                            |

| `religious_affiliation`             | Religious affiliation (if any, as a coded value)                                 |

| `tuition_revenue_per_fte`           | Tuition revenue per full-time equivalent student                                 |

| `instructional_expenditure_per_fte` | Instructional cost per full-time equivalent student                              |

| `peps_ownership`                    | PEPS (Postsecondary Education Participants System) ownership label               |

| `faculty_salary`                    | Average faculty salary (USD)                                                     |

| `online_only`                       | Flag indicating if college is fully online (1 = Yes, 0 = No)                     |

>  Total Records: **6,429**
>  Total Columns: **18**

---

##  Use Cases

This dataset can be used for:

* Data visualization and statistical summaries
* Ownership-type impact on tuition, faculty salaries, and online education
* Clustering colleges based on characteristics (e.g., cost, location)
* Predictive modeling (e.g., completion rate, tuition forecasting, etc.)

---

##  How This Dataset Was Built

The dataset was curated through:

* handling categorical codes
* Normalizing key features for consistency
* Structuring the dataset for easy use in Kaggle notebooks

> For step-by-step processing and EDA, refer to `US_College_dataset.ipynb`.

---

##  How to Use

You can either:

* Download the CSV directly from [Kaggle Dataset Page](https://www.kaggle.com/datasets/muhammadrahimusman12/u-s-college-information-data-set/data) 
* Or clone this repo and use it locally:

```bash
git clone https://github.com/Rebelhere/us-college-dataset.git
cd us-college-dataset
```

Then open the notebook:

```bash
jupyter notebook US_College_dataset.ipynb
```

---

## Credits

**Dataset Creation & Curation**: [Muhammad Rahim Usman](https://github.com/Rebelhere)

---

##  Related Links

*  [Kaggle Dataset Link](https://www.kaggle.com/datasets/muhammadrahimusman12/u-s-college-information-data-set/data)
*  [Rebelhere](https://github.com/Rebelhere)

---
