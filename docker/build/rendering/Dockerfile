# escape=`

#
# Development-only image for running Next.js in a containerized environment.
# Assumes that the Next.js rendering host source is mounted to c:\app.
#

ARG PARENT_IMAGE
FROM ${PARENT_IMAGE} as debug

WORKDIR /app

EXPOSE 3000
# RUN "npm install"
ENTRYPOINT "npm install && npm run start:connected"