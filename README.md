# Hades_project
#
#modify date:20150703,22:50
#
#install grs and example and step:
#sudo apt-get install python-dev
#sudp apt-get install python-pip
#sudo pip install grs
#python
#>>> from grs import Stock
#>>> Stock('2618').info
#
#version:0.03
#
#20150617 - version 0.01
#         (1) list bone of program
#
#20150619 - version 0.01
#         (1) search value in file sub function
#
#20150620 - version 0.01
#         (1) gen target file to save target value
#         (2) finish date and yesterday and the day before yesterday calculate
#         (3) timer function
#         (4) send mail function
#20150621 - version 0.01
#         (1) algorithm of buy and keep
#20150622 - version 0.02
#         (1) define main_process function
#         (2) timer can ruting to call main_process function
#         (3) create share folder for record share of stock
#         (4) base algonism to auto sale out and buy in stock
#         (5) record trade price file
#20150624 - versioin 0.02
#         (1) run many stock in one time
#         (2) Debug flag
#         (3) rm "target_sdate1_val.txt"
#         (4) different stock save diff csv file
#20150701 - version 0.03
#         (1) use "cron" table to count day,"cron" to loop main.py, only run main.py at mon to fri
#              x1. sudo su, no need do this step
#              2. crontab -e
#              3. 40 13 * * 1-5 /home/pi/Hades_project/main.py > /home/pi/Hades_project/syslog.txt
#              4. /etc/init.d/cron restart
#         (2) apach2 server as fw update interface
#              1. input 192.168.1.116 into browser
#              2. chose the main.py 
#              3. the script "fw_Hades_update.sh" will take care of replace main.py file 
#         (3) merge mail "keep or sale" & "trade price" into one mail
#

#
#Next action:
#         (3) read a external file.txt which your stock list as "STOCK=" input
#         (6) manual input share of stock and write into record share file
#         ok - (8) record CPU temp into mail and file(CPU_temp.txt)
#         (9) csv file depand on different folder to save
#         (10) two Stock should send one mail...
#
#
