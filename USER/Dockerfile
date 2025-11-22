FROM almalinux:9
RUN dnf install nginx -y 
RUN useradd Nanimalli

# if we need to sudo execes to give here,complete the sudo use the <<< USER >>> the container is notb sudo its nanimalli user
USER Nanimalli 

CMD ["sleep", "100"]