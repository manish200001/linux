# Linux-Assignment-4

**Q1. Create a directory named "MyFiles" in your home directory. Navigate into this directory and list its contents.**


```
mkdir Myfilies
```

```
ls  Myfilies/
```


![](https://lh7-us.googleusercontent.com/KImj_L1VN2XkVPPfqzFtm_cKbmuViGE4h1LLxioX9jGTgEEWLLMVCWoqb2z4orTNmgt-QinJUN593SONyVJJS8Tz1Mlg0a6jcbErmleX50RQHWW4MFFCETDgM4pII7oIeBssLp_eT_4CBSv2nhgm9Hc)

**Q2 Copy a file named "document.txt" from your home directory to the "MyFiles" directory. Move the file to a subdirectory named "Documents" within "MyFiles."**

```
touch document.txt
```

```
cp document.txt Myfilies/
```

```
ls Myfilies/
```

```
cd Myfilies/
```

```
mkdir Documents
```

```
mv document.txt Documents/
```

```
ls Documents/
```


![](https://lh7-us.googleusercontent.com/kA9KKCUrTXtk8FOz3Sc_plqu9bFP2TEagAWcCOJLhakwcfzFS0E2bdp5BEMJpMfelEE882dAMPFnPaqeUqDjhmJZzSSNqlWOv4AlLK1buIfh6UOXiMqLuHbnSo06q8fd1p7sql4WKs-_UDIx-Ic7eS8)


**Q3. Create an empty file named "notes.txt" in the "MyFiles" directory. Afterward, delete the file.**
```
cd Myfilies/
```
```
touch notes.txt
```
```
rm notes.txt
```
![](https://lh7-us.googleusercontent.com/ZCDtMZL7VYr7WXKmoO2EEAKbIUTzilMxAcBMw16v-FvEBL2Ohxyj48JioPOmnWHjnnYjsPnkIndiTMsiuzcMKLoFjFXS1xafQriogxs7LuvBu020hPmHVeMW-tvcbpWsGVD-4u707G0_NY-j-DlUXLU)

**Q4. Create a hard link named "hardlink.txt" for the file "document.txt" within the "Documents" subdirectory. Also, create a symbolic link named "symlink.txt" in the same location.**
```
ln document.txt Myfilies/Documents/hardlink.txt
```
```
ln -s document.txt Myfilies/Documents/symlink.txt
```
![](https://lh7-us.googleusercontent.com/KtSjrt7m5ix4p0E8JsEvSrY5_sAB9kMegH1vVw9GEuNEWFKo1CYtvduSk1U96qHhzG4tjioQa-xhI_QTvYtjlvVuXF2kqvwoHA4GOBT_yFmEyB_jvzoEdnlZLOvIdy0l5WapS_D_xaOh55dZCbZsv-k)

**Q5. In the "MyFiles" directory, use a single command to list all files that start with the letter "a" and have a ".txt" extension.**
```
cd Myfilies/
```
```
touch aman.txt abcdef.txt auto autom.txt
```
```
ls a*.txt
```
![](https://lh7-us.googleusercontent.com/li_J-U4AvplPL7E9RFXOYBDZbWkkAzdqBtxdWC93nNTd5fbJTzMafQzlh9qGUG1DSMmrgu78J0ATbo2hwtvRjwJhlRjnpDldl1UXBfW3RquTFXgWQxJeRGLFNGz3PeaxaoE_r54S7B10IPHUhUd3ERM)

**Q6. Rename all files in the "Documents" subdirectory of "MyFiles" with a ".bak" extension. Ensure the original file names are preserved.**


```
ls
```
```
vim a.sh
```
```
cat a.sh
```
```
bash a.sh
```
****![](https://lh7-us.googleusercontent.com/tOcmyHcCjrGkPaJYKTVx9Rm9D8zV69y9mu2YjlTFrZYVchat7KbedotfZxRf9DC4sCcRiMJDoZqrwt5Ih2xXe-Ex5FS4naH2nF4lo_X-1_XHbw9QVFTy-K8Uu9gg_-I1EqpRRUPr-fdPlxPb7Sp6kk8)****

****![](https://lh7-us.googleusercontent.com/mSepSj7Ih5XtVw8bubTsu61AmrEQsKrFz2jPKblAcWaeL_hPFFKMmy6AW7tnWqpFG_e67x1NxG-AglHX5RiS0LZmgxs0r2H9PA2Prj_HciXkhs2nJmi17al9YjQ2axcNmfujWYTJO590eQgyoUhDjhs)****




**Q7. Use a wildcard character to copy all files from the "Documents" subdirectory of "MyFiles" to another directory named "Backup."**
```
cd Myfilies/
```
```
mkdir Backup
```
```
cd Documents/
```
```
cp * ../Backup/
```
```
ls ../Backup/
```

![](https://lh7-us.googleusercontent.com/A1bRAH3yie8iMndg0OyXN8PdNeqtuExi5VjNcmKiLsCI-CVE3Sd8zotHS_YnzdPfAnMVd6r7RrjESMfwLf7xDzzIofbKof_-S9uswfc9w24wzcc86wrZwNndM-MJuumePS4Oymhb1I0k0Ahp1ACc_dg)

**Q8. Execute the ls command to list files in the current directory. Save the output to a file named "file\_list.txt." Then, use a pipe to filter the output through grep to display only files with a ".txt" extension.**
```
ls > file_list.txt
```
```
cat file_list.txt
```
```
cat file_list.txt | grep .txt
```
![](https://lh7-us.googleusercontent.com/ogMzg_Xomq7Zslr0DOdSaGmrZp2OyS305LmZwYULg-felvpie5XG1N54bHmPZ8pf1Ap8u2rrxZ1UiKP8M-FL-Jq3s7buH5JLUMMTDOeUZRxaCdSpVLCct3kz-wKPnMG1mBqFmrvZr6Vo2NMioX4_oGQ)

****

**Q9. Create a new text file named "my\_notes.txt" using the touch command. Open the file in the Vim editor, add some text, and save the changes.**
```
touch my_notes.txt
```
```
vim my_notes.txt
```
```
cat my_notes.txt
```

****![](https://lh7-us.googleusercontent.com/aRHbKdZBffsgGgPrqvA6-AISW8ag5-_l97ozoVmN586deSgD1a8csk_PJHijL4C3Sgn2ZAarD5vEPxSelO5Oi3vIq5og_dBkHCf7niyN4f6oyfRn9p0S3Du6htJ3OcNYXsytwGg5u7V3LQTdJKBhU1U)****

****![](https://lh7-us.googleusercontent.com/BGrSP9xSU3U-lSY_pVCWwFESxBbJx65U-qyvPMHkZh8l_qtrCUpv9SyPLpxW1oQod4G2aOYZ-knayqp2i4OH8dNOd_5hwi34T_rdAa7iOqSXM_A6BFcU37IE7qnv5MxcmMy3zuHO1Eifm8t4tAA5IIw)****



**Q10. Run the date command and store the output in a variable named "current\_date." Display the value of the variable and append it to the "my\_notes.txt" file.**

```
current_date=$(date)
```
```
echo $current_date
```
```
cat my_notes.txt
```
```
echo $current_date >> my_notes.txt
```
```
cat my_notes.txt
```
****![](https://lh7-us.googleusercontent.com/cMyZHWoixKtpqNBRoTPKEZBBJMdJX3CXLwAk6erqdAF8HLDS7HOKgMO6nDoAZpgidMat-FOgJIyoiDr7CdskkG_a7vfuBqDz9xpf7KjJ1zTV_cL3EZwLpII9T-56wcDn745Z_ZJB-9qIDMtbvlwS_PU)****


**Q11. Edit the Bash startup script (e.g., .bashrc) to set an environment variable named "CUSTOM\_PATH" to a specific directory path. Ensure the variable is available in new shell sessions.**

```
vim .bashrc
```
```
source ~/.bashrc
```
```
echo $CUSTOM_PATH
```


****![](https://lh7-us.googleusercontent.com/JHLDvRHmQ6Q3tRxClitpLlw42j-ruM6kkemgGT7WwLxzEpBL2A_fTsDp8LzBkUqymsGLNQvtaTy7cDm0Ir6Mf9-cQ4cKm_eu456Q_v_pY3Lp_ZFQZk_C91CLWkzjag0jqvZxbSsOoGWHtH5JwnZx430)****

****![](https://lh7-us.googleusercontent.com/EvRsNKcEg_bPIg_27WhCTNYXHrGIJ4remP_wwTBCED-RfIJuO6zg0ADKolh4JTpjJ0SyTOVjo1T4j1qpfVZ7JDycFRQIkk-tc9IFZSWVG4LRCBArasuvdAcyviiTaEyT5DiqWyeR9F0jpk7xquo5EOs)****

**Q12. Use the echo command to add a new line of text to the "my\_notes.txt" file without overwriting existing content. Verify that the new text is appended.**
```
cat my_notes.txt
```
```
echo "I am writing text in new line" >> my_notes.txt
```
```
cat my_notes.txt
```
****![](https://lh7-us.googleusercontent.com/6NhHivyQjKQ7kBXELBNvBlDP0LSHeVu-n8nI78uBxUPLVPfzXzjmadfIzvcfFuu_aW_zRCXP6RDgEf3V5WyFATdA4GhLJkv6yYpzYTmY5W2D_b6MbyD4kL5BVoMIzvCXQX3-1j4RUNdNJT1jShbrmNU)****

**Q13. List all files in the "/etc" directory, filter the output to include only those containing the word "conf," and save the result to a file named "conf\_files.txt."**

```
ls /etc | grep 'conf' > conf_files.txt
```

```
cat conf_files.txt 
```
****![](https://lh7-us.googleusercontent.com/ucASZvDTA1RSyh9L_aBJuaLVpDY4WQ1QbqgWoO_DMTFKDpY2KHm0LfzWueBLQOJuJLpY6TW2Zc0SQrNEkWMgchiG1EWs8B6-_KwRjXsv_U96JLNI2Davsvhuis_XlwiLATu1gYxrpsBayBm_SZ5rJnc)****

**Q14. Open the "my\_notes.txt" file in Vim. Use Vim's search and replace functionality to replace all occurrences of the word "important" with "critical." Save the changes.**
```
vim my_notes.txt
```
**Note:-** 
**After opening file write below command after press shift + colon**

****![](https://lh7-us.googleusercontent.com/IMm4eE8RIdWc3mzh2D-zD4zGR3peiGjwd4hC87Ky4w80gt-jYeT-d_2nUqS-y8V-rlTOcrghcXn6LDSNdgl03XTUCOqRgZ2fQusV_1qMlwvqidZq0acgKgvLFtObFx_GltRM6k0L_3RvAPDbojuk-vg)****





****![](https://lh7-us.googleusercontent.com/0hiEgqBhWq2nxYARUwbbWD3HDxc97aWKaDfCVVXqMoFGWlU1hxuOf6rT9YyAU6VXJYCaH4KZXrF2ujW266yalYbVfVhX4zfrHvfN7MtRA8U2s9DEkuc4mLHyISV9kq-ABEKWuYABzTWj8MGvWTBAiaA)****


**Q15. Create a new user account named "john\_doe." Set the user's home directory to "/home/john\_doe" and assign the user to the "users" group.**

```
grep '^users:' /etc/group
```
```
sudo adduser --home /home/john_doe john_doe
```
```
sudo usermod -aG users john_doe
```

```
id john_doe
```
****![](https://lh7-us.googleusercontent.com/7AunDC2SZpDQhgpQ6cjHEK3nw0FKJPYa1quVznUXBC3mfAdCu9Hmu0yfTvmQyOjVKNNGvQPI7R-AAZ09b3ulvvcmQ-OErzBRngKUSzg9im1o5TbbSi-qxkPItKN4Tof1UjmNodTCrh5ABG42arXZL1M)****

**Q16. Add the user "john\_doe" to the sudoers file, allowing them superuser privileges. Confirm that "john\_doe" can execute commands with sudo.**

```
sudo usermod -aG users john_doe
```

```
id john_doe
```
```
su - john_doe
```
```
sudo apt update
```
```
exit
```
```
sudo usermod -aG sudo john_doe
```

```
id john_doe
```
```
su - john_doe
```

```
sudo su
```

****![](https://lh7-us.googleusercontent.com/-YRZXZVpojUFAvaTHdQvVbbfe1nzTk5JtJgSRTR4EvH_PyVXrGrv3oHqlDWcVkTQTI8KFEdZU__mEHiyCpVo6p5oEAptkFTe_fJVJCpTdunVT6Z1_AulEUhv8bjA2hUMxqNJCM_ErYnAdsEdNILcXD0)****

**Q17. Modify the user account "john\_doe" to change the default shell to "/bin/bash" and set the account's expiration date to one month from today.**
```
sudo chsh -s /bin/bash john_doe
```
```
sudo chage -E $(date -d "+1 month" +"%Y-%m-%d") john_doe
```
```
sudo chage -l john_doe
```
```
grep john_doe /etc/passwd
```

****![](https://lh7-us.googleusercontent.com/hOY_oeXSR8hxEI2q-E0gNfJE9utdjG1LWmNO6K6SQ8DmVpO_s5imeFE534A9HojwK893GnsjsIxHVrgScqufmRJA64wUzh7Gn_y-jxWJzczVf1f3heRP8g3lOIMrzsPgYilBvAVIY1UgZwRcdEgLj9M)****


**Q18. Create a new group named "development\_team." Add "john\_doe" to this group and verify the group's existence.**

```
grep development_team /etc/group
```
```
sudo addgroup development_team
```
```
grep development_team /etc/group
```
```
sudo adduser john_doe development_team
```
```
id john_doe
```


****![](https://lh7-us.googleusercontent.com/n9PsMDmgItJrIxlJ6DHn1MaHmUkk9K6MU90_UUREXln2b6ix6MD1R0jEhMSCWB_oup7ql0XUdyhO-RVNaOar28lcFYR-yWx_6w5r5t8Wpd01iudHNGIMLAQCdCQZTtqMSZhCPTW5_qhgv0ebtBgaGuE)****

**Q19. Remove "john\_doe" from the "users" group and add them to the "development\_team" group. Confirm the changes.**

```
id john_doe
```

```
sudo deluser john_doe users
```
```
sudo adduser john_doe development_team
```
```
id john_doe
```

****![](https://lh7-us.googleusercontent.com/4A4HfikJCeDNW4Sbd5c2hDVTQ2lG-VfMQtZRQUpodIDB_-CNCAI_asjoGSWPrQ9pgmGJSZdOOb3jrFNNMhHdsZ9e0qnkOXHbaYjNYPUEuAy0HtWyJm0sZPATKgeZuHUI0hEHzHt92MHJkwYrON23ij4)****

 

**Q20. Delete the user account "john\_doe" and ensure that their home directory is also removed.**
```
sudo deluser --remvoe-home john_doe
```
```
id john_doe
```

```
ls /home/john_doe
```
****![](https://lh7-us.googleusercontent.com/e5wQdsktr6f15YrrX9SmsCptMDoTEEMsHqYg53ejca2-pcUbGlAF-PqL5ur1srKOpkhMv_aatiYEeawGWgoL07yOdGXnRvK7YAwmJq5QACBacvHVo3mYlhPYZXPyDmAfKgbDyD5kps7NzcDXPUi2260)****

**Q21. Delete the group "development\_team" and ensure that all users previously belonging to the group are appropriately handled.**

```
sudo deluser john_doe development_team
```
```
sudo delgroup development_team
```
```
grep development_team /etc/group
```
****![](https://lh7-us.googleusercontent.com/-_wTOoaONy2ymlrkQcejEZb2ZCpHxA7gAg0Pp6AySXTLJtJf2noHmcnqR4-UOWOC1NiEPyl8kUBJRwYKHw2Bwa-yICNkPVm3QCJxx-khv8CBqQY7Dk18u_LIASJLCyDguEKYuTmZoWVUXUhsGCC2jNM)****

**Q22. Implement a password policy that requires users to change their passwords every 90 days. Apply this policy to all existing and new user accounts.**

```
sudo chage -M 90 -m 0 -W 7 -I 30 -E -1 $(cut -d: -f1 /etc/passwd)
```
```
sudo sed -i '/^PASS_MAX_DAYS/c\PASS_MAX_DAYS   90' /etc/login.defs
```
```
sudo chage -l john_doe
```
```
grep PASS_MAX_DAYS /etc/login.defs
```


****![](https://lh7-us.googleusercontent.com/85tnaSRABWL5nE3jFKvgr4lgPoB9uznA2PhjNvjl3fvytgSFUQ91n-BFLkaQmGFy6hJBNIkvwipHQPdfe0RxrI5H6KnaVovKSQOwivDGuWignti9ju0yPwnSVJxiOdh2joB_wspAQoe_FNleLzmnt7U)****

**Q23. Manually lock the user account "john\_doe." Attempt to log in as "john\_doe" to confirm that the account is locked. Then, unlock the account.**

```
sudo passwd -l john_doe
```
```
su - john_doe
```
```
sudo su - john_doe
```
```
sudo passwd -u john_doe
```
```
exit
```

```
sudo passwd -u john_doe
```
```
su - john_doe
```
****![](https://lh7-us.googleusercontent.com/S5WL76zqrjCF3hfl_7c4kTl_Ax03_f1DYmD_KWAziJOUcBGWPrTbSHDkh4uqrovoYvpE92j_53UgJKAyTx0vWnJOUCyyQ_ezuMw-ZremWPPj9L6pxb997lQdrTI7WfRc_idWk83Aop9h5ZE2DguUiR8)****

**Q24. Use the id command to display detailed information about the "john\_doe" user, including user ID, group ID, and supplementary groups.**
```
id john_doe
```

****![](https://lh7-us.googleusercontent.com/jKoUDyHZmB-jIA26sXZpsCTuc7V7eiOH6j48BpWyKX5xOfBOgELSC0h4giFYKo8Hf5-E4l_mVHoRIxHiEWlvEYEcjkUJSu3zGDJdPQdFx9ndqn85bpZptQNiYJaS0u6zZUCjk6z5yONXqCGEAo5G_Vw)****

**Q25. Configure the password aging for the user "john\_doe" to enforce a maximum password age of 60 days. Confirm that the changes take effect.**

```
sudo adduser john_doe
```

```
sudo grep 'john_doe' /etc/passwd
```

```
sudo chage -M 60 john_doe
```
```
sudo chage -l john_doe
```
****![](https://lh7-us.googleusercontent.com/MwnfqSGuYwXiSwPZk0duzqMkEZrcXu1FHknMig1nQfIGUFoZMR9wbop65hmmqLGqDx0g0d3msHTrstX5TitZ3F_yBjXJtVS2qDu0TvCZpTP8CE5qPcLXS0MXdM4kXQMUjTmPbjeMBhmd6CiQmdFDM54)****





