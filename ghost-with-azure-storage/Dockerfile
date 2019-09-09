FROM ghost:latest
WORKDIR /var/lib/ghost
COPY package.json /var/lib/ghost
RUN npm install
ADD ghost-azure-storage /var/lib/ghost/content/adapters/storage/ghost-azure-storage
# WORKDIR /var/lib/ghost/content/adapters/storage/ghost-azure-storage
# RUN npm install