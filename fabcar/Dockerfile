FROM node:14-alpine
WORKDIR /go/src/github.com/hyperledger/chaincode/
COPY . .
RUN npm install  && printf "ls\nnpm run start\n" > entrypoint.sh
EXPOSE 9999
CMD ["/bin/sh","entrypoint.sh"]