---

copyright:
  years: 2021
lastupdated: "2021-11-22"

subcollection: fortigate-10g

---

{{site.data.keyword.attribute-definition-list}}

# Managing permissions
{: #managing-permissions}

To view and manage your FortiGate Security Appliance (FSA) 10 Gbps firewalls you need the correct permissions. After your account administrator grants your user account permissions and access, you can view your FSA 10 Gbps firewall details by using the {{site.data.keyword.cloud}} console, or by using the {{site.data.keyword.slapi_short}}. The information or actions that you see depend on your permissions.
{: shortdesc}

The following permissions are required for viewing and managing various parts of your FSA 10 Gbps firewalls:

* **Manage firewalls** - Allows you to view your list of firewalls. It also allows you to view and manage the details of a specific firewall.
* **Manage network gateways** - Allows you to view your list of FSA 10 Gbps firewalls. It also allows you to view and manage the details of a specific FSA 10 Gbps firewall.
* **Cancel services** - Allows you to cancel a firewall.

## Adding permissions for your users
{: #adding-permissions-for-your-users}

If you are the account administrator and you want to grant a user permission to view and manage gateway appliance details, complete the following steps.

1. Log in to the [Access (IAM)](https://cloud.ibm.com/iam/users){: external} page in the {{site.data.keyword.cloud}} console.
2. Select **View: My classic infrastructure users**.
3. Select a user, click the **Classic infrastructure** tab, then click the **Permissions** tab.
4. Expand the **Devices** category and select **Manage firewalls**.
4. Expand the **Network** category and select **Manage network gateways**.
4. Expand the **Account** category and select **Cancel services**.
6. Click **Apply**.

## Next steps
{: #next-steps}

User permissions are updated immediately after the changes are submitted. If permissions are granted, the user can view or interact with the selected features. If permissions are removed, the user can no longer view or interact with the selected features. Permissions can be updated again at any time.
