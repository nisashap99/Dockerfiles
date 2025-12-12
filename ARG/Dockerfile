FROM almalinux:9
ENV course="DevOps with AWS" \
    trainer="Shaik Nisar" \
    duration="120HRS"
# RUN echo "Hello ${trainer}" > /tmp/devops.txt
# CMD ["sleep", "100"]    
#here user1 is key, someuser is default value
ARG USERNAME=Sivakumar
ENV USERNAME=$USERNAME
RUN echo "Hello User: ${USERNAME}" > /tmp/devops.txt
CMD ["sleep", "100"]