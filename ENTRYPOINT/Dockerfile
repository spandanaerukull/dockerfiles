FROM almalinux:9
# CMD ["ping", "google.com"] we can over ride this CMD
ENTRYPOINT ["ping" , "google.com"] 

# NOW THE COMBINATION OF ENTRYPOINT AND CMD
FROM almalinux:9
# CMD ["google.com"]
CMD ["google.com"]
ENTRYPOINT ["ping"]

# ENTRYPOINT is used to set default application to be run when container starts
# here we are telling to run ping command when container starts