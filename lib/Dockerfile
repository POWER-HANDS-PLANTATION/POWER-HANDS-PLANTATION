FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/POWER-HANDS-PLANTATION/POWER-HANDS-PLANTATION /root/power-hands-plantation
WORKDIR /root/power-hands-plantation/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
