ARG version
FROM almalinux:${version:-9}
ENV COURSE="Devops" \
    duration="120hours"
ARG trainer="sivakumar"
ARG trainee="nithin"
ENV trainer=$trainer
RUN echo "hi, iam learning course:${COURSE} of ${duration} from ${trainer} and also the version is : ${version} and also trainee: ${trainee}" 
CMD ["sleep", "1000"]