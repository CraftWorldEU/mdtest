---
SPDX-License-Identifier: MIT
path: "/tutorials/gitlab-server-with-docker"
slug: "gitlab-server-with-docker"
date: "2019-04-01"
title: "Our own GitLab Server with docker and traefik"
short_description: "In this tutorial we will set up our own GitLab server with docker. We also provide a docker image registry and use Traefik as reverse proxy."
tags: ["Git", "GitLab", "Docker", "Image Registry", "Traefik", "Lang:YAML"]
author: "strålende IT solutions"
author_link: "https://github.com/stralende"
author_img: "https://avatars1.githubusercontent.com/u/38130280"
author_description: ""
language: "en"
available_languages: ["en"]
header_img: "header-1"
cta: "cloud"
---


## Introduction

In this tutorial, I will show you how to set up a GitLab CE server on a Hetzner Cloud server using docker and docker-compose. As reverse proxy and to provide a LetsEncrypt certificate we use Traefik. Also, we provide a docker image registry with GitLab.

**Prerequisites**
