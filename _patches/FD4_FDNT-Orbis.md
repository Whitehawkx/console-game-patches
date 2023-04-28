# Dark Souls III: Network Stress Test

[Game Index](README.md#games)

[Installation Guide](https://illusion0001.github.io/install-instructions/)

## Framerate Patch

### 60 FPS Unlock (With Delta Time)

Author: [illusion](https://twitter.com/illusion0002)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x2390407 C7 43 08 05 00 00 00 EB 07
0x239050C 41 B6 01
```

</details>

<!--

### 30 FPS Limit (Proper Frame-Pacing)

Author: [illusion](https://twitter.com/illusion0002)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
# Fliprate

# sceVideoOutSetFlipRate 0x1
```

</details>

-->

## 720p Resolution

Author: [illusion](https://twitter.com/illusion0002)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x5926D84 00 05 00 00 D0 02 00 00
```

## 900p Resolution

Author: [Whitehawkx](https://twitter.com/Whitehawkx)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x5926D84 40 06 00 00 84 03 00 00
```

## Enable TopMenuDebug (hidden additional menu)

Author: [Whitehawkx](https://twitter.com/Whitehawkx)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x19F3D96 B2 01
```

## Enable Developer Debug Menu (touchpad)

Author: [Whitehawkx](https://twitter.com/Whitehawkx)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x236A352 01
```

## Enable All Menu Options (Equipment, Status, Inventory)

Author: [Whitehawkx](https://twitter.com/Whitehawkx)
Author: [Lance McDonald](https://twitter.com/manfightdragon)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x1EA69A9 90 90 90 90 90 90
```

## Enable Video Recording (share button)

Author: [Whitehawkx](https://twitter.com/Whitehawkx)

In file `eboot.bin`

<details>
<summary>Code (Click to Expand)</summary>

```
0x236775F 00
```

</details>
