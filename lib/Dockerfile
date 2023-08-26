FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/Theekshanamax/Red-Lion/root/Theekshanamax 
WORKDIR /root/Theekshanamax/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
