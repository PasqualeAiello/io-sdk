FROM pagopa/theia:2020.06.08
ADD ide-plugin /home/theia/plugins/ide-plugin
RUN sudo find /home/theia -uid 0 -exec chown theia:theia {} \;
#RUN cd /home/theia/plugins/ide-plugin && npm install && npm run build
