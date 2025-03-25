FROM jeandeaual/lilypond:stable

WORKDIR /workspace

COPY . .

USER root

RUN apt-get update && apt-get install -y --no-install-recommends python3 python3-pip \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/*

RUN pip install -r requirements.txt

USER lilypond

CMD tail -f /dev/null
