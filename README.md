# lollipop-playbook

LoLLIPoP を動作させる環境をセットアップします

## 使用法

    $ ansible-playbook -i "<host>," -u <user> -K playbooks/init-playground.yaml -e "ip_addr=192.0.2.10/24"
