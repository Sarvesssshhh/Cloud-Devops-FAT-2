# Use official GCC image to compile the code
FROM gcc:latest

# Set working directory
WORKDIR /app

# Copy source code
COPY main.c .

# Compile C program
RUN gcc main.c -o app

# Command to run the compiled program
CMD ["./app"]
