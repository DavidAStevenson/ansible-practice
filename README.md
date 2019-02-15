# ansible-practice

This is a fork of a repo from a 2016 book.

So, the repo needed some fixes to work. Fixes identified are in this repo.

Oustanding issues that I have not fixed:
- web1 and web2 are not running logstash
  - there must be something wrong with the ansible playbook with respect to starting logstash, but it can be manually resolved as per the troubleshooting guide here at DO:
    https://www.digitalocean.com/community/tutorials/how-to-troubleshoot-common-elk-stack-issues#logstash-how-to-check-if-it-is-running

e.g. manually check the status, and if not running, start it
```
sudo service logstash status
sudo service logstash start
...
sudo service logstash status
```
