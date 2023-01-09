# GG-takehome
### Hello Reader! 
#### Responses to Questions: 
1. What would you do differently on a managed cluster (EKS, GKE…) regarding step 4?
I would configure a loadbalancer, service and ingress for the traffic. 

2. How would you monitor the application?
Through prometheus or other monitoring application from a sidecar

3. What would you change to add a PostgreSQL container?
Add a post gres container and a secrets yaml to protect the senitive contents of the DB

4. Provide us some feedback on this test:
    
    ○ Duration: is it too long, too short or adequate?
        
        Adequate
    
    ○ Difficulty: on a scale from 0 (easy) to 10 (hard), how would you rate the difficulty
    of this test?

        5 - It was an interesting ask to place the script within the configmap. That was fun! 

    ○ Did you find the test interesting? If not, please tell us why

        Yes! It gave me an opportunity to explore a little deeper into command script injections within a 
        kubernetes environment.  