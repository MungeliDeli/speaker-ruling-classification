# Parliamentary Speaker's Rulings Classification Project

This project aims to develop an automated text classification system to categorize Speaker's Rulings from the National Assembly of Zambia into predefined categories, enhancing accessibility for legal, parliamentary, and public use.

---


# Business Understanding

## Problem Statement 
The National Assembly of Zambia generates substantial volumes of parliamentary proceedings containing Speaker's Rulings on various procedural, disciplinary, and administrative matters. Currently, accessing and categorizing these rulings for legal research, parliamentary reference, and civic education requires extensive manual effort. Legal professionals, researchers, parliamentary staff, and citizens face significant challenges in efficiently locating relevant precedents and understanding patterns in parliamentary decision-making.
### Core Problem: 
There is no automated system to classify and categorize Speaker's Rulings from Zambian parliamentary proceedings, making legal and legislative information retrieval inefficient and limiting effective civic education and parliamentary research.

## 1. Business Understanding
### Primary Objectives: 
1. To classify parliamentary rulings into a structured system that is simpler to analyze and 
evaluate  
2. Organize speakers' rulings to improve accessibility and quick retrieval for legal 
professionals, researchers, and public understanding.  

### Success Criteria from Business Perspective:  
- Reduce time spent by legal professionals searching for relevant rulings by at least 60% 
- Enable non-experts to find and understand parliamentary rulings relevant to their interests 
- Provide parliamentary staff with consistent categorization for improved procedural reference 
- Support academic and policy research through structured access to historical ruling patterns 

## 2. Data Mining Goals
### Specific Technical Objectives
1. **Build a Multi-class Classification Model:**  
   Develop a machine learning system that automatically categorizes Speaker's Rulings into predefined categories such as.
    - **Procedural Rulings** (e.g., points of order, procedural motions)
    - **Disciplinary Actions** (e.g., member conduct, sanctions)
    - **Administrative Decisions** (e.g., scheduling, resource allocation)
    - **Constitutional Interpretations** (e.g., constitutional questions, legal precedents)
    - **Debate Management** (e.g., time allocation, speaking order)

2. **Implement Natural Language Processing (NLP):**  
   Apply text mining techniques to extract meaningful features from parliamentary text documents, enabling accurate classification.

3. Create automated pipeline for new ruling classification.

### Technical Success Metrics 
* Accuracy: Achieve at least 80% overall classification accuracy across all ruling categories 
* Precision: Maintain precision above 75% for each individual category to ensure reliable 
categorization 
* F1-Score: Target F1-score above 77% for balanced precision-recall performance
## 3. Project Success Criteria
### Quantitative Criteria
1. **Model Performance:** Overall classification accuracy ≥ 80%
2. **Processing Speed:** System should classify new documents within 5 seconds
   
### Business Impact Measures:
- Reduction in manual categorization time
- Increased usage of parliamentary information by researchers and citizens 
- Improved consistency in referencing past rulings by parliamentary staff 
- Enhanced accessibility of legal and legislative information for civic education


## 4. Project Scope
### In Scope:  
- Speaker's Rulings from National Assembly of Zambia proceedings 
- Text-based classification using parliamentary Hansards and official records 
- English language processing 
### Out of Scope:  
- Rulings from other parliamentary bodies or courts 
- Non-English parliamentary proceedings  
- Real-time audio/video processing of parliamentary sessions 
- Legal advice or interpretation of ruling implications
### Constraints:
- Data availability limited to publicly accessible parliamentary records
- Solution must be cost-effective for potential implementation by parliamentary services
- Timeline constraints require deliverable completion by August 29, 2025


## 5. Contributors
- **Team Leader:** Davy Mwansa
- **Team Members:** Joseph Likando, Webster Daka, Chunda Luchembe, Chikondi Banda
