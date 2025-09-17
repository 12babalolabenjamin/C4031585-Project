# 🏦 FairLoan AI: Bias-Aware Loan Approval System
A fairness-optimized machine learning system that predicts loan approvals while actively mitigating demographic bias through a three-stage fairness pipeline.

## 🌟 Features

- **⚖️ Bias Mitigation**: Three-stage fairness pipeline (pre/in/post-processing)
- **📊 Transparent AI**: SHAP-based explanations for all decisions
- **🚀 Interactive Demo**: Streamlit web application
- **📈 Proven Results**: 60%+ improvement in fairness with minimal accuracy loss

## 🚀 Quick Start

```bash
git clone https://github.com/12babalolabenjamin/C4031585-Project.git
cd C4031585-Project
pip install -r requirements.txt
streamlit run app.py
```

## 🎯 The Problem & Solution

**Problem**: Traditional credit scoring models perpetuate historical biases, leading to unfair lending decisions.

**Solution**: A comprehensive fairness pipeline that maintains high accuracy while ensuring equitable outcomes across demographic groups.

## 🏗️ Architecture

- **Base Model**: XGBoost Classifier
- **Dataset**: German Credit Dataset (1,000 applications, 20+ features)
- **Fairness Pipeline**:
  1. **Pre-processing**: Data reweighting and sampling
  2. **In-processing**: Adversarial debiasing during training
  3. **Post-processing**: Group-specific threshold optimization

**Key Finding**: Significant fairness improvements with minimal accuracy trade-off.

## 📁 Project Structure

```
fairloan-ai/
├── app.py                    # Streamlit demo
├── models/                   # Trained models
├── results/                  # Metrics & visualizations
├── requirements.txt          # Dependencies
└── README.md
```

## 🎮 Demo Features

1. **Loan Decision**: Submit applications, get bias-aware predictions
2. **Performance Analysis**: Compare baseline vs fairness models
3. **Fairness Insights**: Explore bias mitigation effectiveness
4. **Technical Details**: Understanding the methodology

## 🛠️ Requirements

```txt
streamlit>=1.28.0
pandas>=1.5.0
xgboost>=1.7.0
shap>=0.42.0
scikit-learn>=1.3.0
matplotlib>=3.6.0
plotly>=5.15.0
```

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/name`)
3. Commit changes (`git commit -m 'Add feature'`)
4. Push to branch (`git push origin feature/name`)
5. Open Pull Request

## 🔗 Contact

- **Email**: 12babalolabenjamin@gmail.com

---

**⚠️ Disclaimer**: Research prototype. Ensure regulatory compliance for production use.
