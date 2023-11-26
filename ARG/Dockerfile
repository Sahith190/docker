ARG version
FROM almalinux:${version:-8}
# ARG version before FROM will not work after FROM
RUN echo "version passed by user is: ${version}"
ARG COURSE
ARG TRAINER
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
RUN echo "Course is: ${COURSE}, Trainer is: ${TRAINER}"