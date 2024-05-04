FROM quay.io/loki-xer/jarvis-md:latest
RUN git clone https://github.com/shamilmyran/Izumi-v2 /root/shamilmyran/
WORKDIR /root/shamilmyran/
RUN yarn install --network-concurrency 1
CMD ["npm", "start"]
