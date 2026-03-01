# What's Ansible? 
## Read the docs here 
https://codefinity.com/courses/v2/142e6e71-0b2c-4a6f-800c-f5bf43afa550/7161cb9c-3519-4154-a2b6-fd954cc91a25/b10804d2-f326-4f75-9ee8-617533e224f4?utm_source=google&utm_medium=cpc&utm_campaign=23596924742&utm_content=&utm_term=&dki=&ad_id=&gad_source=1&gad_campaignid=23596931663&gbraid=0AAAAABTeUgQlHMtnM0TJndEQpRibOwPac&gclid=Cj0KCQiA5I_NBhDVARIsAOrqIsaJLYUWDRdH_1B6Cf0fl29r011oKOPjHB2w-dnvw8w1NTEeXmosS4oaAiXCEALw_wcB

Read the official ansible docs. Make sure you understand all the concepts before starting the exercise. 

https://docs.ansible.com/projects/ansible/latest/getting_started/

## Exercise: 
1. Deploy gitlab on this vm using ansible. (You can run  ansible when the tagret host is localhost). 
    Before deploying, check that this vm has enough resources. 

2. Add a node exporter (prometheus) that collects data and sends it to the prometheus + grafana Lev created. Check that you can see all the important metrics (including gitlab's metrics, like available repositories etc.)

3. Create another "tasks" file that upgrades the gitlab instance you've created. 


