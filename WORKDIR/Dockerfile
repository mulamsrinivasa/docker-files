FROM almalinux:9
RUN mkdir /tmp/workdir-test
# Generally we use cd to switch to any directory, here we use WORKDIR instruction to switch to desired directory
WORKDIR /tmp/workdir-test
RUN pwd
RUN echo "This is a sample file in workdir-test directory" > sample.txt
CMD ["sleep", "300"]