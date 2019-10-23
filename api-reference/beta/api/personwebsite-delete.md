---
title: "Delete personWebsite"
description: "Delete personWebsite."
localization_priority: Normal
author: "kevinbellinger"
ms.prod: "People"
doc_type: "apiPageType"
---

# Delete personWebsite

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Deletes a personWebsite entry from the users profile.

## Permissions

One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

| Permission type                        | Permissions (from least to most privileged) |
|:---------------------------------------|:--------------------------------------------|
| Delegated (work or school account)     | User.ReadWrite, User.ReadWrite.All |
| Delegated (personal Microsoft account) | User.ReadWrite, User.ReadWrite.All |
| Application                            | User.ReadWrite.All |

## HTTP request

<!-- { "blockType": "ignored" } -->

```http
DELETE /me/profile/websites/{id}
```

## Request headers

| Name      |Description|
|:----------|:----------|
| Authorization  | Bearer {token}. Required.|
| Content-Type   | application/json |

## Request body

Do not supply a request body for this method.

## Response

If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

## Examples

### Request

The following is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_personwebsite"
}-->

```http
DELETE https://graph.microsoft.com/Beta/me/profile/websites/{id}
```

### Response

The following is an example of the response.

<!-- {
  "blockType": "response",
  "truncated": true
} -->

```http
HTTP/1.1 204 No Content
```

<!-- uuid: 16cd6b66-4b1a-43a1-adaf-3a886856ed98
2019-02-04 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete personWebsite",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->