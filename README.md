# 💨 DIY Portable Air Purifier Designs

Laser cutting designs and instructions for DIY portable air purifiers with 1 or 2 fans.

| Instructions | **Approximate Cost (NZD)** | **Estimated CADR (CFM)** | **Estimated CADR (CMH)** |
|--|--|--|--|
| [Single Fan](./single-fan) | $210 | 46 | 78 |
| [Double Fan](./double-fan) | $330 | 92 | 156  |

**Skill Level**: Beginner

**Time to Build**: 15 minutes

The first time you build it will no doubt be slower as you get familiar with the pieces.

The instructions have links to purchase components from AliExpress, shipping will take a few weeks.

The electrical part is simply plugging in a series of cables, each has their own shape and can only be plugged in one way. It's easier than plugging in the old rectangular USB's!

The designs also make use of the [3D printing files for air straighteners](https://github.com/chrisjensen/air-straightener/tree/main) to mount on these so that they create a nice strong wall of straight flowing air.

## What does it look like?

Here's the single design in black, and the double.

![20250109_214003](https://github.com/user-attachments/assets/2523abcd-9853-43ae-82d7-cee907c1b668)

## 😅 New to this? Don't worry! You've got this 🙌

_Laser Cutting, 3D printing, electrics? oh my!_

If you can build an IKEA bookshelf or chair, you can do this.

You don't even need a screwdriver, it can all be assembled by hand!

There's detailed instructions on the next page with pictures you can follow.

## 🔨 Laser Cutting & 3D Printing

The easiest way to get your materials cut accurately to size is to get them laser cut and 3D printed.

Most major cities have places have materials on hand ready to be cut and will post the result to you for a fee. To find them, you can goodle `laser cut wood [major city near you]` and `3d printing [major city near you]`.

In New Zealand I use [Make Shop](https://www.makeshop.co.nz/) for my laser cutting, and in Australia I use [The Laser Co](https://thelaserco.com/). Whoever you use will have their own requirements for how you provide files to them and you may need to adjust the files accordingly.

Both of these places will have MDF on hand, and can cut and post it directly to you.

Now choose if you're making a [double fan](./double-fan/) or [single fan](./single-fan) design  follow the instructions in those folders.

## USB-C and USB-A adapters

The fans run on 12V while USB puts out 5V. There's a couple of ways you can get 12V from a USB power bank:

#### Get a USB-A that converts to 12V

I prefer this option as it's simple, the hardware is designed to do this all the time, and it just works. The only downside is that the USB plug is pretty bulky, and often flimsy and prone to breaking if it's knocked around a lot. By putting the battery under the filter and holding it in place with elastic it is reasonably well protected from this.

<img width="393" alt="Screenshot 2025-01-05 at 2 28 15 PM" src="https://github.com/user-attachments/assets/f2004017-541b-450e-9996-fa06dc4546fd" />

#### Get a USB-C that does Power Delivery

You've probably seen this if you've got a new phone. It uses the new Power Delivery protocol to get more power from the USB battery and charge quickly. In theory you can buy a USB-C Power Delivery adapter from AliExpress.

The nice thing about these is that they're more compact as it just asks the battery pack or wall plug itself to deliver the 12V, so it doesn't need any bulky hardware for converting the power from 5V to 12V. Unfortunately, in my experience, these adapters can be bad at negotiating the Power Delivery protocol, and the power supply ends up only providing 5V which means the fan doesn't run at full speed.

If you want the USB-C, then get a USB-A as a fall back and to test it - you'll be able to hear the difference if it runs slower on one of them.

<img width="339" alt="Screenshot 2025-01-06 at 12 37 25 PM" src="https://github.com/user-attachments/assets/1f4aa6a9-f3b6-4c65-af7a-77629b10cdf4" />

