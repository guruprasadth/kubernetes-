# kubernetes-
kubernetes related resources and hands-on exercises on AWS Cloud

Create a ec2 instances master and worker node must enable port number 6443 on security groups

Here master set up images 

<img width="1920" height="1080" alt="m1" src="https://github.com/user-attachments/assets/37f5ee69-9da3-4bab-aefd-eef83de88714" />



<img width="1913" height="1045" alt="m7" src="https://github.com/user-attachments/assets/b3f7c38a-841e-434e-b505-0323db1c2781" /></br>


#now set up the Worker-node

<img width="1920" height="1080" alt="nodes" src="https://github.com/user-attachments/assets/240aa457-1efd-43ce-a36a-6385a0db504b" />


#Both Master and Worker to connect so we need to create a token in master node then share to worker node

#kubeadm token create --print-join-commands

<img width="1830" height="129" alt="image" src="https://github.com/user-attachments/assets/6f33fbcb-7a4a-489d-9998-fb8bd37f153e" />


#Paste the token and hash in worked to connect

<img width="1920" height="1041" alt="w1" src="https://github.com/user-attachments/assets/58e432c3-cfee-434d-af11-3755649206ec" />

#Now verify in master node
<img width="1830" height="126" alt="image" src="https://github.com/user-attachments/assets/9a11f0ea-80a4-4de6-b666-0c811ff08694" />

#connected one more node to master node
<img width="1830" height="163" alt="image" src="https://github.com/user-attachments/assets/f7c4c5fa-c6d1-4239-b3d1-2d1e0934864c" />

#Label the Roles 
<img width="1230" height="128" alt="image" src="https://github.com/user-attachments/assets/f3b36d41-751d-4d55-8e57-f19b6fd1628f" />

#Now the worker nodes are connect we can create a pod and chech how the masetr assign to worker nodes
<img width="1913" height="1044" alt="ms1 set" src="https://github.com/user-attachments/assets/05cb6e25-07fb-4fe0-bb0a-8ba7c58c2ee8" />


#CHECK THE ASSIGNED PODS IP"S 
<img width="1691" height="435" alt="image" src="https://github.com/user-attachments/assets/266437de-ef32-41c9-bf48-560cd7d638ed" />












