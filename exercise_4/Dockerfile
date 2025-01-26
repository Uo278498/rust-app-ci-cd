# Use an official Rust image as the base image
FROM rust:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the project files to the container
COPY ./exercise_4/rust-app /app

# Build the Rust application
RUN cargo build --release

# Expose the default port
EXPOSE 8080

# Run the compiled binary
CMD ["./target/release/rust-app"]
