# 💨 DIY Portable Air Purifier Designs

Laser cutting designs and instructions for DIY portable air purifiers with 1 or 2 fans.

| Fans | **Approximate Cost (NZD)** | **Estimated CADR (CFM)** | **Estimated CADR (CMH)** |
|--|--|--|--|
| Single Fan | $210 | 46 | 156 |
| Double Fan | $330 | 92 | 78  |

**Skill Level**: Beginner

**Time to Build**: 15 minutes

The first time you build it will no doubt be slower as you get familiar with the pieces.

The instructions have links to purchase components from AliExpress, shipping will take a few weeks.

The electrical part is simply plugging in a series of cables, each has their own shape and can only be plugged in one way. It's easier than plugging in the old rectangular USB's!

The designs also make use of the [3D printing files for air straighteners](https://github.com/chrisjensen/air-straightener/tree/main) to mount on these so that they create a nice strong wall of straight flowing air.

## What does it look like?

**Double Fan Design**

![20250106_120740](https://github.com/user-attachments/assets/f8a7d340-7442-4b41-a5e7-abc65143f97e)

**Single Fan Design**

![20250106_115531](https://github.com/user-attachments/assets/936aabd5-76fa-4d2d-92cc-a36dd6622160)

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

The fans run on 12V while USB puts out 5V. There's a couple of ways you can get 12V for this:

#### Get a USB-A that converts to 12V

I prefer this option as it's simple, the hardware is designed to do this all the time, and it just works. The only downside is that the USB plug is pretty bulky, and often flimsy and prone to breaking if it's knocked around a lot. By putting the battery under the filter and holding it in place with elastic it is reasonably well protected fro this.

<img width="393" alt="Screenshot 2025-01-05 at 2 28 15 PM" src="https://github.com/user-attachments/assets/f2004017-541b-450e-9996-fa06dc4546fd" />

#### Get a USB-C that does Power Delivery

You've probably seen this if you've got a new phone. It uses the new Power Delivery protocol to get more power from the USB battery and charge quickly. In theory you can buy a USB-C Power Delivery adapter from AliExpress.

The nice thing about these is that they're more compact as it just asks the battery or wall plug itself to deliver the 12V, so it doesn't need any bulky hardware for converting the power from 5V to 12V. Unfortunately, in my experience, these adapters can be bad at negotiating the Power Delivery protocol, and the power supply ends up only providing 5V and the fan doesn't run at full speed.

<img width="339" alt="Screenshot 2025-01-06 at 12 37 25 PM" src="https://github.com/user-attachments/assets/1f4aa6a9-f3b6-4c65-af7a-77629b10cdf4" />

