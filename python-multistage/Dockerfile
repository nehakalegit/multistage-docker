#Build stage

FROM python:latest
WORKDIR /app
COPY helloworld.py .
RUN echo "Build stage complete"


#Run stage 
CMD ["python","helloworld.py"]
RUN echo "Run stage complete"
