FROM fusuf/whatsasena:latest

RUN git clone https://github.com/ADHIPAN-MODS/pablo /root/WhatsAsenaPublic
WORKDIR /root/WhatsAsenaPublic/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
