# EBS
WORKING WITH EBS
```
NAME: GOWRI SANKARI R
REGISTER NO:212223060073
```
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:
*Create an Amazon EBS volume *Attach and mount your volume to an EC2 instance *Create a snapshot of your volume *Create a new volume from your snapshot *Attach and mount the new volume to your EC2 instance

## Illustration:
# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.
<img width="1873" height="837" alt="Screenshot 2026-08-03 140253" src="https://github.com/user-attachments/assets/bb8ea9c3-15b9-4826-8129-995af9cf5194" />


# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.
<img width="1896" height="816" alt="Screenshot 2026-08-05 183202" src="https://github.com/user-attachments/assets/97add80d-04aa-431f-8d59-a24d3df1a550" />



# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.

<img width="1902" height="818" alt="Screenshot 2026-08-05 190720" src="https://github.com/user-attachments/assets/cdbdf50b-20fe-4ce8-9837-0071daaa53a2" />



# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

# STEP 5:

<img width="1907" height="825" alt="Screenshot 2026-08-05 191127" src="https://github.com/user-attachments/assets/061b2b37-7a4f-456c-956b-10bff74d3af0" />

<img width="1913" height="815" alt="Screenshot 2026-08-05 191300" src="https://github.com/user-attachments/assets/acb3cd2d-90da-4a2c-9999-04d338be90ef" />

<img width="580" height="418" alt="Screenshot 2026-08-05 191510" src="https://github.com/user-attachments/assets/2ad2dccc-a60b-4f9d-8222-97fec804e992" />


## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.
