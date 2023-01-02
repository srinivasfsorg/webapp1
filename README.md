#PS C:\Users\akhil\projec\crudapp>cd

PS C:\Users\akhil\projec\crudapp>tar

PS C:\Users\akhil\projec\crudapp>ls

PS C:\Users\akhil\projec\crudapp>cd..

PS C:\Users\akhil\projec>cd ..

PS C:\Users\akhil>tar -cvzf webapp.tar.gz crudapp

PS C:\Users\akhil\projec\crudapp>ls .\webapp.tar.gz

PS C:\Users\akhil\projec\crudapp>scp -i sandbox.pem webapp.tar.gz centos@13.232.83.118:

PS C:\Users\akhil\projec\crudapp>ssh -i sandbox.pem centos@13.232.83.118

[centos@-172-31-11-8 ~]$ls

[centos@-172-31-11-8 ~]$du -sch webapp.tar.gz

[centos@-172-31-11-8 ~]$tar webapp.tar.gz crudapp

[centos@-172-31-11-8 ~]$tar -xvzf webapp.tar.gz

[centos@-172-31-11-8 ~]$ls

[centos@-172-31-11-8 ~]$ls -lrt

[centos@-172-31-11-8 ~]$curl localhost:8000

[centos@-172-31-11-8 ~]$curl 127.0.0.1:8000

[centos@-172-31-11-8 ~]$ gunicorn main.wsgi --bind 0.0.0.0:8000

 

3.111.42.234:8000/

 

 

