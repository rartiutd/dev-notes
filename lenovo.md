Lenovo Legion 5 Low Microphone Volume Issue Fix 15ACH6H/16ACH6H/17ACH6H
Tech Support

I've been having issues with my mic volume on my new Lenovo laptop for quite some time. It didn't matter if I was using an external 3.5mm mic, USB mic or the integrated one. It was at 100% volume with +30dB boost. I was using the latest official drivers from the Lenovo website.

The was I managed to fix it was to

- Uninstall the Realtek audio driver from Device Manager and the Lenovo Audio console from Apps
- Restart
- Install the Windows 11 Realtek Audio driver (even if you're on Windows 10)
- Install the Nihamic app from the Microsoft Store.
- Restart again.

I'm sharing my solution because I've read a lot of posts from people with the same issue.
