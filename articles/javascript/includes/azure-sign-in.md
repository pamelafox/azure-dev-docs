---
ms.custom: devx-track-js
ms.topic: include
ms.date: 10/05/2021
---

1. To sign into your Azure account, navigate to the **Azure** explorer.
1. Select **Sign in to Azure**, and follow the prompts. 

    ![Sign in to Azure through VS Code](../media/deploy-azure/azure-sign-in.png)

    If this is not available, you are currently signed in. Verify that the email address of your Azure account (or "Signed In") appears in the Status Bar and your subscription(s) appears in the **Azure** explorer:

    ![VS Code status bar showing Azure account](../media/deploy-azure/azure-account-status-bar.png)

    ![VS Code Azure explorer showing subscriptions](../media/deploy-azure/azure-subscription-view.png)

> [!NOTE]
> If you see the error **"Cannot find subscription with name [subscription ID]"**, this may be because you are behind a proxy and unable to reach the Azure API. Configure `HTTP_PROXY` and `HTTPS_PROXY` environment variables with your proxy information in your terminal:
>
> # [bash](#tab/bash)
>
> ```bash
> export HTTPS_PROXY=https://username:password@proxy:8080
> export HTTP_PROXY=http://username:password@proxy:8080
> ```
>
> # [PowerShell](#tab/powershell)
>
> ```powershell
> $env: HTTPS_PROXY = "https://username:password@proxy:8080"
> $env: HTTP_PROXY = "http://username:password@proxy:8080"
> ```
>
> # [Cmd](#tab/cmd)
>
> ```cmd
> set HTTPS_PROXY=https://username:password@proxy:8080
> set HTTP_PROXY=http://username:password@proxy:8080
> ```
>
> ---
