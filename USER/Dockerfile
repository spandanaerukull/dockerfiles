FROM almalinux:9
RUN dnf install git -y 
RUN useradd spandana
USER spandana
CMD ["google.com"]
ENTRYPOINT ["ping"]

#RUN useradd spandana --> creates a user named spandana in our container
# USER spandana --> switches the user from root to spandana
# Now all the commands will be executed by spandana user not by root user
# CMD and ENTRYPOINT remains same as previous explanation
# here we are creating the normal user and switching to that user to run the commands instead of root user for security reasons