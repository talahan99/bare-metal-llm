# Bare-Metal LLM

## Overview
The **Bare-Metal LLM** project is a research-driven initiative focused on developing a **Linux-powered LLM environment** for **local use**, separate from network dependencies.  

This is the first phase of a larger project that will serve as the **structural foundation** for a **containerized LLM**, combining contextual and generative AI models.  

### Long-Term Goals:
- **Uses user-defined weights** instead of rigid, centralized training models.
- **Employs an objectively coded framework** to maintain usability, avoiding restrictive design biases.
- **Supports both containerized deployment and bare-metal installation**, ensuring flexibility for different environments.

Currently, the project is in the **bare-metal phase**, built and tested in a **local environment** before evolving into a containerized solution.

---

## Technical Details
- **Current OS:** macOS (for initial development & testing)
- **Final Target OS:** Hardened **Gentoo Linux** (optimized for performance & security)
- **Hardware:** Home server deployment, with future containerized support
- **Model:** [Llama 3](https://github.com/facebookresearch/llama)
- **Core Dependencies:**  
  - Python  
  - PyTorch  
  - Transformers  
  - Audio processing tools  
  - Additional necessary Llama 3 dependencies  

This setup is designed for **maximum modularity**, allowing easy adaptation to different computing environments.

---

## Repository Structure
The repository is organized as follows:

- **`llm/`** – Core LLM files and execution logic  
- **`startHere/`** – Essential setup files  
  - `README.md` – This document  
  - `setup.sh` – Automated setup script  
  - `config.yaml` – Core configuration file  
- **`scripts/`** – Automation, utility, and deployment scripts  
- **`models/`** – Pre-trained or fine-tuned LLM models  
- **`data/`** – Datasets for training/testing  
- **`logs/`** – System logs and error tracking  
- **`.gitignore`** – Ignore unnecessary files  
- **`LICENSE`** – *(Optional)* License file  
- **`requirements.txt`** – Dependency list (if using Python)  

---

## Installation & Setup

### **Process Overview**
1. **Ensure dependencies are installed**  
   - Python 3.8+  
   - Git  
   - Required Python packages  
   - *(Optional)* Container runtime (Docker/Podman for later deployment)  

2. **Clone the repository**  
   - Retrieve the latest version from GitHub  

3. **Run the setup script**  
   - Installs dependencies  
   - Configures core directories and environment  

4. **Verify setup**  
   - Confirm installation of required components  
   - Validate directory structure  

5. **Manual configuration (if needed)**  
   - Adjust model paths and dependencies  
   - Customize framework settings  

---

## Usage
Currently, Bare-Metal LLM is **CLI-based**

## Future Plans

This project is evolving through multiple phases:

- ✅ **Phase 1:** Bare-metal implementation *(current phase)*  
- ⬜ **Phase 2:** Containerized deployment *(Gentoo Linux target)*  
- ⬜ **Phase 3:** Hybrid contextual/generative model integration  
- ⬜ **Phase 4:** Backend deployment for external system interaction  

---

## License  

*(Private for now; licensing to be determined in later phases.)*  

---

## Contributions  

This project is currently private. Contribution guidelines will be provided in future phases.  

