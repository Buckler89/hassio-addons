ARG BUILD_FROM="homeassistant/armhf-base-python:3.7"
FROM $BUILD_FROM

# Copy data
COPY tensorflow-1.11.0-cp35-none-linux_armv7l.whl /
COPY run.sh /
RUN chmod a+x /run.sh

WORKDIR /data
CMD ["/run.sh"]
