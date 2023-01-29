FROM blang/latex:ubuntu
COPY pandoc-3.0.1-1-amd64.deb /etc
RUN apt-get update && \
    dpkg -i /etc/pandoc-3.0.1-1-amd64.deb && \
    apt-get install -f && \
    apt-get -y install pandoc-citeproc && \
    apt-get -y install texlive-xetex && \
    apt-get -y install lmodern && \
    apt-get -y install fonts-liberation
    
#    apt-get -y install texlive-lang-german && \
#    apt-get -y install texlive-latex-extra 