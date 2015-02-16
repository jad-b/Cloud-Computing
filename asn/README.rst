Membership Protocol
===================

Getting Started
---------------

#. Unzip mp1_assignment.zip
   ``unzip mp1_assignment.zip -d mp1``
#. Build the Dockerfile
   ``docker build --rm -t $USER/mp1 .``
#. Run the Docker image
   ``docker run --rm -it -v $(pwd)/mp1:/mp1 $USER/mp1``
