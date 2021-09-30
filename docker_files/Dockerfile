############################################################
# Dockerfile to build LPPic
# Based on Fedora base image
############################################################

# Set the base image from jeandet
FROM  jupyter/scipy-notebook
LABEL maintainer "Antoine Tavant <antoine.tavant@lpp.polytechnique.fr>"

# Update the repository sources list

RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir pandas astropy TPM2PPF_learntools matplotlib numpy tqdm seaborn

RUN git clone https://github.com/antoinetavant/TP_M2.git && cd TP_M2 && rm -rf .git