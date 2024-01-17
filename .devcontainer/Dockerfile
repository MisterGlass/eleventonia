FROM mcr.microsoft.com/devcontainers/typescript-node:1-20-bullseye
WORKDIR /code
COPY ../package.json /code/
COPY ../package-lock.json /code/
RUN npm ci

CMD [ls]
