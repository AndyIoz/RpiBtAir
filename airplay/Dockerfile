FROM balenalib/rpi-raspbian

ENV DBUS_SYSTEM_BUS_ADDRESS=unix:path=/host/run/dbus/system_bus_socket
RUN install_packages shairport-sync

COPY start.sh /usr/src/

CMD [ "/bin/bash", "/usr/src/start.sh" ]
