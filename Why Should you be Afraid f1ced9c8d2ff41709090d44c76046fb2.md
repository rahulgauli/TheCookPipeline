# Why Should you be Afraid?

**Let's Achieve 99% Resiliency:** 😀, **I call This the CookPipeline**

The CI/ CR / CD Pipeline

Continuous Integration/ Continous Resiliency / Continous Development 

n = {0,1,2,3,4,5,6,7,8,9}

Initial Stable Release: v0.0.1
Stable Version Release: A version of an application with over 3 Months of active runtime with error margins of ~0.5%.
Faulty Version Release: [v0.0.1, v0.0.2, v0.0.5]
Current Version: v(n).(n).(n)

Resiliency Success Rate Verification for the shared IT platform: 
This is a Cyber Security Bot for resiliency and enhanced CICD pipelines. In Its memory, we store the variables( An Image Build ) above and compute Logical Secure Resilient calculations. Calculations may include the following different steps: 

- Couples an analysis of two different forms of data:
    - In the NonPord Environment:
    - For a Particular Date and Time: {Deployed Version Logs: [Non-Prod Deployed Version Log Files ], Errors: [Error Scanner Bot( non-prod-mezmo ) ],  200s: Success Scanner Bot[Non-Prod Success Rate For all APIs ] }
    - In the Prod Environment:
    - For a Particular Date And Time: {Deployed Version Logs: [ Prod Deployed Version Log Files ], Errors: [Error Scanner Bot( Prod-Mezmo-deployment ) ], 200s: Success Scanner Bot[ Non Prod Success Rate for all APIs ] }
    - Calculations:
        - Non-Prod Version Result:
        
        ```yaml
        Reusable_Workflow_BluePrint: 
        
        Input:
        	To-Release: str 
        Process:
        	- ErrorRateResiliency:
        		Output: 
        			Success: True/False
        	- PossibleSecrets:
        		Output:
        			Success: True/False 
        	- DeploymentAllowed:
        		Output:
        			Success: True/False
        Output:
        	- To-Release-Version: int
        
        ```
