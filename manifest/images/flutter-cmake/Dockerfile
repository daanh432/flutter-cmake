ARG VERSION

FROM cirrusci/flutter:${VERSION}
RUN apt-get update -y && apt-get install -y \
    clang \
    cmake \
    ninja-build \
    pkg-config \
    libgtk-3-dev \
    liblzma-dev \
    appindicator3-0.1 \
    libappindicator3-dev \
    libnotify-dev \
    && rm -rf /var/lib/apt/lists/*
