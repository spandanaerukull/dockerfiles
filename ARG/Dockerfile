ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120hrs" 
ARG trainer="pragney"
ENV trainer=$trainer
RUN echo " Hi, course is: ${course}, duration is: ${duration}, trainer is: ${trainer}"
CMD ["sleep", "5000"]

    
