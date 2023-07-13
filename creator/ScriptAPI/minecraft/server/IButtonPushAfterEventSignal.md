---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.IButtonPushAfterEventSignal Class
description: Contents of the @minecraft/server.IButtonPushAfterEventSignal class.
---
# IButtonPushAfterEventSignal Class

## Classes that extend IButtonPushAfterEventSignal
- [*ButtonPushAfterEventSignal*](ButtonPushAfterEventSignal.md)

Provides an adaptable interface for callers to subscribe to an event that fires when a button is pushed.

## Methods
- [subscribe](#subscribe)
- [unsubscribe](#unsubscribe)

### **subscribe**
`
subscribe(callback: (arg: ButtonPushAfterEvent) => void): (arg: ButtonPushAfterEvent) => void
`

#### **Parameters**
- **callback**: (arg: [*ButtonPushAfterEvent*](ButtonPushAfterEvent.md)) => *void*

#### **Returns** (arg: [*ButtonPushAfterEvent*](ButtonPushAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

### **unsubscribe**
`
unsubscribe(callback: (arg: ButtonPushAfterEvent) => void): void
`

#### **Parameters**
- **callback**: (arg: [*ButtonPushAfterEvent*](ButtonPushAfterEvent.md)) => *void*

> [!IMPORTANT]
> This function can't be called in read-only mode.

> [!WARNING]
> This function can throw errors.