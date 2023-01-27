# maigret
Package installing

NOTE: Python 3.7 or higher and pip is required, Python 3.8 is recommended.

# install from pypi
pip3 install maigret

# or clone and install manually
git clone https://github.com/soxoj/maigret && cd maigret
pip3 install .

# usage
maigret username

Cloning a repository

git clone https://github.com/soxoj/maigret && cd maigret
pip3 install -r requirements.txt

# usage
./maigret.py username

Docker

# official image
docker pull soxoj/maigret

# usage
docker run soxoj/maigret:latest username

# manual build
docker build -t maigret .

Usage examples

# make HTML and PDF reports
maigret user --html --pdf

# search on sites marked with tags photo & dating
maigret user --tags photo,dating

# search for three usernames on all available sites
maigret user1 user2 user3 -a

Use maigret --help to get full options description. Also options are documented.
