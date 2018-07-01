# Based on the alpine Linux: https://alpinelinux.org/
FROM alpine:3.7

# Copies the entrypoint script to the container /
COPY entrypoint.sh /

# Makes the entrypoint.sh script the entrypoint for this container
ENTRYPOINT ["/bin/sh", "entrypoint.sh"]
