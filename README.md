# mastodon-terraform

Set up a brand new Mastodon instance using Terraform and Ansible. A work in progress.

## Who is this for

The person who wants to run a Mastodon instance on their own server, and
who needs to install a bunch of code and configs quickly to get going.

The person testing Mastodon who wants to check that the latest and greatest
passes some set of tests.

The devops person who needs to have a place to practice, and what better
place to practice than a federated system which can generate a firehose of
replicated traffic?

The ARM developer who wants to port a bunch of code that currently works on
Intel so that it [works on ARM](http://worksonarm.com), and who uses devops
tools to make that process go faster.

## What are these things?

[Mastodon](http://mastodon.social) is a self-hosted version of GNU social with a user interface 
reminiscent of Tweetdeck. It has a federated structure, and individuals
can either get an account on someone else's system or run their own.

[Terraform](https://github.com/hashicorp/terraform) (from Hashicorp) is software for provisioning new bare-metal
hardware or virtual machines from a variety of providers (including [Packet](http://packet.net) ).
It speeds the path for going from nothing to something. Your infrastructure
is created from a script.

[Ansible](https://github.com/ansible/ansible) (from Red Hat) automates
the process of taking a machine and making it be some specific configuration.
[ceejbot](https://github.com/ceejbot) has a working [mastodon-ansible](https://github.com/ceejbot/mastodon-ansible)
configuration that reduces setup complexity considerably, though there are
still more than a dozen steps.

## Where is this being discussed?

Mastodon has a hashtag #terraform that's as good as any; also issues here
on Github are always useful.

The hashtag #AdminNeedHelp or just #NeedHelp looks useful too.

The hashtag #devops is good on lots of systems, not just Mastodon.

## Why on earth are you doing this?

I used to run a Usenet feed, need I say more?

## When will this be done?

Hopefully sometime reasonably soon, but no guarantees and no promises.

## Acknowledgements

* [@vielmetti@mastodon.social](https://mastodon.social/@vielmetti) - for most of the text you see here
* [@ceejbot@rafting.io](https://rafting.io/@ceejbot) - for an Ansible playbook
* [@rayalez@hackertribe.io](https://hackertribe.io/@rayalez) - for a [guide](http://digitalmind.io/post/deploying-mastodon-on-digital-ocean) to deploying on Digital Ocean
