# Gender Mod

A Minecraft Forge mod for version 1.21.1 with a gender selection menu and G keybind.

## Features

- **Gender Menu**: Simple GUI to select Male, Female, or Other
- **G Keybind**: Press G to open the gender selection menu
- **Persistent Storage**: Gender selection is saved
- **Version**: 1.21.1 (Minecraft Java Edition)

## Installation

### Prerequisites
- Java 21+
- Minecraft Forge 1.21.1
- Gradle (for building from source)

### Building from Source

1. Clone this repository:
   ```bash
   git clone https://github.com/jdj212223-ctrl/GenderMod.git
   cd GenderMod
   ```

2. Build the mod:
   ```bash
   ./gradlew build
   ```

3. The compiled JAR will be in `build/libs/gender-mod-1.0.0.jar`

4. Copy the JAR to your `mods` folder:
   ```
   %AppData%\.minecraft\mods\  (Windows)
   ~/.minecraft/mods/  (Linux/Mac)
   ```

## Usage

1. Launch Minecraft with Forge
2. Load the mod
3. Press **G** to open the Gender Selection menu
4. Choose Male, Female, or Other
5. Click Close to save

## Keybinds

- **G**: Open Gender Menu (configurable in Controls)

## Project Structure

```
src/
├── main/
│   ├── java/com/example/gendermod/
│   │   ├── GenderMod.java
│   │   ├── client/
│   │   │   ├── GenderMenuScreen.java
│   │   │   └── KeyBindingHandler.java
│   │   ├── config/
│   │   │   └── GenderConfig.java
│   │   └── network/
│   │       └── GenderPackets.java
│   └── resources/
│       ├── META-INF/mods.toml
│       ├── assets/gendermod/lang/en_us.json
│       └── log4j2.xml
build.gradle
```

## Contributing

Feel free to submit issues and pull requests!

## License

MIT License - feel free to use this mod as you wish.

## Author

Created with support from Comet Assistant
