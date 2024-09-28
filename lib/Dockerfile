FROM quay.io/papaigwe/Feith-md V1
RUN git clone https://github.com/papaigwe/Feith-md V1 /root/papaigwe
WORKDIR /root/papaigwe/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
