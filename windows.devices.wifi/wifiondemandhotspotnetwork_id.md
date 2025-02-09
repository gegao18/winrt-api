---
-api-id: P:Windows.Devices.WiFi.WiFiOnDemandHotspotNetwork.Id
-api-type: winrt property
---

# Windows.Devices.WiFi.WiFiOnDemandHotspotNetwork.Id

<!--
public Guid Id { get; }
-->


## -description

A caller-chosen globally-unique identifier (GUID) that is intended to identify the hotspot.

> [!NOTE]
> If you want to use this API in a UWP app, and publish your app to the Microsoft Store, then you'll need to request special approval to use the custom capability **Microsoft.onDemandHotspotControl_8wekyb3d8bbwe** (the On-Demand Network capability). For more info, see [Custom capabilities](/windows/uwp/packaging/app-capability-declarations#custom-capabilities).
>
> The On-Demand Network capability will be made available only to app developers building end-to-end Wi-Fi hotspot scenarios between a tethering-capable hardware device and a Windows PC.

## -property-value

## -remarks

The id is unique per calling app, but it might be the same between apps.

An app has visibility only into its own on-demand hotspot networks, and can't see networks added by other apps.

## -see-also

## -examples

## -capabilities
onDemandHotspotControl
