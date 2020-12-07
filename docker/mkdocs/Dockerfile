# Copyright (c) 2020 ToIP Foundation

# Pull base image from official Material for MkDocs repo
FROM squidfunk/mkdocs-material

# Add bash as alternative to default ash shell env in Alpine
<<<<<<< HEAD
RUN apk add --no-cache --upgrade bash
=======
RUN apk add --no-cache --upgrade bash python py-pip
>>>>>>> template/main

# Add make command utility
RUN apk add --update --no-cache make=4.2.1-r2

<<<<<<< HEAD
=======
# Add MkDocs dependencies
RUN pip install --upgrade pip
RUN pip install --upgrade mkdocs-enumerate-headings-plugin

>>>>>>> template/main
# Set working directory to the name of a Docker Volume
WORKDIR /host_mkdocs
