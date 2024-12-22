# minecraft-cheats

## Injection Methods

### Java Agent Injection
- How It Works: Utilzes Java's built-in java.lang.instrument API to attach an agent to the JVM and modify Minecraft's bytecode at runtime.

- Advantages:
  - Supported natively by Java(Might be possible with rust crates).
  - Easy to inject during startup.

- Disadvantages:
  - Can be detected by anti-cheat tools monitoring JVM agents.

- Examples: VapeV4, Dream Client.

### Native DLL/Memory Injection (C++/Rust Libraries)
- How It Works: Injects a native Dynamic Link Library (DLL) into the Minecraft Java process to manipulate memory and runtime behavior.

- Advantages:
  - Harder for server-side anti-cheats to detect
  - Low-level system access.

- Disadvantages:
  - More complex to develop. 
  - Can trigger Windows Defender or anti-virus
  - Needs Windows and Linux binaries

- Examples: VapeV4

### Mods
- How It works: Cheats are packaged as mods and loaded using modding APIs like Fabric.

- Advantages: Easier to distribute and use; integrates well with modded minecraft.

- Disadvantages: 

## Example Clients

### Vape V4
[VapeV4](https://www.vape.gg/)

Vape V4 is a premium Minecraft cheat client designed for closet cheating, focusing on subtlety to bypass Hypixel's Watchdog.

#### Price
- $6.99/month
- $24.49/one-time

#### Website Features
- Forum 
- Credit card payment
- Login/create account 

#### Client Features
- AutoClicker (Randomized CPS)
- SlientAura (KillAura but made using AimAssist and AutoClickers)
- Block-In (Automatically blocks you in by building walls around you)
- AntiFireball (Aims and swings at a fireball to deflect it)
- Anti-AFK (Prevents you from going AFK)
- Fake Lag (Creates network packets to resemble lag)
- Inventory presets (Automatically manage the items that go into each hotbar slot.)
- Inventory filters (Drop useless items or condense your inventory into a more manageable setup.)
- More features ( Not paying for client to see all features LMAFO)

### Future 
[Future](https://www.futureclient.net/index.php)

Future is a runtime injection client supporting multiple Minecraft verions, known for its extensive module list and compatiblity with various servers anti-cheat systems.

#### Price
- $24.99/one-time 

#### Website Features
- Features Page
- Stripe payments
- PayPal payments

#### Client Features
- AntiBots - Exempt Combat and Render modules from targeting bots.
- Aura - Attacks enemies.
- AutoArmor - Puts on armor.
- AutoBowRelease - Releases the bow at a specified server tick.
- AutoCrystal - Places and blows up End Crystals.
- AutoLog - Logs out at your disired health level.
- AutoObsidian - Surrounds yourself with obsidian.
- AutoPot - Throws an Instant Health potion under you.
- AutoSoup - Eats soup.
- AutoTotem - Replaces Totem of Undying in the off-hand.
- BowAim - Predicts enemies movement and aims at them using a Bow.
- CopsAndCrims - Aimbot for Hypixel Cops and Crims.
- Criticals - Give critical hits.
- SmoothAim - Aims smoothly at enemies.
- Trigger - Clicks for you when you are hovering over a target.

### TODO: Add more opensource clients
