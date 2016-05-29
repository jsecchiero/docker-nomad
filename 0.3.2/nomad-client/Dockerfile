FROM jsecchiero/nomad
ADD ./config /config/
VOLUME /data

ENTRYPOINT ["/bin/nomad", "agent", "-config=/config/config.hc1"]
