# vitaminE-Equitable-AI-for-Dermatology
## Team Members
- [Emily-Ann Willix](https://github.com/emilyannwx)
- [Kymari Bratton](https://github.com/Kymari28)
- [Gianna Lamarre](https://github.com/gialam25)
- [Fernanda Del Toro](https://github.com/Fernandadeltoro)
- [Maria Santos](https://github.com/dsanmar)

## Project Highlights

- Developed a deep learning model using EfficientNetB0 with transfer learning to classify 21 skin conditions.
- Achieved a public leaderboard F1 score of **0.47666** on Kaggle.
- Addressed AI fairness in dermatology through targeted data augmentation and class rebalancing.
- Incorporated exploratory data analysis and image preprocessing to understand dataset diversity and quality.
- Evaluated model performance and highlighted limitations in accuracy across skin tones.

[Link to Kaggle Competition Page](https://www.kaggle.com/competitions/bttai-ajl-2025/overview)

## Setup & Execution

To run the notebook and reproduce our results:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo-name/vitaminE-Equitable-AI-for-Dermatology.git
    cd vitaminE-Equitable-AI-for-Dermatology
    ```

2. (Optional) Set up a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # For Windows: .\env\Scripts\activate
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the dataset from Kaggle and place it in the `data/` folder as per the competition rules.

5. Launch Jupyter Notebook and open:
    ```
    maria-s-notebook.ipynb
    ```

## Project Overview
This project is part of the Break Through Tech AI Fellowship in collaboration with the Algorithmic Justice League (AJL). Our goal was to build an inclusive machine learning model that can accurately classify 21 different skin conditions across diverse skin tones. The competition emphasizes not only performance but also fairness and inclusivity in healthcare AI.

## Real-World Significance
AI in healthcare often underperforms for people with darker skin due to biased training data. Our model aims to improve diagnostic accuracy and promote fair healthcare for all.

## Dataset & Approach

- **Dataset**: A subset of FitzPatrick17k, containing 4,500 images covering 21 skin conditions across different skin tones.
- **Preproccessing**: Cleaned data, applied augmentation, and analyzed class distribution.

## EDA Visualizations
![Plot Distrubitions](images/Fernanda_plot_distributions.jpg)
