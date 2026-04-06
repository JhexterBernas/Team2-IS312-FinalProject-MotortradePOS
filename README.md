# How to Access the MotortradePOS

1. Download the Zip File "Team2-IS312-FinalProject-MotortradePOS" above.
2. After Downloading, Go-to-File Manager in your computer and find the downloaded file.
3. Right click the file then "Extract All".
4. Click/open the Folder(The extracted file) dont click any files/folder inside it.
5. From that folder hold "Shift" in your keyboard and right click.
6. Click the "Open Powershell" and wait.
7. After opening the powershell the following command must be prompted.

# Command in Powershell/Terminal

One at a time

1.python -m pip install django

2.python -m pip install Pillow

8.Your Computer is settled! after the command successfully prompted you can run the MotortradePOS! Just prompt this

3.python manage.py runserver

9.Wait for the Deployment Server, It should look like this "http://127.0.0.1:8000/".

10. To run this Hold "CTRL key" then click the server and voilà you successfully run the prototype locally!

# Optional Command

4.python manage.py shell -c "from MotortradeSystem.models import Transaction, TransactionItem; TransactionItem.objects.all().delete(); Transaction.objects.all().delete()"

This command is IF you want to delete/refresh the transactrion History ONLY!, DON'T command this if you are okay with the existing history.

# Credentials of MotortradePOS

Username: CTDN-Jherico
Password: Pandi3014
