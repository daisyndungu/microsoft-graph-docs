---
description: "Automatically generated file. DO NOT MODIFY"
---

```php

<?php

// THIS SNIPPET IS A PREVIEW FOR THE KIOTA BASED SDK. NON-PRODUCTION USE ONLY
$graphServiceClient = new GraphServiceClient($requestAdapter);

$requestConfiguration = new HorizontalSectionColumnRequestBuilderGetRequestConfiguration();

$queryParameters = new HorizontalSectionColumnRequestBuilderGetQueryParameters();
$queryParameters->select = ["id","expand=webparts"];

$requestConfiguration->queryParameters = $queryParameters;


$requestResult = $graphServiceClient->sitesById('site-id')->pagesById('sitePage-id')->canvasLayout()->horizontalSectionsById('horizontalSection-id')->columnsById('horizontalSectionColumn-id')->get($requestConfiguration);


```