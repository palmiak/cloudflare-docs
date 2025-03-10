---
order: 6
pcx-content: how-to
---

import BeforeYouBegin from "../_partials/_before-you-begin.md"

# Network solutions

You can follow the instructions below to transfer your domain from Network Solutions to Cloudflare.

---

## Before you begin

<BeforeYouBegin/>

--------

## Restrictions
To transfer to a new registrar, your domain must meet the following requirements.

* ICANN rules prohibit a domain from being transferred if it has been transferred within the last 60 days or if the WHOIS contact information was modified in the last 60 days (even if redacted).
* Your account at your current registrar must be active. If your domain has expired, you may have to pay a redemption fee to renew it before you can process a transfer.
* Cloudflare does not currently support premium domains. Some registries designate a domain name as “premium” and charge higher wholesale rates for these domains.

If it is listed as available for transfer in the Cloudflare dashboard, these restrictions have already been checked.

--------

## Email forwarding
Cloudflare Registrar does not currently support email forwarding. If you require email forwarding from your registrar, you will need to use a third-party forwarding service and configure your MX record in the Cloudflare DNS setting for the domain.

--------

## Step 1: Login to Network Solutions
Login to the Network Solutions account where the domain is registered. Navigate to the **Account Settings** page.

--------

## Step 2: Unlock the domain and request authorization code
In the **Details** section, select “Turn Off or Request Authorization Code” next to **Transfer Lock**. Once you hit “Continue”, you will need to acknowledge the Network Solutions’ transfer terms.

After confirming the terms, you may be asked to complete survey questions. Once completed, click “Request Authorization Code”. You will need to select “Leave Domain Protect off” and then check the “Request Authorization Code” box. Once checked, click save.

Network Solutions will email the code to the registrant contact email on file for your domain.

If you do not receive the code, please check the registrant email address listed in the domain contact information for the given domain. It might be different than your GoDaddy account email.

--------

## Step 3: Add domain to Cloudflare
Log in to your [Cloudflare dashboard](https://dash.cloudflare.com/login). Choose the account where you want to add the domain. From the accounts home, click **Add a Site** to add the new domain to your Cloudflare account.

---

## Step 4: Transfer to Cloudflare
Go to your Cloudflare dashboard. From your accounts home, click **Registrar** > **Transfer** and input the authorization code. Each domain will have a unique authorization code and you will need to enter each for every domain you want to transfer.

If you do not see this screen or do not have an authorization code, please ensure you have gone through all the steps mentioned above before trying to transfer your domain to Cloudflare.

--------

## Step 5: Approve the transfer
Once Cloudflare processes your transfer, Network Solutions will send an email to the domain’s registrant contact (the same address where the authorization code was emailed). The email will contain a link that you can click to immediately approve and process the transfer. If you do not click the link, the transfer will automatically be approved within five days.
