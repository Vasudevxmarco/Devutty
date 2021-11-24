FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Vasudevxmarco/Devutty /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN git clone https://github.com/Ajmal-Achu/Nandhuttynew
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit


CMD ["node", "bot.js"]
