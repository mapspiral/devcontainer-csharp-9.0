# Use the .NET SDK base image
FROM mcr.microsoft.com/dotnet/sdk:9.0

# Create a user (non-root) for the container
RUN useradd -ms /bin/bash developer

# Set the user for the rest of the image build
USER developer