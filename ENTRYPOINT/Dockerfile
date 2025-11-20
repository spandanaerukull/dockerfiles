FROM almalinux:9
# CMD ["ping", "google.com"] we can over ride this CMD
ENTRYPOINT ["ping" , "google.com"] 

# NOW THE COMBINATION OF ENTRYPOINT AND CMD
FROM almalinux:9
# CMD ["google.com"]
CMD ["google.com"] 
ENTRYPOINT ["ping"]

# here cmd is option and entrypoint is command, so bysusing th option of both we can pass arguments to command we can chang the option while running container without changing the command

# ENTRYPOINT is used to set default application to be run when container starts
# here we are telling to run ping command when container starts