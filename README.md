# Extracted-Triple-in-CTI-using-LLMs
Cyber Threat Intelligence (CTI) Triple Extraction Using LLMs
This project leverages advanced Large Language Models (LLMs) to extract structured information from unstructured cybersecurity-related text. The goal is to enhance Cyber Threat Intelligence (CTI) by identifying and extracting subject-predicate-object triples that represent relationships between entities such as malware, threat actors, vulnerabilities, and attack methods.

**Objective**:
To create a scalable and efficient system for automatically extracting actionable insights from cybersecurity documents using state-of-the-art LLMs. The extracted triples can be used for constructing knowledge graphs, aiding security analysts in understanding complex relationships within the cybersecurity domain.

**Key Features**:
- Triple Extraction with LLMs: Utilizes powerful models like Llama 2, Llama 3, GTP 4o-mini, and GPT-3.5 Turbo to extract high-quality subject-predicate-object triples directly from raw CTI text.
- Pretrained and Fine-Tuned Models: Employs fine-tuned LLMs optimized specifically for CTI data to ensure accurate and relevant extractions.
- Noise Filtering: Implements postprocessing steps to validate and filter extracted triples, ensuring the quality of the output.- 
- Knowledge Graph Integration: Facilitates the visualization and exploration of relationships between extracted cybersecurity entities.
- Evaluation Metrics: Measures performance using precision, recall, and F1-score to validate the effectiveness of the extraction pipeline.
  
**How It Works**:
- Data Ingestion: Load raw CTI data, such as malware reports, attack descriptions, and threat actor profiles.
LLM-based Triple Extraction: Use state-of-the-art LLMs to extract structured triples (subject-predicate-object) from text without manual feature engineering.
- Postprocessing and Validation: Filter out irrelevant or low-confidence triples, ensuring meaningful and accurate outputs.
- Knowledge Graph Construction: Transform the extracted triples into a structured graph format for easy visualization and querying.
- Evaluation: Assess the system’s accuracy and relevance using standard metrics to fine-tune and improve the pipeline.
  
**Technologies Used**:
- Python: Core language for developing the pipeline and integrating tools.
- LLMs (Llama 2, Llama 3, GTP 4o-mini, and GPT-3.5): Models for extracting triples and understanding complex cybersecurity contexts.
- Jupyter Notebooks: For interactive development and experimentation.

**Future Enhancements**:
- Real-time Analysis: Expand the pipeline to process live CTI streams for real-time threat analysis.
- Model Expansion: Explore the integration of newer LLMs for improved accuracy and broader support.
- Integration with Security Tools: Connect the pipeline to existing cybersecurity platforms for seamless integration and analysis.
- Postprocessing Algorithms: For cleaning and validating extracted triples.
**Benefits**:
- Automated Insights: Automates the extraction of critical relationships from unstructured text, saving time and effort for security analysts.
- Advanced Intelligence Analysis: Enables analysts to uncover complex relationships between malware, vulnerabilities, and threat actors with minimal manual intervention.
- Future-Proof System: Built on LLMs that can adapt to evolving cybersecurity terminology and contexts
