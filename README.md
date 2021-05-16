[ec2-user@ip-172-31-29-8 ansible-automation]$ history
    1  sudo su - 
    2  ls -ltr
    3  ansible --version
    4  ssh-keygen
    5  ls -ltr
    6  cat ~/.ssh/id_rsa.pub 
    7  ssh 172.31.27.34
    8  ansible localhost -m ping 
    9  ansible 172.31.27.34 -m ping 
   10  ls -ltr
   11  ls -ltr /etc/
   12  sudo mkdir /etc/ansible
   13  sudo vi /etc/ansible/hosts
   14  ansible all -m ping 
   15  sudo vi /etc/ansible/hosts
   16  ansible all -m ping 
   17  cat ~/.ssh/id_rsa.pub 
   18  cat ~/.ssh/authorized_keys 
   19  vi ~/.ssh/authorized_keys 
   20  ansible all -m ping 
   21  sudo vi /etc/ansible/hosts
   22  ansible all -m ping 
   23  ansible webserver -m ping 
   24  ansible webserver -m shell -p uptime
   25  ansible webserver -m shell -a uptime
   26  ansible all -m shell -a uptime
   27  uptime
   28  ls -ltr
   29  mkdir ansible-automation
   30  cd ansible-automation/
   31  mkdir web-s
   32  cd web-s/
   33  ls -ltr
   34  vi 
   35  vi apache.yaml
   36  vi index.html
   37  ls -ltr
   38  vi apache.yaml
   39  ls -ltr
   40  vi apache.yaml
   41  ansible-playbook apache.yaml
   42  ls -ltr
   43  cat index.html 
   44  vi apache.yaml 
   45  cd ../
   46  ls -ltr
   47  mkdir webserver
   48  cd webserver/
   49  ls -ltr
   50  vi apache.yaml
   51  ls -ltr
   52  mkdir roles
   53  cd roles/
   54  ls -ltr
   55  mkdir web app
   56  ls -ltr
   57  cd web/
   58  ls -ltr
   59  mkdir tasks
   60  cd tasks/
   61  ls -ltr
   62  vi main.yaml
   63  cat ~/ansible-automation/web-s/apache.yaml 
   64  vi main.yaml
   65  cd ../
   66  ls -ltr
   67  cd app/
   68  mkdir tasks
   69  cd tasks/
   70  vi main.yaml
   71  cd .././
   72  cd ../../
   73  ls -ltr
   74  tree
   75  sudo yum install tree
   76  tree
   77  cat apache.yaml 
   78  ansible-playbook apache.yaml 
   79  ls -lr
   80  vi index.html
   81  ansible-playbook apache.yaml 
   82  ls -ltr
   83  rm -rf index.html 
   84  ls -ltr
   85  mkdir group_vars
   86  cat apache.yaml 
   87  vi group_vars/webserver
   88  cd roles/web/
   89  ls -ltr
   90  mkdir tempalates
   91  cd tempalates/
   92  vi index.html.j2
   93  cd ../
   94  vi tasks/main.yaml 
   95  cat tempalates/index.html.j2 
   96  cat ../../group_vars/webserver 
   97  ls -ltr
   98  cd ../../
   99  ansible-playbook apache.yaml 
  100  vi roles/web/tasks/main.yaml 
  101  mv roles/web/tempalates roles/web/templates
  102  ansible-playbook apache.yaml 
  103  sudo vi /etc/ansible/hosts 
  104  vi ~/.ssh/ansible-may-2021.pem
  105  chmod 400 ~/.ssh/ansible-may-2021.pem
  106  sudo vi /etc/ansible/hosts 
  107  cp /etc/ansible/hosts  inventory
  108  ls -ltr
  109  ansible-playbook -i inventory apache.yaml 
  110  cat inventory 
  111  ls -ltr
  112  touch abc
  113  ls -ltr
  114  rm -rf abc 
  115  cd roles/web/
  116  ls -ltr
  
  117  cat tasks/main.yaml 
  118  cd ../../
  119  ansible-playbook -i inventory apache.yaml 
  120  cd roles/web/
  121  ls -ltr
  122  cd we
  123  ls -ltr
  124  mkdir handlers
  125  cd handlers/
  126  vi main.yaml
  127  cd ../
  128  vi tasks/main.yaml 
  129  vi templates/index.html.j2 
  130  cd ../../
  131  vi roles/web/tasks/main.yaml 
  132  vi roles/web/handlers/main.yaml 
  133  ansible-playbook -i inventory apache.yaml 
  134  cat roles/web/handlers/main.yaml 
  135  cd ../
  136  cd ansible-automation/
  137  ls -ltr
  138  sudo yum install git -y
  139  git init
  140  git add README.md
  141  git commit -m "first commit"
  142  git add .
  143  git commit -m "first commit"
  144  git branch -M main
  145  git remote add origin https://github.com/devopsmar2021/ansible-automation.git
  146  git push -u origin main
  147  history
