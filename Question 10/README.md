# Question 10: Discover a Privacy Technique Used Offline.

### Explanation
For this task, I implemented an Offline Virtual Vault using Windows Disk Management. I created a **Virtual Hard Disk (VHDX)** with a fixed size of 100MB to act as an isolated storage container. After initializing the disk and creating a new volume, I was able to move sensitive files into this dedicated drive. To secure the data, I used **BitLocker drive encryption** (or by 'Detaching' the VHD), which ensures the volume is invisible and inaccessible to unauthorized users when unmounted.

### Proof of Discovery
<img width="1600" height="901" alt="image" src="https://github.com/user-attachments/assets/d3fe1bba-58a3-4b28-bcee-ec5891824bbc" />
<img width="1600" height="901" alt="image" src="https://github.com/user-attachments/assets/7630089b-45b7-4cc4-8350-2589da7ec593" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/09d4bec1-e55e-4d31-83db-a46f6584beba" />
<img width="954" height="1079" alt="image" src="https://github.com/user-attachments/assets/db93a31a-d5d8-4057-985b-94a44200e447" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/d97d3eae-4183-437f-9f97-68b3dce539a6" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/44198a2a-56f1-40d0-99c5-4b56524add0a" />
<img width="1600" height="898" alt="image" src="https://github.com/user-attachments/assets/06d730a7-5f6b-4ee7-9feb-b2459a4ba98f" />
