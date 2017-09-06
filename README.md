# mydnshost-docker-cron
Docker Cron Container

This container is used to run cron jobs.

It is expected that crontabs are mounted into /etc/cron.d/ as volumes.

If /scripts/init.sh exists, it will be run before cron is started.

Based on https://github.com/renskiy/cron-docker-image with additional packages as required for mydnshost.
