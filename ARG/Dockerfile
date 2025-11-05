ARG version
FROM almalinux:${version:-9}
ENV NAME="hrushikesh" \
    COMP="HME_SOLUTIONS"
ARG ROLE="DevOps"
ENV ROLE = ${ROLE}
RUN echo "name: ${NAME}, company: ${COMP}, designation: ${ROLE}, version: ${version}"
CMD ["sleep", "1000"]