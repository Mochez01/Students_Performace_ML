# Student Performance Prediction Project

## Overview
This project focuses on predicting student academic performance using machine learning techniques. It addresses Sustainable Development Goal 4 (Quality Education) by helping identify students who might be at risk of underperforming academically, enabling early intervention and targeted support.

## 🎯 SDG Problem Addressed
- **SDG 4: Quality Education**
  - Promotes inclusive and equitable quality education
  - Supports lifelong learning opportunities for all
  - Aims to identify at-risk students early
  - Enables data-driven educational interventions
  - Helps optimize resource allocation

## 🤖 Machine Learning Approach
- **Model Type**: Simple Linear Regression
- **Dataset**: [Student Performance Dataset on Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)
- **Predictor Variable**: Reading score
- **Target Variable**: Math score
- **Train-Test Split**: 80-20
- **Evaluation Metrics**: R² and Mean Squared Error (MSE)

## 📈 Results
- **R² Score**: 0.73 (73% of math score variation explained by reading scores)
- **Model Coefficient (Slope)**: 0.83
- **Mean Squared Error (MSE)**: 72.74

## ⚖️ Ethical Considerations
- Avoid reinforcing existing biases based on socioeconomic or demographic factors
- Do not use predictions in isolation for high-stakes decisions
- Maintain data privacy and fairness
- Ensure transparency in model implementation
- Consider underrepresented groups and students with learning differences

## Project Structure
```
student_performance/
├── student_performance.ipynb    # Main Jupyter notebook
├── README.md                    # Project documentation
└── StudentsPerformance.csv            # Project Dataset
```

## Getting Started
1. Clone the repository
2. Install the required dependencies
3. Open and run the Jupyter notebook


## Future Improvements
- Incorporate additional predictor variables
- Explore more complex machine learning models
- Add data visualization components
- Implement cross-validation
- Include demographic analysis

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

