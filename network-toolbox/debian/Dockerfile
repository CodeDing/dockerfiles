FROM debian:stretch-slim

RUN apt-get update && apt-get install -y --no-install-recommends \
		bash-completion \
		ca-certificates \
		curl \
		dnsutils \
		gnupg dirmngr \
		inetutils-ping \
		ipcalc \
		iperf \
		iproute2 \
		iptables \
		mtr-tiny \
		nbtscan \
		net-tools \
		netcat-openbsd \
		nmap \
		openssh-client \
		procps \
		rsync \
		socat \
		traceroute \
		tshark \
		wget \
	&& rm -rf /var/lib/apt/lists/*

CMD ["bash", "--login", "-i"]
