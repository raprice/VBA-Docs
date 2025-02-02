---
title: MailMergeDataSource.EverValidated property (Publisher)
keywords: vbapb10.chm6291496
f1_keywords:
- vbapb10.chm6291496
ms.prod: publisher
api_name:
- Publisher.MailMergeDataSource.EverValidated
ms.assetid: f87980c8-d327-9313-fa6d-efdfaecb0e35
ms.date: 06/11/2019
ms.localizationpriority: medium
---


# MailMergeDataSource.EverValidated property (Publisher)

Indicates whether the list of recipient addresses in the parent **MailMergeDataSource** object has ever been validated. Read/write.


## Syntax

_expression_.**EverValidated**

_expression_ A variable that represents a **[MailMergeDataSource](Publisher.MailMergeDataSource.md)** object.


## Return value

Boolean


## Remarks

The initial value of **EverValidated** is **False**.

If you create an add-in for Microsoft Publisher that validates recipient addresses and maintains its own data sources, your add-in can set the **EverValidated** property value to **True** after a successful validation.

The value of the **EverValidated** property is saved in the Microsoft Publisher file and is accessible across multiple sessions of Publisher.

[!include[Support and feedback](~/includes/feedback-boilerplate.md)]