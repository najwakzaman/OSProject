Group Name: Latte

Section: 2 

Team Mates:
1. Najwa Hannani Bt Kamaruzaman  2215426
2. Nur Adilah Bt Kamal Ariffin   2214064
3. Faheyra Ezzah Bt Musa         2212016

## Rules
1. You are allowed to have **3 group** members. *Exception* is allowed **IFF (if and only if)** you are allowed to have 4 group members if you are a **multinational** or a **multigender** group. 
2. When you complete the project, make sure to submit the repository link of your cloned project. Make sure all the files are as what you aspect in your repository. 
3. Answer all questions in the **README.md**, in your own repository. Either use the online VSCode, terminal or github to edit. Answers are expected where you see __Fill answer here__.
4. Learn how to use markdown. https://www.w3schools.io/file/markdown-introduction/

## Forking this OS project repository
1. First thing you need in doing this project is to have a github account. Make sure to sign up at https://www.github.com
2. The second thing you need is to fork the OS project repository in your own github account. 

    1. Go to https://github.com/joeynor/OSProject and click fork to copy the project into your own repository
    2. Make sure that the new fork is now in your own repository

***Questions:***

1. What is the link of the fork OSProject in your repository. ***(1 mark)*** - https://github.com/najwakzaman/OSProject.git
2. How many files and folders are in this repository. ***(1 mark)*** 1 file and 1 folder


## Exploring github codespaces

1. The next thing that we will be doing is exploring codespaces. First of all, read about codespaces https://docs.github.com/en/codespaces/overview#what-is-a-codespace
2. Then go to the link https://github.com/codespaces and we shall start a new codespace.  
3. Click on ***New codespace***.
4. Choose your own OSProject repository to start your codespace.

 <img src="./images/newcodespace.png" width="50%">

5. Once you have created you codespace, you will see the following. You might already be familiar with this, since it will look similar to VSCode. 

 <img src="./images/UIwebvscode.png" width="70%">

6. You will see the [README file](./README.md) file. One is a preview of how it looks like on the web, and the other is the editing view in markdown language. 
7. Edit the [README file](./README.md). Make sure you have your group details correct, ie, group name, section and team members along with their matric IDs. 
8. Once you have finish editing, click File->Save or ***ctrl-s*** to save it. 
9. After saving, you will notice an M or U next to your file. You will need to commit any changes, whenever you make changes so that it is uploaded to the github repository. 

 <img src="./images/SourceControlUI.png" width="70%">

10. Click on the source control, hint: its on the left side panel, and it will list down the files that have been modified or updated. Click on commit. It will then ask you "Would you like to stage all your changes and commit them directly?" Just say yes, and a new tab will appear. Type a message to log what you have done, and click on the check mark. 

 <img src="./images/CommittingUI.png" width="70%">

11. After that, sync the changes to the main repository. 
12. Make sure to commit and sync your files to the main repository, or else, your work will be lost since it is not saved into the main repository when you submit your project.

***Questions:***

1. What is default OS used to run the virtual environment for codespaces. ***(1 mark)*** \
- Ubuntu Linux
2. What are the two options of ram, disk and vcpu configuration you can have in running codespaces . ***(1 mark)*** 
- 1- 8GB RAM, 32GB STORAGE, 2 CORES VCPU
  2- 64GB RAM, 128GB STORAGE, 32 CORES VCPU

3. Why must we commit and sync our current work on source control? ***(1 mark)***
- To make sure all changes are saved to the main repository

## Exploring the Terminal

1. Look at the TERMINAL tab. Explore and run commands according to the questions below. 
2. You can include your answers as images, or cut and paste the output here. If you are cutting and pasting your answers, wrap your answers in the codeblock clause in markdown. For example, if i run the command **whoami** the the output would look like the one below.
```bash
@joeynor ➜ /workspaces/OSProject (main) $ whoami 
codespace
```

Answers
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ whoami
codespace
```




***Questions:***

Look at the TERMINAL tab. Run the following commands and provide the output here. 

1. Run the command **pwd** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ pwd
/workspaces/OSProject
```
2. Run the command **cat /etc/passwd** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ cat /etc/passwd
root:x:0:0:root:/root:/bin/bash
daemon:x:1:1:daemon:/usr/sbin:/usr/sbin/nologin
bin:x:2:2:bin:/bin:/usr/sbin/nologin
sys:x:3:3:sys:/dev:/usr/sbin/nologin
sync:x:4:65534:sync:/bin:/bin/sync
games:x:5:60:games:/usr/games:/usr/sbin/nologin
man:x:6:12:man:/var/cache/man:/usr/sbin/nologin
lp:x:7:7:lp:/var/spool/lpd:/usr/sbin/nologin
mail:x:8:8:mail:/var/mail:/usr/sbin/nologin
news:x:9:9:news:/var/spool/news:/usr/sbin/nologin
uucp:x:10:10:uucp:/var/spool/uucp:/usr/sbin/nologin
proxy:x:13:13:proxy:/bin:/usr/sbin/nologin
www-data:x:33:33:www-data:/var/www:/usr/sbin/nologin
backup:x:34:34:backup:/var/backups:/usr/sbin/nologin
list:x:38:38:Mailing List Manager:/var/list:/usr/sbin/nologin
irc:x:39:39:ircd:/var/run/ircd:/usr/sbin/nologin
gnats:x:41:41:Gnats Bug-Reporting System (admin):/var/lib/gnats:/usr/sbin/nologin
nobody:x:65534:65534:nobody:/nonexistent:/usr/sbin/nologin
_apt:x:100:65534::/nonexistent:/usr/sbin/nologin
systemd-timesync:x:101:101:systemd Time Synchronization,,,:/run/systemd:/usr/sbin/nologin
systemd-network:x:102:103:systemd Network Management,,,:/run/systemd:/usr/sbin/nologin
systemd-resolve:x:103:104:systemd Resolver,,,:/run/systemd:/usr/sbin/nologin
messagebus:x:104:105::/nonexistent:/usr/sbin/nologin
codespace:x:1000:1000::/home/codespace:/bin/bash
sshd:x:105:65534::/run/sshd:/usr/sbin/nologin
```
3. Run the command **df** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ df
Filesystem     1K-blocks     Used Available Use% Mounted on
overlay         32847680 10346636  20806948  34% /
tmpfs              65536        0     65536   0% /dev
shm                65536        0     65536   0% /dev/shm
/dev/root       30298176 24477008   5804784  81% /vscode
/dev/loop3      32847680 10346636  20806948  34% /workspaces
/dev/sdb1       46127956      124  43752256   1% /tmp
```
4. Run the command **du** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ du
8       ./.git/info
4       ./.git/lfs/tmp
8       ./.git/lfs
8       ./.git/refs/heads
12      ./.git/refs/remotes/origin
16      ./.git/refs/remotes
4       ./.git/refs/tags
32      ./.git/refs
4       ./.git/branches
8       ./.git/logs/refs/heads
12      ./.git/logs/refs/remotes/origin
16      ./.git/logs/refs/remotes
28      ./.git/logs/refs
36      ./.git/logs
8       ./.git/objects/04
8       ./.git/objects/93
8       ./.git/objects/fa
12      ./.git/objects/ff
12      ./.git/objects/72
12      ./.git/objects/17
12      ./.git/objects/b5
8       ./.git/objects/c6
8       ./.git/objects/4f
8       ./.git/objects/eb
12      ./.git/objects/3d
8       ./.git/objects/83
4       ./.git/objects/info
8       ./.git/objects/71
8       ./.git/objects/c3
8       ./.git/objects/4b
1828    ./.git/objects/pack
8       ./.git/objects/39
8       ./.git/objects/f6
8       ./.git/objects/41
12      ./.git/objects/4e
12      ./.git/objects/1c
8       ./.git/objects/fc
8       ./.git/objects/81
8       ./.git/objects/60
16      ./.git/objects/fb
8       ./.git/objects/cb
12      ./.git/objects/af
8       ./.git/objects/fe
8       ./.git/objects/cd
12      ./.git/objects/46
8       ./.git/objects/52
8       ./.git/objects/a6
8       ./.git/objects/b2
8       ./.git/objects/1b
8       ./.git/objects/3a
12      ./.git/objects/6e
8       ./.git/objects/b9
8       ./.git/objects/58
8       ./.git/objects/c0
8       ./.git/objects/7b
8       ./.git/objects/20
12      ./.git/objects/3f
8       ./.git/objects/f2
8       ./.git/objects/e7
8       ./.git/objects/0b
8       ./.git/objects/24
8       ./.git/objects/91
12      ./.git/objects/2e
8       ./.git/objects/49
8       ./.git/objects/a3
8       ./.git/objects/0d
12      ./.git/objects/e5
8       ./.git/objects/fd
8       ./.git/objects/b6
8       ./.git/objects/86
12      ./.git/objects/70
8       ./.git/objects/8a
8       ./.git/objects/47
12      ./.git/objects/44
12      ./.git/objects/29
12      ./.git/objects/73
8       ./.git/objects/74
8       ./.git/objects/d8
8       ./.git/objects/a4
8       ./.git/objects/f4
12      ./.git/objects/62
12      ./.git/objects/d2
12      ./.git/objects/14
8       ./.git/objects/4a
8       ./.git/objects/96
8       ./.git/objects/ab
8       ./.git/objects/e9
12      ./.git/objects/64
2504    ./.git/objects
68      ./.git/hooks
2696    ./.git
1972    ./images
4692    .
```
5. Run the command **ls** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ ls
README.md  images
```
6. Run the command **ls -asl** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ ls -asl
total 40
 4 drwxrwxrwx+ 4 codespace root  4096 May 29 03:58 .
 4 drwxr-xrwx+ 5 codespace root  4096 May 29 03:58 ..
 4 drwxrwxrwx+ 9 codespace root  4096 Jun  7 09:10 .git
24 -rw-rw-rw-  1 codespace root 22012 Jun  7 09:19 README.md
 4 drwxrwxrwx+ 2 codespace root  4096 May 29 03:58 images
 ```
7. Run the command **free -h** . ***(1 mark)***
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ free -h
              total        used        free      shared  buff/cache   available
Mem:          7.7Gi       1.6Gi       495Mi       1.0Mi       5.7Gi       5.9Gi
Swap:            0B          0B          0B
```
8. Run the command **cat /proc/cpuinfo** . ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ cat /proc/cpuinfo
processor       : 0
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.589
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 0
initial apicid  : 0
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:

processor       : 1
vendor_id       : AuthenticAMD
cpu family      : 25
model           : 1
model name      : AMD EPYC 7763 64-Core Processor
stepping        : 1
microcode       : 0xffffffff
cpu MHz         : 3243.359
cache size      : 512 KB
physical id     : 0
siblings        : 2
core id         : 0
cpu cores       : 1
apicid          : 1
initial apicid  : 1
fpu             : yes
fpu_exception   : yes
cpuid level     : 13
wp              : yes
flags           : fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl tsc_reliable nonstop_tsc cpuid extd_apicid aperfmperf pni pclmulqdq ssse3 fma cx16 pcid sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand hypervisor lahf_lm cmp_legacy svm cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw topoext invpcid_single vmmcall fsgsbase bmi1 avx2 smep bmi2 erms invpcid rdseed adx smap clflushopt clwb sha_ni xsaveopt xsavec xgetbv1 xsaves clzero xsaveerptr rdpru arat npt nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold v_vmsave_vmload umip vaes vpclmulqdq rdpid fsrm
bugs            : sysret_ss_attrs null_seg spectre_v1 spectre_v2 spec_store_bypass srso
bogomips        : 4890.86
TLB size        : 2560 4K pages
clflush size    : 64
cache_alignment : 64
address sizes   : 48 bits physical, 48 bits virtual
power management:
```
9. Run the command **top** and type **q** to quit. ***(1 mark)*** 

```bash
top - 09:26:28 up 38 min,  0 users,  load average: 0.15, 0.18, 0.28
Tasks:  24 total,   1 running,  23 sleeping,   0 stopped,   0 zombie
%Cpu(s):  6.7 us,  3.3 sy,  0.0 ni, 90.0 id,  0.0 wa,  0.0 hi,  0.0 si,  0.0 st
MiB Mem :   7929.6 total,    488.4 free,   1587.6 used,   5853.6 buff/cache
MiB Swap:      0.0 total,      0.0 free,      0.0 used.   6025.9 avail Mem 

    PID USER      PR  NI    VIRT    RES    SHR S  %CPU  %MEM     TIME+ COMMAND                           
      1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.06 docker-init                       
      7 codespa+  20   0    7236   1792   1792 S   0.0   0.0   0:00.02 sleep                             
     22 root      20   0   12196   3480   2560 S   0.0   0.0   0:00.00 sshd                              
    345 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.01 sh                                
    375 root      20   0    2616   1536   1536 S   0.0   0.0   0:00.00 sh                                
    539 codespa+  20   0    2624   1664   1664 S   0.0   0.0   0:00.00 sh                                
    548 codespa+  20   0 1321888  98792  45312 S   0.0   1.2   0:10.03 node                              
    583 codespa+  20   0 1240564  55120  41216 S   0.0   0.7   0:00.37 node                              
   1002 codespa+  20   0 1126080  63544  42240 S   0.0   0.8   0:02.37 node                              
   2276 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                
   2338 root      20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                
   2530 codespa+  20   0   16496  11392   3456 S   0.0   0.1   0:00.08 bash                              
   3192 root      20   0 1983432  84524  52736 S   0.0   1.0   0:00.32 dockerd                           
   3200 root      20   0 1724676  46028  30464 S   0.0   0.6   0:00.52 containerd                        
   9905 codespa+  20   0    2616   1408   1408 S   0.0   0.0   0:00.00 sh                                
   9972 root      20   0    2616   1664   1664 S   0.0   0.0   0:00.00 sh                                
  10174 codespa+  20   0   21.5g 340948  49920 S   0.0   4.2   0:28.25 node                              
  10185 codespa+  20   0 1240564  57592  41344 S   0.0   0.7   0:00.24 node                              
  10211 codespa+  20   0 1010356  69492  40832 S   0.0   0.9   0:03.04 node       
 ```
10. Run the command **uname -a**. ***(1 mark)*** 
```bash
@najwakzaman ➜ /workspaces/OSProject (main) $ uname -a
Linux codespaces-500d4a 6.5.0-1021-azure #22~22.04.1-Ubuntu SMP Tue Apr 30 16:08:18 UTC 2024 x86_64 x86_64 x86_64 GNU/Linux
```
11. What is the available free memory in the system. 495 Mi
12. What is the available disk space mounted on /workspace. ***(1 mark)*** 5.9 Gi
13. Name the version and hardware architecture of the linux Virtual environment. ***(1 mark)*** 
Architecture : AMD EPYC 7763 64-Core Processor
14. What is the difference between **ls** vs **ls -asl**. ***(1 mark)*** 
- ls is used to list the content of directory, ls -asl is used to provide more detailed listing of directory such as hidden file, size, and detailed information about the file in directory.
15. What is the TLB size of the Virtual CPU. ***(1 mark)*** 2560 4K pages
16. What is the CPU speed of the Virtual CPU. ***(1 mark)*** 3243.359Mhz
17. What is the top running process that consumes the most CPU cycles. ***(1 mark)***
```bash
 1 codespa+  20   0    1136    640    640 S   0.0   0.0   0:00.06 docker-init   
 ```

## Running your own container instance.

1. At the terminal, run a linux instance. By typing the following command. 
```
@nuradilahka ➜ /workspaces/OSProjects (main) $ docker pull debian
Using default tag: latest
latest: Pulling from library/debian
fea1432adf09: Pull complete 
Digest: sha256:a92ed51e0996d8e9de041ca05ce623d2c491444df6a535a566dabd5cb8336946
Status: Downloaded newer image for debian:latest
docker.io/library/debian:latest

@nuradilahka ➜ /workspaces/OSProjects (main) $ docker run --detach -it debian
bc027a914792792c8e8ee3ce2ab8936f6a8773cdaecef5fcc382026a0fc8fb27
```
2. This will run the debian container. To check if the debian container is running, type
```bash
@nuradilahka ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
bc027a914792   debian    "bash"    18 seconds ago   Up 17 seconds             agitated_williamson
```

3. Keep note of the name used by your container, this is usually given random names unless you specify your own name. Now run a bash command on the container. Make sure you use the name of your container instead of the one shown here. 
```bash
@nuradilahka ➜ /workspaces/OSProject (main) $ docker exec -i -t agitated_williamson /bin/bash
```

4. Create a file on the container. First you must make sure you are in the bash command prompt of the container. The container is new, and does not have any software other than the debian OS. To create a new file, you will need an editor installed. In the bash shell of the container, run the package manager apt-get to install nano text editor. 

```bash
root@bc027a914792:/# apt-get update
Get:1 http://deb.debian.org/debian bookworm InRelease [151 kB]
Get:2 http://deb.debian.org/debian bookworm-updates InRelease [55.4 kB]
Get:3 http://deb.debian.org/debian-security bookworm-security InRelease [48.0 kB]
Get:4 http://deb.debian.org/debian bookworm/main amd64 Packages [8786 kB]
Get:5 http://deb.debian.org/debian bookworm-updates/main amd64 Packages [13.8 kB]
Get:6 http://deb.debian.org/debian-security bookworm-security/main amd64 Packages [160 kB]
Fetched 9214 kB in 1s (9545 kB/s)                         
Reading package lists... Done
root@bc027a914792:/# apt-get install nano
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following additional packages will be installed:
  libgpm2 libncursesw6
Suggested packages:
  gpm hunspell
The following NEW packages will be installed:
  libgpm2 libncursesw6 nano
0 upgraded, 3 newly installed, 0 to remove and 0 not upgraded.
Need to get 837 kB of archives.
After this operation, 3339 kB of additional disk space will be used.
Do you want to continue? [Y/n] y
Get:1 http://deb.debian.org/debian bookworm/main amd64 libncursesw6 amd64 6.4-4 [134 kB]
Get:2 http://deb.debian.org/debian bookworm/main amd64 nano amd64 7.2-1 [689 kB]
Get:3 http://deb.debian.org/debian bookworm/main amd64 libgpm2 amd64 1.20.7-10+b1 [14.2 kB]
Fetched 837 kB in 0s (35.5 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libncursesw6:amd64.
(Reading database ... 6090 files and directories currently installed.)
Preparing to unpack .../libncursesw6_6.4-4_amd64.deb ...
Unpacking libncursesw6:amd64 (6.4-4) ...
Selecting previously unselected package nano.
Preparing to unpack .../archives/nano_7.2-1_amd64.deb ...
Unpacking nano (7.2-1) ...
Selecting previously unselected package libgpm2:amd64.
Preparing to unpack .../libgpm2_1.20.7-10+b1_amd64.deb ...
Unpacking libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libgpm2:amd64 (1.20.7-10+b1) ...
Setting up libncursesw6:amd64 (6.4-4) ...
Setting up nano (7.2-1) ...
update-alternatives: using /bin/nano to provide /usr/bin/editor (editor) in auto mode
update-alternatives: using /bin/nano to provide /usr/bin/pico (pico) in auto mode
Processing triggers for libc-bin (2.36-9+deb12u7) ...
root@bc027a914792:/# nano helloworld.txt
root@bc027a914792:/# ls -la
total 72
drwxr-xr-x   1 root root 4096 Jun 16 04:53 .
drwxr-xr-x   1 root root 4096 Jun 16 04:53 ..
-rwxr-xr-x   1 root root    0 Jun 16 04:51 .dockerenv
lrwxrwxrwx   1 root root    7 Jun 12 00:00 bin -> usr/bin
drwxr-xr-x   2 root root 4096 Jan 28 21:20 boot
drwxr-xr-x   5 root root  360 Jun 16 04:51 dev
drwxr-xr-x   1 root root 4096 Jun 16 04:53 etc
-rw-r--r--   1 root root   36 Jun 16 04:53 helloworld.txt
drwxr-xr-x   2 root root 4096 Jan 28 21:20 home
lrwxrwxrwx   1 root root    7 Jun 12 00:00 lib -> usr/lib
lrwxrwxrwx   1 root root    9 Jun 12 00:00 lib64 -> usr/lib64
drwxr-xr-x   2 root root 4096 Jun 12 00:00 media
drwxr-xr-x   2 root root 4096 Jun 12 00:00 mnt
drwxr-xr-x   2 root root 4096 Jun 12 00:00 opt
dr-xr-xr-x 221 root root    0 Jun 16 04:51 proc
drwx------   1 root root 4096 Jun 16 04:53 root
drwxr-xr-x   3 root root 4096 Jun 12 00:00 run
lrwxrwxrwx   1 root root    8 Jun 12 00:00 sbin -> usr/sbin
drwxr-xr-x   2 root root 4096 Jun 12 00:00 srv
dr-xr-xr-x  12 root root    0 Jun 16 04:51 sys
drwxrwxrwt   1 root root 4096 Jun 16 04:53 tmp
drwxr-xr-x   1 root root 4096 Jun 12 00:00 usr
drwxr-xr-x   1 root root 4096 Jun 12 00:00 var

```

5. Edit your helloworld.txt, create your messsage and save by typing ctrl-X. Once saved, explore using the container to see where the file is located. Then exit the shell, by typing **exit**.

```bash
root@bc027a914792:/# find / -name helloworld.txt
/helloworld.txt
root@bc027a914792:/# exit
exit
```

6. Stop the container and run **docker ps -a**, and restart the container again. Is your file in the container still available?
```bash 
@nuradilahka ➜ /workspaces/OSProject (main) $ docker stop agitated_williamson
agitated_williamson

@nuradilahka ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                        PORTS     NAMES
bc027a914792   debian    "bash"    4 minutes ago   Exited (137) 13 seconds ago             agitated_williamson

@nuradilahka ➜ /workspaces/OSProject (main) $ docker restart agitated_williamson
agitated_williamson
```

7. Stop the container and delete the container. What happened to your helloworld.txt?

```bash 
@nuradilahka ➜ /workspaces/OSProject (main) $ docker stop agitated_williamson
agitated_williamson
@nuradilahka ➜ /workspaces/OSProject (main) $ docker ps -a
CONTAINER ID   IMAGE     COMMAND   CREATED         STATUS                        PORTS     NAMES
bc027a914792   debian    "bash"    5 minutes ago   Exited (137) 11 seconds ago             agitated_williamson
@nuradilahka ➜ /workspaces/OSProject (main) $ docker rm agitated_williamson
agitated_williamson
```

helloworld.txt is removed. 
Deleting the container resulting in all its data, including the helloworld.txt file, is removed. 

***Questions:***

1. Are files in the container persistent. Why not?. ***(1 mark)*** 
- Container are designed to be lightweight, that when it is stopped or removed, any changes to the file within the container will be lost.
2. Can we run two, or three instances of debian linux? . ***(1 mark)*** 
- Yes, we cun run two or three instances of debian linux.

## Running your own container with persistent storage

1. In the previous experiment, you might have notice that containers are not persistent. To make storage persistent, you will need to mount them. 
At the terminal, create a new directory called **myroot**, and run a instance of debian linux and mount myroot to the container. Find out the exact path of my root, and mount it as the root folder in the debian container. 

```bash 
@nuradilahka ➜ /workspaces/OSProject (main) $ mkdir myroot
@nuradilahka ➜ /workspaces/OSProject (main) $ cd myroot
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ pwd
/workspaces/OSProject/myroot
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ docker run --detach -it -v /workspaces/OSProject/myroot:/root debian
2aa98fc97dee277e78581473074f13a97e1436e6d31bd9ecfcc1aef08a12e3c6
```
2. Create a file in /root on the container, the files should also appear in myroot of your host VM.

```bash 
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ docker run -it --name my-debian -v /home/user/myroot:/myroot debian
touch /myroot/myfile.txt
exit
root@f8f979ddb313:/# touch /myroot/myfile.txt
root@f8f979ddb313:/# exit
exit

@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ ls -l /home/user/myroot
helloworld.txt
```

***Questions:***

1. Check the permission of the files created in myroot, what user and group is the files created in docker container on the host virtual machine? . ***(2 mark)*** User: root Group: root.
2. Can you change the permission of the files to user codespace.  You will need this to be able to commit and get points for this question. ***(2 mark)***
```bash
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ docker stop my-debian
my-debian
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ docker rm my-debian
my-debian
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ docker run -it --name my-debian -v /home/user/myroot:/myroot debian
root@c068abfa3981:/# touch /myroot/myfile.txt
root@c068abfa3981:/# exit 
exit
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ sudo chown -R codespace:codespace /home/user/myroot
@nuradilahka ➜ /workspaces/OSProject/myroot (main) $ ls -l /home/user/myroot
total 0
-rw-r--r-- 1 codespace codespace 0 Jun 16 05:07 myfile.txt

```
*** User: codespace Group: codespace***

## You are on your own, create your own static webpage

1. Create a directory called webpage in your host machine
```bash
@nuradilahka ➜ ~ $ mkdir webpage
@nuradilahka ➜ ~ $ cd webpage
```
2. Inside the directory, create a page index.html, with any content you would like

```bash
@nuradilahka ➜ ~/webpage $ touch index.html
@nuradilahka ➜ ~/webpage $ nano index.html
```

![index.html](https://github.com/najwakzaman/OSProject/assets/145886073/38e4c948-2d3d-46dd-9c08-bc754fbe2127)


3. Then, run the apache webserver and mount the webpage directory to it. Hint:
```bash
@nuradilahka ➜ ~/webpage $ docker run --detach -v /workspaces/OSProject/webpage:/usr/local/apache2/htdocs/ -p 8080:80 httpd
Unable to find image 'httpd:latest' locally
latest: Pulling from library/httpd
2cc3ae149d28: Pull complete 
840d8df643b2: Pull complete 
4f4fb700ef54: Pull complete 
9d1465828338: Pull complete 
4a16a983b278: Pull complete 
9129890c4c50: Pull complete 
Digest: sha256:10182d88d7fbc5161ae0f6f758cba7adc56d4aae2dc950e51d72c0cf68967cea
Status: Downloaded newer image for httpd:latest
73942f15de1e991fabdf7e7583d21b8c695c3a7ab20c228b0b64b074efb3ba80
```

4. If it works, codespace will trigger a port assignment and provide a URL for you to access your webpage like the one below.

![webpage](https://github.com/najwakzaman/OSProject/assets/145886073/8c1af567-9691-48f7-8f67-dfa28d534631)# OSProject Running Containers for Application Development


5. You can also see the Port in the **PORTS** tab, next to the terminal tab.

6. You can then access your website by adding an index.html towards the end of your url link, like the one below. 

 <img src="./images/helloworldweb.png" width="70%">

***Questions:***

1. What is the permission of folder /usr/local/apache/htdocs and what user and group owns the folder? . ***(2 mark)*** 

Permissions of Folder /usr/local/apache2/htdocs:

Permissions: drwxr-xr-x

User and Group:
User: root
Group: root.

2. What port is the apache web server running. ***(1 mark)*** 80.
3. What port is open for http protocol on the host machine? ***(1 mark)*** 8080.

## Create SUB Networks

1. In docker, you can create your own private networks where you can run multiple services, in this part, we will create two networks, one called bluenet and the other is rednet
2. Run the docker create network to create you networks like the ones below
```bash
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network create bluenet
Error response from daemon: network with name bluenet already exists
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network create rednet
06abaa79737e523dff139bb8e3f820c9211234de282e62f441a01afc2e21b346
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network ls

## STEP 2: (automatically running)
## Create (1) Container in background called "c1" running busybox image ##
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker run -itd --net bluenet --name c1 busybox sh
Unable to find image 'busybox:latest' locally
latest: Pulling from library/busybox
ec562eabd705: Pull complete 
Digest: sha256:9ae97d36d26566ff84e8893c64a6dc4fe8ca6d1144bf5b87b2b85a32def253c7
Status: Downloaded newer image for busybox:latest
dc469b19d7baa0547c6f592e6718a89d871978e49d57b8aea14cdc5ff3b2b4f8
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker run -itd --net rednet --name c2 busybox sh
43ebe3472970ba5aa3903210893efb23bf6a9083edb39a41d9f7babbcd1e35e0
```
***Questions:***

1. Describe what is busybox and what is command switch **--name** is for? . ***(2 mark)***
   BusyBox: BusyBox is a software suite that provides several Unix utilities in a single executable file. It is often used in embedded systems and Docker containers because it offers a lightweight set of tools that are        efficient and functional.
   --name switch: The --name switch in Docker is used to assign a name to a container. This makes it easier to reference the container by name rather than by its container ID, simplifying management and identification of      the container.

2. Explore the network using the command ```docker network ls```, show the output of your terminal. ***(1 mark)***
   ![Screenshot 2024-06-16 213712](https://github.com/najwakzaman/OSProject/assets/137309946/f090c955-ccdd-4692-acf0-41d3513e603e)

3. Using ```docker inspect c1``` and ```docker inspect c2``` inscpect the two network. What is the gateway of bluenet and rednet.? ***(1 mark)***
   bluenet - Gateway: "172.18.0.1"
   rednet - Gateway": "172.19.0.1"
   
4. What is the network address for the running container c1 and c2? ***(1 mark)***
   c1(bluenet)-"IPAddress": "172.18.0.2"
   c2(rednet)-"IPAddress": "172.19.0.2",
   
5. Using the command ```docker exec c1 ping c2```, which basically tries to do a ping from container c1 to c2. Are you able to ping? Show your output . ***(1 mark)*** 
![Screenshot 2024-06-16 215524](https://github.com/najwakzaman/OSProject/assets/137309946/e93c18ad-d4ab-4796-a811-1cb285e6d114)
Answer : No , Since c1 and c2 are on different networks (bluenet and rednet respectively), they cannot communicate directly with each other. Therefore, the ping command fails with a "bad address" error.

## Bridging two SUB Networks
1. Let's try this again by creating a network to bridge the two containers in the two subnetworks
```
@faheyraezzah ➜ /workspaces/OSProject (main) $  docker network create bridgenet
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c1
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network connect bridgenet c2
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker exec c1 ping c2
```
***Questions:***

1. Are you able to ping? Show your output . ***(1 mark)*** __Fill answer here__.
   Yes . I am able to ping c2 from c1 successfully.
   ![Screenshot 2024-06-16 220821](https://github.com/najwakzaman/OSProject/assets/137309946/9a5914c4-327d-4620-8b97-ba4d2a459e8f)

2. What is different from the previous ping in the section above? ***(1 mark)*** __Fill answer here__.
   
   Previous Ping: The previous ping attempt failed with the error ping: bad address 'c2' because c1 and c2 were on separate, isolated networks (bluenet and rednet) and couldn't communicate with each other directly.

   Current Ping: After connecting both containers to the bridgenet network, they are now part of a common network, allowing them to communicate with each other. As a result, the ping from c1 to c2 is successful.

## Intermediate Level (10 marks bonus)

### Node.js and MySQL in Docker Containers

This guide will help you set up a simple Node.js website that retrieves a random row from a MySQL database. Both the MySQL server and the Node.js server will run in separate Docker containers on two separate networks. Your job is to make it work by making the two containers in two separate network bridged together.

#### Step 1: Set Up the Docker Network

Create a Docker network to for the two containers.
For mysql, call it **mysqlnet** for nodejs call it **nodejsnet** .

```sh
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network create mysqlnet
fac2d7ef92668402da163a452e839f6354648c882d96b8087b4ce57d1c8bd455
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker network create nodejsnet
0e11ebb0d837e3443b1a3d7085af81dbd633deee846cf08c8832b7eb5f098795
```
#### Step 2: Set Up the MySQL Container

Run a MySQL container on the created network.

```sh
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker run --name mysql-container --network mysqlnet -e MYSQL_ROOT_PASSWORD=rootpassword -e MYSQL_DATABASE=mydatabase -e MYSQL_USER=myuser -e MYSQL_PASSWORD=mypassword -d mysql:latest
Unable to find image 'mysql:latest' locally
latest: Pulling from library/mysql
07bc88e18c4a: Pull complete 
1a9c1668bf49: Pull complete 
1021dda8eecf: Pull complete 
fb61b56acac1: Pull complete 
0bca83908a5b: Pull complete 
165e8b3d37ca: Pull complete 
3e1b086f1295: Pull complete 
dba651668484: Pull complete 
ed90f5355e12: Pull complete 
0412f59ab2b5: Pull complete 
Digest: sha256:aa021e164da6aacbefc59ed0b933427e4835636be380f3b6523f4a6c9564e1f0
Status: Downloaded newer image for mysql:latest
39dff18d255f6aea8cc319d0d53363d877b73a9dea1156940c529dd329ce29b1
```

#### Step 3: Set Up the Node.js Container

1. **Create a directory for your Node.js application and initialize it.**

  ```sh
@faheyraezzah ➜ /workspaces/OSProject (main) $  mkdir nodejs-app
@faheyraezzah ➜ /workspaces/OSProject (main) $ cd nodejs-app
@faheyraezzah ➜ /workspaces/OSProject/nodejs-app (main) $ npm init -y
Wrote to /workspaces/OSProject/nodejs-app/package.json:

{
  "name": "nodejs-app",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": ""
}

@faheyraezzah ➜ /workspaces/OSProject/nodejs-app (main) $ npm install express mysql

added 76 packages, and audited 77 packages in 11s

12 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
    ```

2. **Create a file named `index.js` with the following content:**

    ```js
    const express = require('express');
    const mysql = require('mysql');

    const app = express();
    const port = 3000;

    // Create a MySQL connection
    const connection = mysql.createConnection({
      host: 'mysql-container',
      user: 'myuser',
      password: 'mypassword',
      database: 'mydatabase'
    });

    // Connect to MySQL
    connection.connect((err) => {
      if (err) {
        console.error('Error connecting to MySQL:', err);
        return;
      }
      console.log('Connected to MySQL');
    });

    // Define a route to get a random row
    app.get('/random', (req, res) => {
      const query = 'SELECT * FROM mytable ORDER BY RAND() LIMIT 1';
      connection.query(query, (err, results) => {
        if (err) {
          console.error('Error executing query:', err);
          res.status(500).send('Server Error');
          return;
        }
        res.json(results[0]);
      });
    });

    // Start the server
    app.listen(port, () => {
      console.log(`Server running at http://localhost:${port}`);
    });
    ```

3. **Create a Dockerfile for the Node.js application:**

    ```Dockerfile
    # Use the official Node.js image
    FROM node:14

    # Create and change to the app directory
    WORKDIR /usr/src/app

    # Copy application dependency manifests to the container image
    COPY package*.json ./

    # Install production dependencies
    RUN npm install

    # Copy local code to the container image
    COPY . .

    # Run the web service on container startup
    CMD [ "node", "index.js" ]
    ```

#### Step 4: Build and Run the Node.js Container

1. **Build the Docker image for the Node.js application.**

    ```sh
   @faheyraezzah ➜ /workspaces/OSProject (main) $ docker build -t nodejs-app ./nodejs-app

   @faheyraezzah ➜ /workspaces/OSProject/nodejs-app (main) $ docker build -t nodejs-app /workspaces/OSProject/nodejs-app
    ```

2. **Run the Node.js container on the same network as the MySQL container.**

    ```sh
@faheyraezzah ➜ /workspaces/OSProject (main) $ docker run --name nodejs-container --network nodejsnet -p 3000:3000 -d nodejs-app
ef294e87c6a72858fb2819075566cf22e6c8756b0d85f64137e9a24e04a2d7be
    ```

#### Step 5: Test the Setup

You can now test the setup by accessing the Node.js application in your browser or using a tool like `curl`:

```sh
@faheyraezzah ➜ /workspaces/OSProject (main) $  curl http://localhost:3000/random
```

#### Step 6: Ensure `mytable` is Populated

Make sure you have created the `mytable` table and populated it with some data in your MySQL database for the above steps to work correctly.

You can use the following SQL commands to create and populate the table (run these commands in the MySQL container):

```sql
mysql> CREATE TABLE mytable (
    ->   id INT AUTO_INCREMENT PRIMARY KEY,
    ->   name VARCHAR(255) NOT NULL,
    ->   value VARCHAR(255) NOT NULL
    -> );
 value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');Query OK, 0 rows affected (0.11 sec)

mysql> 
mysql> INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
Query OK, 3 rows affected (0.04 sec)
Records: 3  Duplicates: 0  Warnings: 0
);

INSERT INTO mytable (name, value) VALUES ('example1', 'value1'), ('example2', 'value2'), ('example3', 'value3');
```

### Summary

You have now set up a Node.js application in a Docker container on nodejsnet netowrk and a MySQL database in another Docker container on mysqlnet network. Now bridge the two network together.

***Questions:***

1. What is the output of step 5 above, explain the error? ***(1 mark)*** __Fill answer here__.
   ![Screenshot 2024-06-17 002446](https://github.com/najwakzaman/OSProject/assets/137309946/059d5f8d-d5a4-471c-9403-fe0d97d0931f)    
   The "Server Error" message indicates that there was a problem when trying to handle the request to http://localhost:3000/random from our Node.js application. This error commonly occurs due to issues related to              database connectivity, query execution, or error handling within the Node.js application itself.

2. Show the instruction needed to make this work. ***(1 mark)*** __Fill answer here__.
   To make the setup work , connect the Node.js container to the mysqlnet network using the following command : 
    ```sh
    docker network connect mysqlnet nodejs-container
   ```



## What to submit

1. Make sure to commit all changes on your source control, and make sure your source control is sync to the repository. 
2. Check your repository link, to see if all the files and answers are included in the repository. 
3. Submit through italeem, by providing the link to your repository.
4. Due by ***AS STATED IN ITALEEM SYSTEM***
