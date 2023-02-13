FROM alpine:3.15.4

RUN apk update && apk add bash && apk add curl && apk add nano && apk add openssl && apk add git && apk add gnupg

# Install Terraform
RUN wget https://releases.hashicorp.com/terraform/1.3.8/terraform_1.3.8_linux_amd64.zip
RUN unzip terraform_1.3.8_linux_amd64.zip
RUN mv terraform /usr/bin/terraform

CMD tail -f /dev/null
