---
title: Create a Relay namespace using the Azure portal | Microsoft Docs
description: In order to get started with Azure Relay, you will need a namespace. Here's how to create one using the Azure portal.
services: service-bus-relay
documentationcenter: .net
author: jtaubensee
manager: timlt
editor: ''

ms.assetid: 78ab6753-877a-4426-92ec-a81675d62a57
ms.service: service-bus-relay
ms.devlang: tbd
ms.topic: get-started-article
ms.tgt_pltfrm: multiple
ms.workload: na
ms.date: 10/28/2016
ms.author: jotaub

---
# Create a Relay namespace using the Azure portal
A namespace is a common container for all your Relay components. Multiple Relays can reside in a single namespace, and namespaces often serve as application containers. There are currently two different ways to create a Relay namespace.

1. Azure portal (this article)
2. [Azure Resource Manager](../azure-resource-manager/resource-group-overview.md) templates

## Create a namespace in the Azure portal
[!INCLUDE [relay-create-namespace-portal](../../includes/relay-create-namespace-portal.md)]

Congratulations! You have now created a Relay namespace.

## Next steps:
* [Relay FAQ](relay-faq.md)
* [Get started with .NET](relay-hybrid-connections-dotnet-get-started.md)
* [Get started with Node](relay-hybrid-connections-node-get-started.md)

