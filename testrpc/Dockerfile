FROM mhart/alpine-node:latest

RUN apk add --no-cache make gcc g++ python git bash
RUN npm install -g ethereumjs-testrpc

EXPOSE 8545

ENTRYPOINT ["testrpc", "--account", "0xdb3083055c72ea2528902aae0ff8f9ee488ad9bf009d359da0db2824c9c45fe8,2000000000000000000000", "--account", "0x9ac1f2f2cbb0d43909f1fa69554994fc63a1e5ff0e028f806fe035ac7cb78590,1000000000000000000000", "--account", "0x864c51dd13443614d0ff6949a3bab604d2664370dfc3ddb0f35b30e324872f51,3000000000000000000000", "--account", "0x6eaf6c1191b090631668ad8db7dd7f8b5d703f8f5e7315a06f775d030c33829b,5000000000000000000000"]
