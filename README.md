# Wow Yin Yang Music-Podcast platform Project


## How to setup and start the containers
**Important** - you need Docker Desktop installed

1. Clone this repository.  
1. Create a file named `db_root_password.txt` in the `secrets/` folder and put inside of it the root password for MySQL. 
1. Create a file named `db_password.txt` in the `secrets/` folder and put inside of it the password you want to use for the a non-root user named webapp. 
1. In a terminal or command prompt, navigate to the folder with the `docker-compose.yml` file.  
1. Build the images with `docker compose build`
1. Start the containers with `docker compose up`.  To run in detached mode, run `docker compose up -d`.

## How to insert fake data 

1.Open the fake.py file

2.Follow the instruction at the bottom of the file, run the functions accordingly to instruction (Rememeber to comment out the function that has been run!)

## Project Presentation video link
[https://drive.google.com/file/d/1rJSyPmhIhcwCS8ubpfQfzTG3LQ_5flWG/view?usp=drive_link]
## Team memebers
1.Junhua Chen   

2.Lang Shao

3.Jiada Li

4.Qingyu Jiang

## AppSmith UI repo is here:

https://github.com/samueeelsiu/WYY-Appsmith-Final




