---
title: Audio Listener Component
template: page.tmpl.html
skip: true
---

The 'audiolistener' component specifies the listener's position in 3D space. All 3D audio playback will be relative to this position.

<img alt="Component Interface" src="/images/platform/component_audiolistener.png" />

## Properties

This component has no properties. It simply uses the entity's position in 3D space to determine the location of the listener.

## Scripting Interface

You can control an audiolistener component's properties using a [script component][script_component]. The audiolistener component's scripting interface is [here][docs].

[script_component]: /user-manual/packs/entities/components/script
[docs]: /engine/api/stable/symbols/pc.fw.AudioListenerComponent.html