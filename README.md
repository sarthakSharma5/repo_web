# repo_web
repo to test Kubernetes integration

Neccessary updates before using code to mail: mail.py
1. line-10: provide sender's mail address
2. line-11: provide app password, create before-hand
3. line-15: add/remove recievers' addresses
4. line-16: to edit the subject of mail to send
5. line-17: edit the body of the mail

To use the Dockerfile a pre-configured Single-Node Kubernetes Cluster is must.
Copy the 4 files to the same directory where the Dockerfile is present
1. ca.crt
2. client.crt
3. client.key
4. config file

for better understanding visit: https://www.linkedin.com/pulse/integrating-jenkins-kubernetes-sarthak-sharma
