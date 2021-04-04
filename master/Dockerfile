FROM node:lts-alpine
ARG REPO=gitee
ARG REPO_URL=$REPO.com
ARG JD_SHELL=jd_shell
ARG JD_SHELL_BRANCH=master
ARG JD_SHELL_HOST=jd_shell_$REPO
ARG JD_SHELL_KEY="-----BEGIN OPENSSH PRIVATE KEY-----\nb3BlbnNzaC1rZXktdjEAAAAABG5vbmUAAAAEbm9uZQAAAAAAAAABAAACFwAAAAdzc2gtcn\nNhAAAAAwEAAQAAAgEArq9QxXshg6YFGWGcHrmJUMbhNBOM6i/pOJdbkkd9ElHgaa9QznLa\ngd18ecgSsSji81bm8qeDR5CfnczsYh9zXcmmJreWEQLnlVLMNfZ+bLsG+vMFcJ9sG5G+n3\ngAhHNCWUE/7qSajLSpVybgcvK3M+XvK6yr3FB8VF6SicRTd3luW16AlVXPImmqXQjq+zRf\nn2RqOA+OnZgWR9zZRT8KL/DnQanJONKW8PBoHZZeV7PGs5nrxXZ3gcQfPTDSPOcg7Tt7Fk\nusNSW330O/2Rs/9xKOmXFPYqVrljjiYrTbg/Tzfu80M0OiNXCA9JZuSwvuKxOjWQ79e5pP\nH7XQNr3qr7py0v5H7FRojbm175SPHODnyPv68EZ5BZ6pEzcLCK9PIYjZRfbsYzs/IiHnR0\nvENCsKjBecowKmNuP6K0P0tQzqv6B90XsQNaMUWgfvbo9mrW6iDaW/YIDONqD1/Og7uTzk\nNav75NY30Qr+sKxJbXKzAlmx/T5/PnKa+DL+ajfaVrNE/gh+B32hQy+fF8sFBFAZUnpKXZ\nYqxA2y5QbQ4AvwnQ+aXVojfuhrspuzYcEGd52dnyqWAeSiXui892jwILJJcyTvcAvdu2Ct\nqNBZm+mcktmBROH6+tV2yGe+MSEpe5SWqlG9brf/Ln8slkgLJ5Dye98xZ/G2n2f2AlvV2f\nsAAAdAsoPOKLKDzigAAAAHc3NoLXJzYQAAAgEArq9QxXshg6YFGWGcHrmJUMbhNBOM6i/p\nOJdbkkd9ElHgaa9QznLagd18ecgSsSji81bm8qeDR5CfnczsYh9zXcmmJreWEQLnlVLMNf\nZ+bLsG+vMFcJ9sG5G+n3gAhHNCWUE/7qSajLSpVybgcvK3M+XvK6yr3FB8VF6SicRTd3lu\nW16AlVXPImmqXQjq+zRfn2RqOA+OnZgWR9zZRT8KL/DnQanJONKW8PBoHZZeV7PGs5nrxX\nZ3gcQfPTDSPOcg7Tt7FkusNSW330O/2Rs/9xKOmXFPYqVrljjiYrTbg/Tzfu80M0OiNXCA\n9JZuSwvuKxOjWQ79e5pPH7XQNr3qr7py0v5H7FRojbm175SPHODnyPv68EZ5BZ6pEzcLCK\n9PIYjZRfbsYzs/IiHnR0vENCsKjBecowKmNuP6K0P0tQzqv6B90XsQNaMUWgfvbo9mrW6i\nDaW/YIDONqD1/Og7uTzkNav75NY30Qr+sKxJbXKzAlmx/T5/PnKa+DL+ajfaVrNE/gh+B3\n2hQy+fF8sFBFAZUnpKXZYqxA2y5QbQ4AvwnQ+aXVojfuhrspuzYcEGd52dnyqWAeSiXui8\n92jwILJJcyTvcAvdu2CtqNBZm+mcktmBROH6+tV2yGe+MSEpe5SWqlG9brf/Ln8slkgLJ5\nDye98xZ/G2n2f2AlvV2fsAAAADAQABAAACADodUybP5v9wPSQLiC/kk91OvN9hXbEPjWxp\nVmqc4+wzVxBx5dU4+p7Xu7CcMjPEIXTJRX4W4qLtZ1zNLxsZ0XyzOFaLHx67s6XG7O9K+R\nZdRl44eWfVcdbeLufIuYtW+QzOm2FeW5hSBkBbS7KSMwbOCTqjcG2UTTiYWfIBYa9Os7sr\n/mUwLgAJ3UakT+CQtPtHIdtSuaSOU2NHAvV5mn8GizkaLjp8PQEdSdYGD47n3UQlAf4ogm\numfqoR0u+2CQtDjZiGRl1MFhbt6CZnXWlqQAymWL29wMQyWoZyGtGUrWleVSR07MMQkaZN\nYZYP+wVTvDVFumjjlk07ZHDB0BBnpC/CPeQoF7FfrTdmAhX5l1zj5pO6c/RnpC2U6mfU+/\nMQJVGyAMR5Jh+/EuoQCzp2iTrIUV8hToklfPQehe2AyCwEnifMY+KSimLjveqPU8IZuka7\nTbVy6M5LJ3wrlG8lWOtHNOwP7LebHJ/IxG03iLLb+FypNKyidcohrOTmP9Dqks5/MWjhyr\nhjfyxGqhE8D7Lt+AJ67/SiuA1GH0MFIVPii/GRAi7i6af9+1ETycvaUd8IhiEpwlobW0HO\nNLr26Oj2twbdcubqC2OdfFg+IN7yqbq3iuf13IBKCfH0WdgNe07ciB+AndP3Fmy7qLMqJ/\nQw870HECW3w/rW6Tj5AAABAQDKXswpbm9bqWazqfXJqCwaVXx/GYJ8Celtvc3k7zkqwZEt\nLbqYDnSACJ9qDGCzCBlTznlvXfteqW+l2gBcLFr3D+77/GBsaObh6GzHZxnd+3Gs/q6sz4\n92TeZ165kmkhh3eyVR0EkXFUjBaGKyJmDBurApdWcuE0SFvSxSjEGi9W3eggFzuarm8oSR\nN4vh4ciayRPLm0K3I4pS3xI/xVqHmyXrDw7iXT0mEV82Z3yqmZk4qXijnvpckQ29duf9ck\ndQEGbya699SSUNwjJM2DYHA/mCrifRwdFYP4Q4TfH9YahrXrqVcM3stjj14CPrpMqb7L+A\nJAzWnVnl7wz/GBpEAAABAQDWOIDMWsfMpdrof7LiR/N3zmGSXdLa7PibbycWYtb5opfIsd\nKMslv8yVB4Aw/FMxIGc8cUvLJlvgcUB/2qb3fqPDpvnQ80kdIhqz5LguCF5FoZEejWltIc\nkbFXFYK6R9SvSyV6M8vo/tSpie7jszfvt6gGOFqpZABH7GTIPGVlZtv573Y2tMj2xGIIjv\nf4ZF6mAYcTnxlknvrjFe11+GQ4t2b+DAxwfDAPnEs0RfjPRiGUG4nTPLyu7hlS47TMfhMO\nvn7X931/5TQMixdgl426aHLRmQOcF4KJ3EdqbpKxbcHCS2CCu45619W+IoUomKLUgqUYo7\nnIqf3oO7jm2G4dAAABAQDQwOLAWtnCt2XP5tESNk0YxYpdKYkx7Go+sKxevwjMNV9953Ai\noh90uPJHemmgjCYmSIg+FdoDqSowFZJWEKI1se17PyHYRKf6GhtAzM7h8r7SbfV473XPL9\nBgPz03g9LHb4+6rGhiGaE7wFyaN5KcSSi+30AZi/CNxnZ+A36UbI/Lnm7GXNuIJbW94EHB\n81f+LLTNdHClwiFoXYofB2muC7l1HTh3q4M/hLqkzu8mA6SBFjvHO0lGDdZrkzJd/3dIB+\n6uTkOgxItzVyOJnQCeDcbHBwlnWzQvgy74AEgZA08fYnNFDnxkZtOAL7lXphna2JGwj/tc\n8dne9G99L0z3AAAACHJvb3RAbmFzAQI=\n-----END OPENSSH PRIVATE KEY-----"
ARG JD_SCRIPTS=jd_scripts
ARG JD_SCRIPTS_BRANCH=master
ARG JD_SCRIPTS_HOST=jd_scripts_$REPO
ARG JD_SCRIPTS_KEY="-----BEGIN OPENSSH PRIVATE KEY-----\n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\n-----END OPENSSH PRIVATE KEY-----"
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
    LANG=zh_CN.UTF-8 \
    SHELL=/bin/bash \
    PS1='\u@\h:\w $ ' \
    JD_DIR=/jd \
    ENABLE_HANGUP=false \
    ENABLE_RESET_REPO_URL=true \
    JD_SHELL_URL=git@$JD_SHELL_HOST:evine/$JD_SHELL.git \
    JD_SCRIPTS_URL=git@$JD_SCRIPTS_HOST:lxk0301/$JD_SCRIPTS.git
WORKDIR $JD_DIR
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update -f \
    && apk upgrade \
    && apk --no-cache add -f bash \
                             coreutils \
                             git \
                             wget \
                             curl \
                             nano \
                             tzdata \
                             perl \
                             openssh-client \
                             python \
                             python3 \
    && rm -rf /var/cache/apk/* \
    && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone \
    && mkdir -p /root/.ssh \
    && echo -e $JD_SHELL_KEY > /root/.ssh/$JD_SHELL \
    && echo -e $JD_SCRIPTS_KEY > /root/.ssh/$JD_SCRIPTS \
    && chmod 600 /root/.ssh/$JD_SHELL /root/.ssh/$JD_SCRIPTS \
    && echo -e "Host $JD_SHELL_HOST\n\tHostname $REPO_URL\n\tIdentityFile=/root/.ssh/$JD_SHELL\n\nHost $JD_SCRIPTS_HOST\n\tHostname $REPO_URL\n\tIdentityFile=/root/.ssh/$JD_SCRIPTS" > /root/.ssh/config \
    && echo -e "\n\nHost *\n  StrictHostKeyChecking no\n" >> /etc/ssh/ssh_config \
    && chmod 644 /root/.ssh/config \
    && ssh-keyscan $REPO_URL > /root/.ssh/known_hosts \
    && git clone -b $JD_SHELL_BRANCH $JD_SHELL_URL $JD_DIR \
    && git clone -b $JD_SCRIPTS_BRANCH $JD_SCRIPTS_URL $JD_DIR/scripts \
    && cd $JD_DIR/scripts \
    && npm install \
    && npm install -g pm2 \
    && ln -sf $JD_DIR/jtask.sh /usr/local/bin/jd \
    && ln -sf $JD_DIR/jtask.sh /usr/local/bin/jtask \
    && ln -sf $JD_DIR/jtask.sh /usr/local/bin/otask \
    && ln -sf $JD_DIR/jtask.sh /usr/local/bin/mtask \
    && ln -sf $JD_DIR/jup.sh /usr/local/bin/git_pull \
    && ln -sf $JD_DIR/jup.sh /usr/local/bin/jup \
    && ln -sf $JD_DIR/jlog.sh /usr/local/bin/rm_log \
    && ln -sf $JD_DIR/jlog.sh /usr/local/bin/jlog \
    && ln -sf $JD_DIR/jcode.sh /usr/local/bin/export_sharecodes \
    && ln -sf $JD_DIR/jcode.sh /usr/local/bin/jcode \
    && ln -sf $JD_DIR/jcsv.sh /usr/local/bin/jcsv \
    && cp -f $JD_DIR/docker/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 $JD_DIR/*.sh \
    && rm -rf /root/.npm
ENTRYPOINT ["docker-entrypoint.sh"]
