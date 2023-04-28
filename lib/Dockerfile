FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Sl-Yasia/x-asena-1 /root/X-Asena
WORKDIR /root/X-Asena
RUN yarn install --network-concurrency 1
CMD ["node", "bot.js"] 
