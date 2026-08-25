# Linux Practical Examination

**Linux version:** Ubuntu (Debian-based, as identified by apt package manager and Apache/2.4.66 Ubuntu build)
**Brief result/conclusion:** This examination tested various Linux system administration tasks. The executed commands successfully demonstrate basic file operations, user management, file permissions, web server installation (Apache), and text processing using grep. Questions not taught in the course syllabus were intentionally skipped as instructed.

---

### Q1. Basic File Operations
**Commands:**
`mkdir linuxexam`
`cd linuxexam/`
`nano student.txt course.txt result.txt`
`pwd`
`ls`

### Q2. File Management
**Commands:**
`cp student.txt student_backup.txt`
`mv course.txt linux_course.txt`
`rm result.txt`
`mkdir document backups_scripts`
`mv student_backup.txt backups/`
`ls -R`

### Q3. File Content Operations
**Commands:**
`nano student.txt`
`nano linux_course.txt`
`cat student.txt`
`cat linux_course.txt`
`head -3 linux_course.txt`
`tail -2 linux_course.txt`
`wc -l linux_course.txt`

### Q4. User Management
**Commands:**
`sudo adduser student01`
`id student01`
`su student01`
`pwd`
`who`

### Q5. Group Management
This topic is not covered by ravi sir

### Q6. File Permissions
**Commands:**
`mkdir project.txt`
`chmod 754 project.txt/`
`ls -l`
`chmod 640 project.txt/`
`sudo chown student01 project.txt/`
`ls -l`

### Q7. Permission Challenge
**Commands:**
`mkdir linuxexam`
`cd linuxexam/`
`mkdir public privet shared`
`chmod 777 public/`
`chmod 700 privet/`
`chmod 770 shared/`
`ls -ld`
`ls -l`
### Q8. Package Management
**Commands:**
`sudo apt-get update`
`sudo apt-get install apache2 -y`
`apache2 -v`
`sudo service apache2 start`
`sudo service apache2 status`
`sudo systemctl enable apache2`

### Q9. Apache Web Server Configuration
**Commands:**
`cd /var/www/html/`
`sudo nano index.html`
`sudo service apache2 restart`
`curl http://13.204.79.237`

### Q10. Process Management
This topic is not covered by ravi sir

### Q11. Search and Text Processing
**Commands:**
`nano student.txt`
`grep 'pune' student.txt`
`grep 'Pune' student.txt`
`grep -i 'pune' student.txt`
`grep -c 'Pune' student.txt`
`sort student.txt`
`find -type f -name 'student.txt'`
`find -type f -name "*.txt"`

### Q12. Linux Networking
This topic is not covered by ravi sir
