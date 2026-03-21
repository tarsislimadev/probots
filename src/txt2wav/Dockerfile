FROM ubuntu

RUN apt update -y && apt install -y espeak-ng

ENV input=file.txt

ENV output=file.wav

CMD espeak-ng -f "${input}" -w "${output}"
