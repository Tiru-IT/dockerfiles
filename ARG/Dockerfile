ARG VERSION 
FROM almalinux:${VERSION:-9}
# we cont access after FROM  ARg not access 
ARG COURSE="DOCKER" \
    TRAINER="NANIMALLI"
# access the in side container 
ENV COURSE=${Courser}
RUN echo "Trainer:${TRAINER}, Courser: ${COURSE}, Version: ${VERSION}"
CMD ["sleep", "1000"]