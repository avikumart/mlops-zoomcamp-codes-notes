
# Module 3: Workflow Orchestration and ML pipelines notes

**Prefect workflow**

- Install prefect on local
- add them (functions) all to a flow and run locally 
- Turn functions into tasks
- parameters and type checking
- show the local UI and the flow run information

**Prefect - Workflow chaining tool**

- It chains and manages tasks together to ensure reliable deployment for ML models.
- It enables reproducibility and observebility for ML workflow
- It enables automation of training of ML models and deployment on a regular interval
- Modularity - It is also a modular in design enabling easier modifications, logging, storing and handling of the state

**Negative engineering tasks**

- Re-tries and API go down
- Malformed data
- Notifications
- Observability into failure
- Conditional failure logic
- Timeouts

**Remote prefect deployment**

- Open port on AWS VM
- Install prefect on VM
- Configure prefect on server as remote VM
- Start prefect Orion

**Prefect flow:**

Set a modular code under @ task decorator —> Create a prefect flow @ flow 

—> deploy on local or remote machine
