# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY dylan.c .
# Compile the C program
RUN gcc -o dylan dylan.c
# Set the command to run when the container starts
CMD ["./dylan"]