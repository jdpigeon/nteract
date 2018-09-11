FROM node:8@sha256:1d33c01da62a9b998147bc2d19411cd690171d599acbdb0beca5ebc462d45915
ADD . /playground
WORKDIR /playground
RUN npm install && npm run build

EXPOSE 3000

CMD ["/playground/node_modules/.bin/next", "start", "--host", "0.0.0.0"]
