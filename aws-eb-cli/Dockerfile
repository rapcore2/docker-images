FROM python:3.7.3-alpine
RUN addgroup -S awsebcli && adduser -D -G awsebcli awsebcli
RUN pip install awsebcli==3.15.2
USER awsebcli
