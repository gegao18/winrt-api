---
-api-id: M:Windows.Services.Cortana.CortanaActionableInsights.ShowInsightsForImageAsync(Windows.Storage.Streams.IRandomAccessStreamReference)
-api-type: winrt method
ms.custom: RS5
---

<!-- Method syntax.
public IAsyncAction CortanaActionableInsights.ShowInsightsForImageAsync(IRandomAccessStreamReference imageStream)
-->

# Windows.Services.Cortana.CortanaActionableInsights.ShowInsightsForImageAsync

## -description

Asynchronously retrieves and displays insights based on the specified image content.

> [!IMPORTANT]
> The [CortanaActionableInsights](cortanaactionableinsights.md) APIs are a limited access feature. Please contact [InsightsAPISupport@microsoft.com](mailto://InsightsAPISupport@microsoft.com) for more info, or to request an unlock token.

## -parameters

### -param imageStream

The image that defines the scope of the insights returned.

## -returns

Returns an [IAsyncAction](../windows.foundation/iasyncaction.md) object that is used to control asynchronous execution. If the system does not support showing insights, the method has no effect. An app can check for this case using the [IsAvailableAsync](cortanaactionableinsights_isavailableasync_962669120.md) method.

## -capabilities

cortanaSurface

## -remarks

The [CortanaActionableInsights](cortanaactionableinsights.md) class requires the following be added to the Package.appxmanifest:

- To \<Package\>
  - `xmlns:rescap="http://schemas.microsoft.com/appx/manifest/foundation/windows10/restrictedcapabilities"`
  - `IgnorableNamespaces="rescap"`
- Under \<Capabilities\>
  - `<rescap:capability name="cortanaSurface"/>`

## -see-also

[ShowInsightsForImageAsync(IRandomAccessStreamReference imageStream, CortanaActionableInsightsOptions options)](cortanaactionableinsights_showinsightsforimageasync_751542345.md)

## -examples
