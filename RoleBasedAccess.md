Role-based Authorization Strategy Plugin configuration

+ CI/CD pipeline is very sensitive to changes & has hard time to recover from failures or user-caused "whoopsies". With that being said: probably do not provide a junior developers with much access to Jenkins, outside of "view" permissions lol - at least until they're familiar enough with the landscape.

+ In a mature security environment usually roles are assigned as "base" roles and then priviledges are extended as needed, providing additional priviledges as assigned roles. Ex.: "developer" role can build and view; but there is no role for a senior developer, so instead senior devs are assigned additional roles that have souped up priviledges. 

+ Here's a good article about that: ```https://plugins.jenkins.io/role-strategy/```
