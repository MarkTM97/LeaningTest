> [!TIP]
> Use [template functions](https://docs.microsoft.com/azure/azure-resource-manager/templates/template-functions-resource) to access common values like *`[resourceGroup().name]`* and **`[variables()]`**.

> [!CAUTION]
> This `arguments` property is invalid. If you're using the Azure Resource Manager extension in Visual Studio Code, it might flag this line. You'll fix this problem in the next steps.

> [!TIP]
> The last of these categories is implemented by using the Azure Policy Guest Configuration client, which is available as an Azure VM extension. Azure Arc for servers uses the same client to provide functionality in hybrid scenarios.
> Specifically, Contoso IT staff could use Azure Policy to assign tags to resources during their deployment. After you install the agent, it requires outbound connectivity to Azure Arc over TCP **443**. At that point any Azure Policy Guest Configuration client-based configuration that's in the assigned policy or initiative definition will automatically take effect.

## Italicized text in alert

> [!TIP]
> Applications and services use a *security identity* to access specific Azure resources. Think of it as a user identity (username and password or certificate) for an application. *Scope* is the set of resources to which the access applies.

## Alert in a list and new line in the middle

1. Open a web browser and sign into the Azure Portal

    > [!IMPORTANT]
    > Make sure to use your own subscription. When you are in the free sandbox environment, it will not allow you to create resource groups. You can tell which subscription you are using by looking at the tenant name under your profile picutre. You can switch tenants by selecting your profile picture and selecting **Switch Directory** from the options menu.
    >
    > This is an alert with a new line in the middle

1. On the Azure portal menu or from the **Home** page. select **Create a resource.**
3. Type **resource group** in the search box and hit Enter.
1. The first item in the list should be the resource group resource. Select it and then select the **Create** button.
1. # Image and alert in list
    > [!TIP]
    > Image after alert with a new line between
    
    ![cat image](../media/cat1.jpg)

    > [!TIP]
    > Image after alert. NO new line between
    ![cat image](../media/cat1.jpg)

    ![cat image](../media/cat2.jpg)

    > [!NOTE]
    > Image is before this alert in a list with new line between

    ![cat image](../media/cat2.jpg)
    > [!NOTE]
    > Image is before this alert in a list with NO new line between 

## Alert with headers

> [!TIP]
> ## Inline - Contoso, Ltd. Case Study
> ### Another header in this alert
> Use [template functions](https://docs.microsoft.com/azure/azure-resource-manager/templates/template-functions-resource) to access common values like `[resourceGroup().name]` and `[variables()]`.
> # Some heading 1

> [!CAUTION]
> This `arguments` property is invalid. If you're using the Azure Resource Manager extension in Visual Studio Code, it might flag this line. You'll fix this problem in the next steps.
