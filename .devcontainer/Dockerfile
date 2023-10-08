FROM tenasi/base

RUN apt-get install -y --no-install-recommends openjdk-21-jdk git zip unzip && \
    curl -s "https://get.sdkman.io" | bash && \
    source "$HOME/.sdkman/bin/sdkman-init.sh" && \
    sdk install gradle