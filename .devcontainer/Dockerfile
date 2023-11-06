FROM tenasi/base

RUN apt-get install -y --no-install-recommends openjdk-21-jdk git zip unzip && \
    curl -s "https://get.sdkman.io" | bash && \
    echo "sdkman_auto_answer=true" > $SDKMAN_DIR/etc/config && \
    echo "sdkman_auto_selfupdate=false" >> $SDKMAN_DIR/etc/config
RUN bash -c "source $HOME/.sdkman/bin/sdkman-init.sh && sdk install gradle"
