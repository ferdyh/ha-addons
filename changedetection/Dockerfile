FROM ghcr.io/dgtlmoon/changedetection.io

LABEL \
  io.hass.version="1" \
  io.hass.type="addon" \
  io.hass.arch="amd64"

WORKDIR /app

CMD [ "python", "./changedetection.py" , "-d", "/datastore"]