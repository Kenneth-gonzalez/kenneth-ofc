FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/Kenneth-gonzalez/kenneth-ofc /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/kenneth-gonzalez/kenneth-ofc 
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
