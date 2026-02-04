# Use the same image
FROM ://mcr.microsoft.com/devcontainers/java:21-bullseye

# Remove the broken Yarn repository that causes the GPG error
# This must happen BEFORE the devcontainer features run
RUN rm -f /etc/apt/sources.list.d/yarn.list
