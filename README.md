# Github

![image](https://user-images.githubusercontent.com/22832922/139620243-13fe8415-0614-4015-bce0-99b117e4da7f.png)

Welcome to the Github wiki!

Comand line:

1. Change config:

git config --replace-all user.email "thanhphq87@gmail.com"

2. Add whole file in order to commit

git add .

3. Committing the changes

git commit -m "Update"

4. Push change in local into github

git push

5. Git branch

git clone --single-branch --branch publication https://github.com/khanhha/crack_segmentation.git

__Create SSH key in PC__

Step 1: Open terminal 

ssh-keygen -t ed25519 -C "thanhphq87@gmail.com"

Step 2: Enter many times

Step 3: sudo nano ~/.ssh/id_ed25519.pub or use cat

Step 4: Copy all content of file id_ed25519.pb into github

Example: ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIPtzB7uhHSWahouptEfRio0EuuFgkwZzbCkcp5sB4nS+ thanhphq87@gmail.com

Step 5: Use ssh protocol

git clone git@github.com:ThanhPham1987/OCR_JP_EN.git

Reference:

[1] https://phamdinhkhanh.github.io/deepai-book/ch_appendix/appendix_OOP.html

__How to set up for human capacity__

![Screenshot from 2023-05-13 11-09-09](https://github.com/ThanhPham1987/Github/assets/22832922/72e21793-b653-4a32-be33-978ea30600cb)


Reference

[1] https://support.atlassian.com/bitbucket-cloud/docs/set-up-personal-ssh-keys-on-linux/

[2] https://bitbucket.org/account/settings/ssh-keys/


