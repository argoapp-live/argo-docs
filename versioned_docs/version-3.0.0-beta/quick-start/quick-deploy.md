---
id: quick-deploy
title: Create a Deployment
sidebar_label: Create a Deployment
slug: /quick-start/quick-deploy
---

Spheron Protocol deploys each new website atomically, ensuring that there are no anomalies while submitting new files or making modifications to existing ones.

:::info info

There are some issues with Arweave URL that may restrict normal routers.

Thus it is better to use a [Hash Router](https://v5.reactrouter.com/web/api/HashRouter) instead of a [Browser Router](https://v5.reactrouter.com/web/api/BrowserRouter).

If using a normal router, please use our custom domain to ensure 404 error does not pop up.

:::

## 1. Creating a Deployment

Select **New Project** on the Spheron dashboard and go through the following steps for deploying a successful project.

<img src={require('@site/static/img/3.0.0/dashboard.png').default} />

### Part 1. Pick a Repository

<font size="4"> <b>Step 1.</b> As spheron protocol offers services from <b>GitHub</b>, <b>GitLab</b> and <b>Bitbucket</b>, users can choose their desired option. Click on any git provider to fetch the repositories associated with it. </font> <br/><br/>

<img src={require('@site/static/img/3.0.0/deploy-choose-repo.png').default} />

You will be redirected to the selected provider's (GitHub/Gitlab/Bitbucket) authorization page.

After successful installation of your account, you will be automatically redirected to Spheron, where you can see the repositories present in your account.

<font size="4"> <b>Step 2.</b> Pick the repository you want to deploy. </font> <br/><br/>

<img src={require('@site/static/img/3.0.0/deploy-github-repo.png').default} />

### Part 2. Pick a Protocol

We support multiple decentralized protocols in which you can deploy your app. Pick the protocol which is most suited for your needs.

:::info

Currently, we support **Arweave**, **Skynet**, **Filecoin** and **Pinata** protocols. We are constantly working on adding multiple protocols, which will be added soon.

:::

<img src={require('@site/static/img/3.0.0/deploy-pick-protocol.png').default} />

### Part 3. Configure your Build options

Get control of the build settings for your site based on the framework of your app.

Click [here](deployments/get-started.md/#configuring-the-deployment) to know more about the build settings required by Spheron for your framework.

<img src={require('@site/static/img/3.0.0/deploy-build-options.png').default} />

### Part 4. Deploy

Upon successful selection of all the parameters, click the **Deploy** button to deploy your app.

Your deployment will start and the deployment logs will be visible on the screen.

<img src={require('@site/static/img/3.0.0/deploy-success.png').default} />
