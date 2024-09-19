# End-to-end perfect pipeline project using DVC, MLFlow, AWS, Databricks

1. Into & Github setup
- git clone <repo_link>
- run __code .__

2. Project template creation
- script <template.py>
- run __python template.py__

3. Setup & Requirements (poetry) & (pip)
- (case poetry) pip install poetry 
- poetry init 
- add below the [tool.poetry] > package-mode = false
- poetry add <package_name>@<version><latest>
- conda create -n <enviroment_name> python=<version> -y
- conda activate <enviroment_name>
- (case pip) pip install -r requirements.txt

4. Logging, Utils & Exception Module
- logger at src/`__init__.py`
- exceptions at utils/common.py

5. Workflow
- update config.yaml
- update secrets.yaml [optional]
- update params.yaml
- update entity
- update src/config/configuration.py
- update components
- update pipeline
- update main.py
- update dvc.yaml
- build app.py [lastest]

6. Notebook Experiments

7. Modular code implementation

8. Training pipeline

9. MLFlow (for experiments and model registration)

10. DVC (for pipeline tracking and implementation)

11. Prediction pipeline & app creation

12. Docker

13. Final CI/CD deployments on AWS