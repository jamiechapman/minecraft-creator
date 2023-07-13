---
# DO NOT TOUCH — This file was automatically generated. See https://github.com/mojang/minecraftapidocsgenerator to modify descriptions, examples, etc.
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.BlockLiquidContainerComponent Class
description: Contents of the @minecraft/server.BlockLiquidContainerComponent class.
---
# BlockLiquidContainerComponent Class

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

## Extends
- [*BlockComponent*](BlockComponent.md)

## Classes that extend BlockLiquidContainerComponent
- [*BlockLavaContainerComponent*](BlockLavaContainerComponent.md)
- [*BlockPotionContainerComponent*](BlockPotionContainerComponent.md)
- [*BlockSnowContainerComponent*](BlockSnowContainerComponent.md)
- [*BlockWaterContainerComponent*](BlockWaterContainerComponent.md)

For blocks that can contain a liquid (e.g., a cauldron), this is a base component for liquid containers. 

## Properties

### **fillLevel**
`fillLevel: number;`

Relative fill level of the liquid container.

Type: *number*
  
> [!IMPORTANT]
> This property can't be edited in read-only mode.

## Methods
- [isValidLiquid](#isvalidliquid)

### **isValidLiquid**
`
isValidLiquid(): boolean
`

Returns true if the liquid type is valid for this container.

#### **Returns** *boolean*