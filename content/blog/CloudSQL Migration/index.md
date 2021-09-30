---
title: "MySQL to Cloud SQL Migration"
publishdate: 2021-08-04
date: 2021-08-04
draft: true
lastmod: 2021-08-04
hideLastModified: true
summary: "Migrate a MySQL database to Cloud SQL using one of three migration processes."
# summaryImage: "blog_post_default_image.jpg"
---

# Introduction
This blog post explains how to migrate a MySQL database to Cloud SQL using three different methods.

# MySQL on GCE
Firstly, we need to create a MySQL database which we can then migrate to Cloud SQL. To do that, we will install MySQL on a GCE instance from scratch to simulate a typical MySQL database.

Follow [this doc](https://cloud.google.com/architecture/setup-mysql) to create a Compute Engine instance (I used Ubuntu as my OS), install MySQL on it and connect to MySQL.
You can replace this manual step by using [Google Cloud Marketplace](https://cloud.google.com/marketplace/?q=mysql) for a simple click-to-deploy solution.

Now that MySQL has been set up, we need to create a simple database with a few tables before moving on to the migration processes.

# Migration Methods
1. [Export/import migration](#export-import-migration)
2. [External replica promotion migration](#external-replica-promotion-migration)
3. [Migration using Database Migration Service](#migration-using-database-migration-service)

# Export/import migration

# External replica promotion migration

# Migration using Database Migration Service