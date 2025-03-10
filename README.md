$$
\Huge \text{\color{orange}{AWS Certified SysOps Administrator-Associate}}
$$



## ✅ Connect Windows CMD with AWS Instance

To connect **Windows Command Prompt (CMD)** to an AWS EC2 instance:

> **Command:**
> ```
> ssh -i DemoKeyPair.pem ec2-user@3.133.112.164
> ```
### ⚡ **Steps to Connect**
1. Open **Command Prompt (CMD)** or **PowerShell**.
2. Navigate to the directory where the `.pem` file is located using:
   ```cmd
   cd C:\Users\YourUser\Downloads
### ⚡ **The other way we can connect**
![image](https://github.com/user-attachments/assets/a9a5c813-6761-4f28-9f6c-c7d548313a18)
After that, we have to click **connect** again. It will directly connect with the instance in the browser.
For practical example:
[![Watch the video](https://img.youtube.com/vi/kzLRxVgos2M/0.jpg)](https://youtu.be/kzLRxVgos2M)
## ✅ How to change EC2 instance type
Suppose, we need more storage and cpu. For that we have to change the instance type.
![image](https://github.com/user-attachments/assets/d1fb53aa-c142-4e84-aa60-7f284ed9a781)

![image](https://github.com/user-attachments/assets/4d6e9bca-c436-4940-93b2-1162527fda14)

![image](https://github.com/user-attachments/assets/4d9e9a99-44b1-464a-b19d-0f4f3230e162)

![image](https://github.com/user-attachments/assets/d633432b-bbab-4b3a-8c62-b43c1d264a75)
EBS optimized means that we are going to get better throughout and the newer generation EBS has better version throughput than previous genaration.

If we do this we have to pay for this as T2 tier is not free.

Our data will remain same if we switch from one EBS base system to another EBS based system as the storage technology will remain same. 

## ✅ Enhanced Networking
![image](https://github.com/user-attachments/assets/7a8bb866-c159-48fe-88d1-dcc4420952e6)

- If we want Enhanced networking with lower latency then we should go for ENA
- If we have a HPC cluster then we should select EFA
## ✅ Practical example of ENA
we will start a t2.micro instance and we will also create a t3 instance which is newer version instance.
![image](https://github.com/user-attachments/assets/0dd1d9a2-ed22-4a97-8ad7-cf334db4e6fe)
![image](https://github.com/user-attachments/assets/363c40ea-392a-400d-9b9b-346449431f0d)
t3 is not a free tier. We have to pay for that. Now lets login with the t2 instance type.
![image](https://github.com/user-attachments/assets/3147792a-2781-4f92-96ff-a367eaef5647)
![image](https://github.com/user-attachments/assets/e224b24e-524c-4751-b767-2aa4dfa3ab59)
As we can see the driver type is vif, not ena. So we must have a newer version of instance like t3.micro inorder to have a ena mechanism.
![image](https://github.com/user-attachments/assets/9f5d048a-d6fc-42a0-9b13-faf2ad1cbd20)















