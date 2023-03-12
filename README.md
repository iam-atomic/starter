docker run --platform linux/amd64 -d --rm --name=jenkins-agent1 -p 4444:22 \
-e "JENKINS_AGENT_SSH_PUBKEY=/Users/ilham-tia/.ssh/atomic/jenkins_agent_key" \
jenkins/ssh-agent:alpine