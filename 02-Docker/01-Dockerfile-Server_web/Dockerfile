from python

run apt-get update && apt-get install -y unzip
run wget https://gist.github.com/ttwthomas/bcfc524e0328343c6e70d0ac93f4ef3e/archive/a7b8c232554c58dddb06dd7a06025a45f92b0e66.zip -O fichier.zip
run unzip fichier.zip -d /tmp

workdir /tmp/bcfc524e0328343c6e70d0ac93f4ef3e-a7b8c232554c58dddb06dd7a06025a45f92b0e66
expose 7777

entrypoint ["python", "-m", "http.server", "7777"]
