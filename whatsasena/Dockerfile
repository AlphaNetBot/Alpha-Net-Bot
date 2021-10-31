FROM fusuf/whatsasena:latest

RUN git clone https://github.com/AlphaNetBot/Alpha-Net-Bot /root/Alpha-Net-Bot
WORKDIR /root/Alpha-Net-Bot/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
