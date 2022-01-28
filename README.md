# demo

# requirments
    - Distroless container https://github.com/GoogleContainerTools/distroless
    - Runtime RKT 

# flow 

- commit - 
  - simple pre-commit hook checks.
  - no dev, stage , prod branches to build off.   

- build -  
  - container security
    - scm/dca.
    - flag pass/fail.
    - cannot proceed past dev. 
  - outputs 
         - generic container 
         - abstracted configuration

- deployment 
    - triggers 
        - new container version. (versioning strategy)
        - new manifest.
        - new variable / configuration change.
    - promotion
        -> dev 
        -> stage
        -> prod 

# prod ready dashboard 
    - prod ready score. 

