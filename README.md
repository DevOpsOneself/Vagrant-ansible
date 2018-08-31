Vagrant-ansible
====

目录结构
-

        inventories   
            hosts   # Ansible 主机信息配置文件

        playbooks    # Ansible 主目录
            roles   #Ansible roles主目录
                role   #Ansible role
                    files   #role依赖文件
                        main.yml
                    tasks   #role tasks
                        main.yml
                    vars    #role 变量
                        main.yml
            xxx.yml   #各节点 Ansible配置文件

        nodes.yaml   #全部节点 Vagrant 配置文件

        Vagrantfile**#Vagrant 主文件

安装包路径
-
   [Oracle_jdk](http://www.oracle.com/technetwork/java/archive-139210.html)<br/>
   [Erlang_package](https://www.erlang.org/downloads)<br/>
   [RabbitMQ_Server](https://bintray.com/rabbitmq/all/rabbitmq-server/)<br/>
   [Wso2EI Release Artifact](https://wso2.com/integration/previous-releases/)<br/>
   [Wso2AM](https://wso2.com/api-management/previous-releases/)<br/>

Runtime
-
1 将依赖包放到对应role目录下的files文件夹下<br/>
2 修改对应vars文件夹下变量<br/>
