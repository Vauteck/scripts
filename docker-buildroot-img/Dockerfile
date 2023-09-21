FROM ubuntu:22.04

RUN apt-get update 
RUN apt-get install -y sed make binutils build-essential diffutils gcc g++ bash patch gzip bzip2 perl tar cpio unzip rsync file bc findutils wget
RUN apt-get install -y lib32ncurses-dev libncurses-dev libncurses5-dev libncurses5
RUN apt-get install -y python3

# ** +asciidoc+, version 8.6.3 or higher
# ** +w3m+
# ** +python+ with the +argparse+ module (automatically present in 2.7+ and 3.2+)
# ** +dblatex+ (required for the pdf manual only)
# 
# * Graph generation tools:
# ** +graphviz+ to use 'graph-depends' and '<pkg>-graph-depends'
# ** +python-matplotlib+ to use 'graph-build'
