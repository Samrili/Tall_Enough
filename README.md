# Tall Enough — Co-op Multiplayer RTS Extension (Unreal Engine 5.3)

**Tall Enough** is a 2-player cooperative strategy and island management project developed on **Unreal Engine 5.3** (Blueprints & C++), built by extending the [Unreal Engine Cropout Sample](https://www.unrealengine.com/marketplace/en-US/product/cropout-sample-project) and its Steam multiplayer replication foundation.

---

## Custom Modules & Features Implemented

### 1. Gameplay & Progression Systems (\@Samrili\)
- **Blacksmith Upgrade System:** Interactive building and unit upgrade mechanics with custom blacksmith textures and state logic.
- **Game Speed & Editor Controls:** Dynamic in-game speed acceleration toggle and editor mode controls.
- **End-Game UI & Animations (\UI_EndGame.uasset\):** Custom victory/end-game screen layouts and UI transition animations.
- **Localization Support:** Multi-language UI text localization setup.

### 2. Backend & Database Integration (\@TheAtom71\)
- External database connectivity, table bindings, API authorization rules, and coordinate request synchronization.

---

## Technical Specifications
- **Engine:** Unreal Engine 5.3
- **Architecture:** Blueprints & C++ Structs
- **Networking:** Steam SDK Listen-Server & Dedicated-Server Session Replication