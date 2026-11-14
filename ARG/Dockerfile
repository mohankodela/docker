ARG version
FROM almalinux:${version:-9}
ENV NAME="mohan" \
    AGE="35"
ARG COMPANY="ACC"
ENV COMPANY=$COMPANY
RUN echo "${NAME} ${AGE} ${COMPANY}"
CMD ["sleep", "1000"]