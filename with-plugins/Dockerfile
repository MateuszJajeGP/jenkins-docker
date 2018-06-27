FROM mjgp/jenkins-docker:latest

# tools
RUN /usr/local/bin/install-plugins.sh sbt
RUN /usr/local/bin/install-plugins.sh groovy
RUN /usr/local/bin/install-plugins.sh jdk-tool
RUN /usr/local/bin/install-plugins.sh git

# 3rd parties
RUN /usr/local/bin/install-plugins.sh slack
RUN /usr/local/bin/install-plugins.sh gitlab-merge-request-jenkins
RUN /usr/local/bin/install-plugins.sh gitlab-plugin
RUN /usr/local/bin/install-plugins.sh gitlab-hook
RUN /usr/local/bin/install-plugins.sh amazon-ecr

# jobs management
RUN /usr/local/bin/install-plugins.sh envinject
RUN /usr/local/bin/install-plugins.sh workflow-aggregator
RUN /usr/local/bin/install-plugins.sh job-dsl
RUN /usr/local/bin/install-plugins.sh startup-trigger-plugin
RUN /usr/local/bin/install-plugins.sh parameterized-trigger
RUN /usr/local/bin/install-plugins.sh throttle-concurrents

# miscelanuous
RUN /usr/local/bin/install-plugins.sh cloudbees-folder
RUN /usr/local/bin/install-plugins.sh timestamper
RUN /usr/local/bin/install-plugins.sh dashboard-view
RUN /usr/local/bin/install-plugins.sh view-job-filters
RUN /usr/local/bin/install-plugins.sh locale
RUN /usr/local/bin/install-plugins.sh extra-columns
RUN /usr/local/bin/install-plugins.sh text-file-operations
