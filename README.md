# Holistic AI & UCL Hackathon: Advanced Stereotype Detection System  

## **Overview**  
This project addresses stereotype detection, focusing on identifying and mitigating bias in textual data using advanced AI techniques. 
Leveraging the **Expanded Multi-Grain Stereotype Dataset (EMGSD)**, this system incorporates fairness, explainability, and sustainability 
to create a trustworthy and robust solution for stereotype classification and mitigation.  

---

## **Problem Statement**  
Detecting and mitigating stereotypes in textual content is critical for creating ethical and inclusive AI systems. 
Traditional models often struggle with fairness, robustness, and explainability, limiting their trustworthiness and real-world applicability.  

This project aims to:  
1. Classify text into **stereotype**, **neutral**, or **unrelated** categories.  
2. Identify token-level stereotypes for nuanced understanding.  
3. Build a fair, robust, and sustainable system adhering to ethical AI principles.  

---

## **Objectives**  
- Develop a **multi-grain stereotype detection system** that operates at sentence and token levels.  
- Ensure fairness by evaluating the model across different demographic subgroups.  
- Provide explainable predictions using tools like SHAP and LIME.  
- Optimize for sustainability using carbon-efficient techniques.  

---

## **Solution Overview**  
The system fine-tunes multiple transformer models (BERT, RoBERTa, DistilBERT) on the EMGSD dataset, incorporating:  
- **Data Augmentation**: Enhanced dataset diversity for better generalization.  
- **Explainability Tools**: SHAP and LIME to visualize model predictions.  
- **Fairness Metrics**: Bias testing with Fairlearn and AIF360.  
- **Robustness Testing**: Evaluation on adversarial and out-of-distribution samples.  
- **Sustainability**: Energy-efficient techniques with CodeCarbon for emissions tracking.  

---

## **System Design**  
The system follows a modular architecture:  
1. **Data Preprocessing**: Text normalization, tokenization, and data augmentation.  
2. **Model Fine-Tuning**: Training transformer models for multi-grain stereotype detection.  
3. **Evaluation**: Performance measured using F1 Score, Fairness metrics, and Explainability fidelity.  
4. **Deployment**: Easily integrable API or cloud-based deployment for real-world usage.

---

## **Value Proposition**  
### **Business Value**  
- Enables organizations to create inclusive and culturally sensitive content.  
- Useful in content moderation, education, marketing, and global collaboration.  

### **Academic Value**  
- Contributes to the growing research on ethical AI systems.  
- Proposes novel solutions for stereotype detection and mitigation.  

---

## **Risk Considerations**  
This project addresses the following risks:  
1. **Performance**: Evaluated using rigorous metrics and adversarial testing.  
2. **Fairness**: Bias analysis across demographics with fairness tools.  
3. **Robustness**: Ensures reliability in diverse and unseen environments.  
4. **Privacy**: Incorporates differential privacy for sensitive data handling.  
5. **Explainability**: Uses SHAP and LIME for transparent decision-making.  
6. **Sustainability**: Tracks energy consumption to minimize environmental impact.  

---

## **Future Work and Limitations**  
### **Future Work**  
- Expand dataset with diverse cultural contexts.  
- Integrate real-time feedback mechanisms for active learning.  
- Extend to multi-modal data for better contextual understanding.  

### **Limitations**  
- Dataset limitations may affect cultural representation.  
- Model performance may vary in extremely low-resource languages.  

---

## **How to Use**  
1. **View files**  
   ```bash
   -src
   
