---
title: LCSC Barcode Plugin
---

## LCSC Barcode Plugin

The **LCSC Barcode Plugin** provides barcode support for [LCSC](https://lcsc.com/) products. When receiving items from LCSC, the barcode on the product can be scanned to automatically identify the product in InvenTree.

This plugin implements the [BarcodeMixin](../mixins/barcode.md) mixin to provide custom barcode support - see [Barcode Plugins](./barcode_index.md).

### Activation

This plugin is an *optional* plugin, and must be enabled in the InvenTree admin center.

### Plugin Settings

After activating the plugin, the user must specify which [supplier](../../purchasing/supplier.md) the plugin should be associated with. This is done by selecting the supplier from the dropdown list in the plugin settings:

{{ image("lcsc_plugin_settings.png", base="plugin/builtin", title="LCSC Plugin Settings") }}
