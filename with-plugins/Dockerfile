FROM mjgp/jenkins-docker:latest

COPY plugins.txt /tmp/plugins.txt

RUN /usr/local/bin/install-plugins.sh git
RUN /usr/local/bin/install-plugins.sh timestamper
RUN /usr/local/bin/install-plugins.sh job-dsl
RUN /usr/local/bin/install-plugins.sh startup-trigger-plugin
RUN /usr/local/bin/install-plugins.sh cloudbees-folder
RUN /usr/local/bin/install-plugins.sh parameterized-trigger
RUN /usr/local/bin/install-plugins.sh envinject
RUN /usr/local/bin/install-plugins.sh groovy
RUN /usr/local/bin/install-plugins.sh jdk-tool
RUN /usr/local/bin/install-plugins.sh workflow-aggregator
RUN /usr/local/bin/install-plugins.sh locale
RUN /usr/local/bin/install-plugins.sh dashboard-view
RUN /usr/local/bin/install-plugins.sh view-job-filters

RUN /usr/local/bin/install-plugins.sh < /tmp/plugins.txt
