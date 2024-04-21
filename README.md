" REALTIME LOG MONITORING IN KUBERNETES USING EFK STACK "

*ELASTICSEARCH    * FLUENTD     *KIBANA 
            
INTRODUCTION :

Hello everyone, I'm Elamparithi M, a DevOps engineer passionate about innovative projects in DevOps and cloud environments. Recently, I completed an exciting monitoring project focusing on Kubernetes cluster log management using the EFK (Elasticsearch, Fluentd, Kibana) stack. Through this project, I delved into real-time monitoring workflows, log collection from containers using Fluentd, log extraction, and storage leveraging Elasticsearch. Additionally, I developed a visually appealing dashboard in Kibana to facilitate efficient log management.

PROJECT EXPLANATION :

The primary objective of this project is to monitor Kubernetes pods and application logs. The workflow entails aggregating logs from containers using Fluentd, which subsequently transfers the log data to an analytic engine, Elasticsearch. Upon receipt, Elasticsearch organizes the logs into documents and maps the data into index format for robust analysis and visualization. Finally, Kibana is utilized to visualize the logs through dashboards and charts. Kubernetes components such as deployments, services, daemon sets, stateful sets, cluster roles, cluster role bindings, service accounts, persistent volumes (PV), and persistent volume claims (PVC) are employed in this project. Through this setup, I effectively managed application health and performance.

HIGH-LEVEL STEPS OF THE PROJECT :

Created an EKS cluster.
Set up nodes and attach them to the cluster.
Deployed the EFK stack in the EKS cluster using YAML manifest files:
Fluentd was deployed as a daemon set, ensuring it runs on each worker node.
Kibana was deployed as a deployment.
Elasticsearch was deployed as a stateful set.
Established port forwarding to access Kibana and Elasticsearch externally via localhost.
Developed a dashboard in Kibana:
Maintained the specified format without deviations.

GitHub :  [ https://github.com/elam1234/Monitoring-EFK.git ]

CONCLUSION :

In summary, this real-time log monitoring project using the EFK stack in Kubernetes has provided valuable insights into the EKS cluster's health and performance. Leveraging Elasticsearch, Fluentd, and Kibana, I've established an efficient system for log aggregation, storage, and visualization. The project's GitHub repository [https://github.com/elam1234/Monitoring-EFK.git] offers a comprehensive view of my implementation, enabling others to replicate my setup and enhance their log management capabilities. Overall, this initiative demonstrates my commitment to innovation in DevOps practices, paving the way for continued improvements in my operational efficiency.

     
                



              
