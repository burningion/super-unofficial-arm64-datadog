# Super Unofficial ARM64 Deb for Datadog Agent 6.11

I got tired of manually builiding the Agent for my Jetson TX1, TX2, Nano, and Raspberry Pi version 3. So I built this `deb` using the Omnibus build for Datadog. There are zero guarantees that this will work, I did it in my own time. (But it _should_ work.)

You _should_ be able to install this using just a `sudo dpkg -i <filename>.deb`. If you're running Raspbian it _won't_ work. That's because Raspbian defaults to 32 bits, and this is a 64 bit build.

All the files live in the `pkg/` directory.


