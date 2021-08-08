FROM fusuf/whatsasena:latest

RUN https://github.com/nandhuz47/wizard/nandhuz47/wizard/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
