![Screenshot 2025-03-09 151405](https://github.com/user-attachments/assets/dc6118c4-af35-434f-b1e5-97987151fd0d)
1. Open PowerShell as Administrator.
2. Run the following command to disable Hyper-V:
    dism.exe /Online /Disable-Feature:Microsoft-Hyper-V-All
3. Reboot your machine and try running VirtualBox again.
