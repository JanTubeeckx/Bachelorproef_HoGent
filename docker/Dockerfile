FROM debian:bullseye

RUN brew install -y \
    texlive-latex-base \
    texlive-latex-extra \
    texlive-lang-european \
    texlive-bibtex-extra \
    biber \
    git \
    texlive-xetex \
    python3-pip \
    latexmk \
    install pygments \
    rm -rf /var/lib/apt/lists/*
RUN fc-cache -f -v
