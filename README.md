# MAPI Framework - README
 
## Introduction
 
MAPI is a framework designed to enhance Clinical Decision Support Systems (CDSS) by incorporating analogy-based reasoning to assist healthcare professionals in making more informed decisions regarding patient diagnosis, treatment, and care. MAPI utilizes case-based reasoning (CBR), an approach in artificial intelligence where past cases are used to solve new problems by finding similarities between them. By applying CBR, MAPI can search for treatment processes that resemble a current patient's case, thereby offering more transparent and interpretable decision support. The framework operates on XES event logs, which capture detailed records of treatment processes. MAPI allows users to define complex and flexible similarity measures on these logs, enabling an analogy-based search that aids clinicians in making informed decisions.
 
### Key Features
 
- **Case-Based Reasoning (CBR):** Leverages CBR, an analogy-based artificial intelligence approach, to identify similarities between patient cases based on procedural treatment data (XES).
- **Similarity Measures:** Allows for the definition of complex and flexible similarity measures on treatment sequences.
- **Process Mining Integration:** Combines CBR with process mining techniques to enhance the analysis of patient treatment pathways.
- **Event Log Analysis:** Facilitates the retrieval of similar patient cases using event logs, supporting evidence-based treatment decisions.
 
## Components
 
The MAPI framework is composed of several components, each playing a crucial role in its functionality. Below are the key components along with their respective GitLab repositories:
 
1. **XES2NEST Converter**: This tool converts XES event logs into workflow models for further analysis.
   - Repository: [XES2NEST Converter](https://gitlab.rlp.net/wi2/onkocase/xestoworkflowconverter)
 
2. **CBR Component**: The core engine for case-based reasoning, enabling the retrieval of similar patient cases.
   - Repository: [CBR Component](https://gitlab.rlp.net/wi2/onkocase/procake-extension)
 
3. **API**: A RESTful API that facilitates communication between different components of the MAPI framework.
   - Repository: [API](https://gitlab.rlp.net/wi2/onkocase/restapi)

4. **Database Component**: Any database such as MySQL or PostgreSQL can be used for the database component. The database can then be connected to the system via the API component.
 
 
## Future Work
 
The current version of the MAPI framework is under continuous development. Future updates will include GitHub links for easier access and integration. We aim to make all components publicly available on GitHub soon. Please stay tuned for further updates.
 
## Citation
 
If you use the MAPI framework in your research, please cite the corresponding paper:


## Main Contributer: 
- Karim Amri, German Research Center for Artificial Intelligence (DFKI), SDS Branch Trier, Trier, Germany

