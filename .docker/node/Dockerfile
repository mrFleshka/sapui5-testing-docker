FROM node:10-alpine

# install yarn
RUN npm install --global yarn @ui5/cli node-env-run
ENV PATH "/var/www/app/node_modules/.bin:$PATH"

COPY ./.docker/node/entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

WORKDIR /var/www/app

USER node

ENTRYPOINT ["/entrypoint.sh"]
CMD ["node", "index.js"]