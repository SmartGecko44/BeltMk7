# Conveyor Belt Mk6*

_If you enjoy my work, please consider my [completely optional tip jar](https://ko-fi.com/robb4)._

This mod adds a conveyor belt (and lift) that moves **2000 items per minute**,
which is the fastest speed a conveyor belt can move items before they start getting deleted.

It looks exactly the same as the Mk5 belt; the point of this mod is literally just a faster belt,
it is not focused on graphics or anything else.
Unlock it in T8 in the HUB. They are quite pricy given their high speed.
I balanced them around being used in small quantities where their high-throughput is required the most.

## Answered Questions

**Want an even faster belt?**
That's not how this works.
Until something changes in the base game, 2000/min is as fast as it gets.
Use something like [Heavy Solid Overhaul](https://ficsit.app/mod/HeavySolids) if you want to move more items per minute.

**Want more tiers of belt in the middle?**
That's not what this mod is for, get something like [Simple Conveyor](https://ficsit.app/mod/conveyorbeltmod) instead.

**Don't want any modded buildings in your save file?**
Use [Enhanced Conveyors](https://ficsit.app/mod/EnhancedConveyors) instead.

**Don't like the build or unlock costs I chose?**
Use [ContentLib](https://ficsit.app/mod/ContentLib) to change them to what you want!

**Worried I will disappear and your save will be broken forever if you use these belts?**
Unlikely, but see the "Uninstalling" directions below to convert all of your Mk6* belts to something else even if the mod isn't installed.
Also, the mod is open source, so you can update it yourself.

**The belt isn't reaching 2000 items/min in your game?**
Read the section below.

## *Measuring True Belt Speed

Depending on your computer, the belt may not reach this speed.
That's why they're called "Mk6*" - this is the asterisk.
As such, you should test the belt's actual speed before using it in your factory.
The [Throughput Counter Limiter](https://ficsit.app/mod/CounterLimiter)
mod is automatically installed with this mod to assist you with this process.

Build a setup like this to check what belt speed you get before designing your setups around it:

![Belt speed tester](https://i.imgur.com/b0Y2jgl.jpeg)

## Uninstalling

Want to uninstall this mod? Use Core Redirects to replace all of your Mk6* belts with another belt type.
The process for doing this is outlined in [this guide](https://ficsit.app/guide/Mg9t1BzVdaGhz).
Use the following core redirect file to replace the belt with Mk5 belt and the lift with Mk5 lift:

```ini
[CoreRedirects]
+ClassRedirects=(OldName="/BeltMk6/Buildable/ConveyorLiftMk6/Build_ConveyorLiftMk6.Build_ConveyorLiftMk6_C",NewName="/Game/FactoryGame/Buildable/Factory/ConveyorLiftMk5/Build_ConveyorLiftMk5.Build_ConveyorLiftMk5_C")
+ClassRedirects=(OldName="/BeltMk6/Buildable/ConveyorBeltMk6/Build_ConveyorBeltMk6.Build_ConveyorBeltMk6_C",NewName="/Game/FactoryGame/Buildable/Factory/ConveyorBeltMk5/Build_ConveyorBeltMk5.Build_ConveyorBeltMk5_C")
```
