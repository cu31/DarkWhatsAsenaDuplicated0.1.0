FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cu31/DarkWhatsAsenaDuplicated0.1.0 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
