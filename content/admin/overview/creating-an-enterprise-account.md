---
title: Creating an enterprise account
intro: 'If you''re currently using {% data variables.product.prodname_ghe_cloud %} with a single organization, you can create an enterprise account to centrally manage multiple organizations.'
versions:
  ghec: '*'
type: how_to
topics:
  - Accounts
  - Enterprise
  - Fundamentals
permissions: Organization owners can create an enterprise account.
shortTitle: Create enterprise account
---

## About enterprise account creation

{% data variables.product.prodname_ghe_cloud %} allows you to create an enterprise account, which enables collaboration between multiple organizations and gives administrators a single point of visibility and management. When you purchase {% data variables.product.prodname_ghe_cloud %}, you can create an enterprise account. Creation of an enterprise account does not result in additional charges on your bill.

For more information, see "[About enterprise accounts](/admin/overview/about-enterprise-accounts)."

{% data reusables.enterprise.create-an-enterprise-account %} If you pay by invoice, you can create an enterprise account yourself on {% data variables.product.prodname_dotcom %}. If not, you can [contact our sales team](https://github.com/enterprise/contact?ref_page=/pricing&ref_cta=Contact%20Sales&ref_loc=cards) to create an enterprise account for you.

When you create an enterprise account that owns your existing organization on {% data variables.product.product_name %}, the organization's resources remain accessible to members at the same URLs. After you add your organization to the enterprise account, the following changes will apply to the organization.

- Your existing organization will automatically be owned by the enterprise account.
- {% data variables.product.company_short %} bills the enterprise account for usage within all organizations owned by the enterprise. The current billing details for the organization, including the organization's billing email address, will become billing details for the new enterprise account. For more information, see "[About billing for your enterprise](/billing/managing-billing-for-your-github-account/about-billing-for-your-enterprise)."
- All current owners of your organization will become owners of the enterprise account, and all current billing managers of the organization will become billing managers of the new enterprise account. For more information, see "[Roles in an enterprise](/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise)."

For more information about the changes that apply to an organization after you add the organization to an enterprise, see "[Adding organizations to your enterprise](/admin/user-management/managing-organizations-in-your-enterprise/adding-organizations-to-your-enterprise#about-addition-of-organizations-to-your-enterprise-account)."

## Creating an enterprise account on {% data variables.product.prodname_dotcom %}

To create an enterprise account, your organization must be using {% data variables.product.prodname_ghe_cloud %}.

If you pay by invoice, you can create an enterprise account directly through {% data variables.product.prodname_dotcom %}. If you do not currently pay by invoice, you can [contact our sales team](https://github.com/enterprise/contact?ref_page=/pricing&ref_cta=Contact%20Sales&ref_loc=cards) to create an enterprise account for you.


{% data reusables.organizations.billing-settings %}
1. Click **Upgrade to enterprise account**.
1. Under "Enterprise name", type a name for your enterprise account.
1. Under "Enterprise URL slug", type a slug for your enterprise account. This slug will be used in the URL for your enterprise. For example, if you choose `octo-enterprise`, the URL for your enterprise will be `https://github.com/enterprises/octo-enterprise`.
1. Click **Confirm and upgrade**.
1. Read the warnings, then click **Create enterprise account**.

## Next steps

After your enterprise account is created, we recommend learning more about how enterprise accounts work and configuring settings and policies. For more information, follow the "[Get started with your enterprise account](/admin/guides#get-started-with-your-enterprise-account)" learning path.
