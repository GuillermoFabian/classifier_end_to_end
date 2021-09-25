# ML pipeline
Full End to End pipeline with Mlflow and Hydra in a Conda Enviroment that
produces a trained Random Forest model and save and store resuils in W&B

## Preliminary step: create a repository and commit and push the starter kit

### Running the full steps

  ```bash
  mlflow run . -P hydra_options="main.execute_steps='random_forest'"
  ```
 ### For testing purposes 
  ```bash
  mlflow run . -P hydra_options="main.execute_steps='random_forest'"
  ```
  and this executes ``download`` and ``preprocess``:
  ```bash
  mlflow run . -P hydra_options="main.execute_steps='download,preprocess'"
  ```
