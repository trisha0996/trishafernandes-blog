---
title: "Setting up a Website and an Organisation"
publishdate: 2021-04-30
date: 2021-04-30
draft: false
lastmod: 2021-03-05
hideLastModified: true
summary: "High level overview on how to set up your own organisation and website based on the products and technologies used to create this website"
summaryImage: "resource-hierarchy.png"
---

#### Introduction
This is a step-by-step guide on how to set up an organization & create a static website. More specifically, this demonstrates how I set up my organisation, created my website and the tools used to do so. 
The topics covered are as follows:

1. [Buy a domain name](##1.-Buy-a-domain-name)
2. [Resolve DNS](#resolve-dns)
3. [Set up identity management](#set-up-identity-management)
3. [Create an organisation](#create-an-organisation)
    - [Set up administrator access](#set-up-administrator-access)
    - [Set up billing](#set-up-billing)
    - [Set up resrouce hierarchy](#set-up-resource-hierarchy)
    - [Set up IAM](#set-up-iam)
4. [Host website](#hosts-website)
5. [Apply CI/CD](#apply-ci-cd)


##### 1. Buy a domain name

The first step to do is to register a domain name with a registrar. I bought my domain name on [namecheap](https://www.namecheap.com/). There are many popular domain registrars you can choose from depending on the pricing structures, bundles and web hosting options and other add-on services. Some examples are [GoDaddy](https://uk.godaddy.com/domains/domain-name-search), [Domain.com](https://www.domain.com/domains) and [Google Domains](https://domains.google/).

Some of the reasons to go with [namecheap](https://www.namecheap.com/) are its ease of use, free Whois privacy and as the name suggests, it's relatively cheap.

##### 2. Resolve DNS

Namecheap offers a default DNS service, as is with most domain name registrars. But, these are very basic free DNS services and they usually lack advanced DNS capabilities; this is where [Cloudflare DNS](https://www.cloudflare.com/dns/) comes in. Having the fastest authoritative DNS in the world, built-in DDoS protection and its 100% uptime are just a few of the reasons to choose Cloudflare DNS.

Some alternatives to Cloudflare DNS are [Google Cloud DNS](https://cloud.google.com/dns), [Amazon Route 53](https://aws.amazon.com/route53/), [OpenDNS](https://www.opendns.com/) etc.

You can use [this guide](https://www.namecheap.com/support/knowledgebase/article.aspx/9607/2210/how-to-set-up-dns-records-for-your-domain-in-cloudflare-account/) to transfer your domain from NameCheap to Cloudflare.

##### 3. Set up identity management

Identity management has to be set up to enable organisations to use single sign-on (SSO using SAML or OIDC), authentication and access controls. My "Identity as a service (IDaaS)" provider of choice for my organisation was Cloud Identity (free edition). You could, however, also use Cloud Identity Premium Edition or Google Workspace.  

Other identity management offerings outside of Google Cloud are:
- Okta
- OneLogin
- Auth0
- Microsoft Azure Active Directory,
but these pose other requirements. 




More blog posts to follow. If you liked this post, please feel free to share using the buttons on the right. I'm always looking to improve my skillset so if you have any tips/suggestions, please feel free to reach out to me.