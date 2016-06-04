FROM jsecchiero/nomad
COPY config /

VOLUME /data
ENTRYPOINT ["/bin/nomad", "agent", "-config=/config/config.hc1"]
