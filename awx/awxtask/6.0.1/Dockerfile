FROM ansible/awx_task:4.0.0
USER root
ADD launch_awx_task.sh /usr/bin/launch_awx_task.sh
ADD settings.py /etc/tower/settings.py
RUN chmod +rx /usr/bin/launch_awx_task.sh
USER 1000
