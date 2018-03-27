ansible-elk
===========
Ansible Playbook for setting up the ELK Stack on remote hosts


## What does it do?
   - Automated deployment of a ELK (Elasticsearch , Logstash & Kibana) on Redhat family (redhat , centos , fc)
     * Install ELK stack 6.x.
     * Uses Nginx as a reverse proxy for Kibana
     * Create username and password to access Kibana
    
## What is next?
   - Generates SSL certificates for Filebeat
   - Install and configure Filebeat
   - Configure Logstash filters for nginx , aws services
   
## Notes
   - Modify the Kibana password from Kibana variables file
