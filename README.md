ShieldSG: Adversarially Robust Toxicity Detection using BERT

ShieldSG is a BERT-based toxicity detection framework designed to improve the robustness of transformer models against adversarial text attacks. The project combines attention-head interpretability, selective head suppression, adversarial training, and game-theoretic optimization to build a reliable and efficient content moderation system.

🚀 Features
Fine-tuned BERT for toxic comment classification.
Performed attention-head analysis to identify vulnerable and crucial transformer heads.
Implemented semantic adversarial attacks using TextAttack to evaluate model robustness.
Applied selective attention-head suppression to improve robustness while preserving model accuracy.
Developed a game-theoretic attacker–defender framework to determine the optimal defense strategy.
Enhanced robustness using adversarial training, dynamic re-suppression, and randomized inference.
📊 Results
✅ Clean Accuracy: 95.1%
✅ Adversarial Accuracy: 89.4%
✅ 41.8% reduction in inference time
✅ Significant improvement in robustness against semantic adversarial attacks
🛠️ Tech Stack
Python
PyTorch
Hugging Face Transformers
BERT
TextAttack
Scikit-learn
Kaggle GPU
📂 Datasets
Jigsaw Toxic Comment Classification Dataset
ToxiGen Dataset
🔬 Research Highlights
Identified vulnerable attention heads using interpretability techniques.
Optimized transformer defenses through a Stackelberg game-theoretic framework.
Demonstrated an effective trade-off between model accuracy and adversarial robustness.
📄 Research

This project is based on our research work "ShieldSG: A Game-Theoretic Framework for Adversarially Robust Transformer-Based Toxicity Detection." It investigates interpretable and robust transformer defenses against semantic adversarial attacks for content moderation systems.
