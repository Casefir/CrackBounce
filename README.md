<div align="center">
<p>
    <img width="200" src="https://raw.githubusercontent.com/CCBlueX/LiquidCloud/master/LiquidBounce/liquidbounceLogo.svg">
</p>

# CrackBounce

**A community fork of [LiquidBounce](https://github.com/CCBlueX/LiquidBounce)**

[Upstream LiquidBounce](https://github.com/CCBlueX/LiquidBounce) |
[Website](https://liquidbounce.net) |
[Forum](https://forums.ccbluex.net) |
[Discord](https://liquidbounce.net/discord) |
[YouTube](https://youtube.com/CCBlueX) |
[X](https://x.com/CCBlueX)
</div>

CrackBounce is a free and open-source, Fabric-based Minecraft client forked from [LiquidBounce](https://github.com/CCBlueX/LiquidBounce) by [@Casefir](https://github.com/Casefir). It retains attribution to the upstream project and is developed independently. **Made by Casefir.**

## Issues

If you find a bug or have a feature request for CrackBounce, please open an
[issue in this repository](https://github.com/Casefir/CrackBounce/issues).

For issues specific to the upstream LiquidBounce project, use the
[LiquidBounce issue tracker](https://github.com/CCBlueX/LiquidBounce/issues).

## License

This project is subject to the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html). This
applies to source code located directly in this repository. During development and compilation, additional source code
may be used to which we have obtained no rights. Such code is not covered by the GPL license.

For those who are unfamiliar with the license, here is a summary of its main points. This is by no means legal advice
nor legally binding.

*Actions that you are allowed to do:*

- Use
- Share
- Modify

*If you do decide to use ANY code from the source:*

- **You must disclose the source code of your modified work and the source code you took from this project. This means
  you are not allowed to use code from this project (even partially) in a closed-source (or even obfuscated)
  application.**
- **Your modified application must also be licensed under the GPL**

## Setting up a Workspace

CrackBounce uses Gradle; to make sure that it is installed properly, you can
check [Gradle's website](https://gradle.org/install/). It also requires [Node.js](https://nodejs.org) to build the included
theme.

1. Clone this repository and its submodules using `git clone --recurse-submodules https://github.com/Casefir/CrackBounce.git`.
2. Change into the local repository (`cd CrackBounce`).
3. Run `./gradlew genSources` for a better development experience (optional).
4. Open the folder as a Gradle project in your preferred IDE.
5. Run the client with `./gradlew runClient`.

## Upstream Project

CrackBounce is derived from [CCBlueX/LiquidBounce](https://github.com/CCBlueX/LiquidBounce), which is licensed under the
GPL-3.0. Please consult the upstream repository for its history, documentation, and contribution guidelines.

## Additional libraries

### Mixins

Mixins can be used to modify classes at runtime before they are loaded. CrackBounce uses them to inject code into the
Minecraft client. This way, none of Mojang's copyrighted code is shipped. To learn more, see the
[Mixin documentation](https://docs.spongepowered.org/5.1.0/en/plugin/internals/mixins.html).

## Contributing

Contributions to CrackBounce are welcome. Feel free to open an issue or submit a pull request in this repository.

## Stats

![Alt](https://repobeats.axiom.co/api/embed/ad3a9161793c4dfe50934cd4442d25dc3ca93128.svg "Repobeats analytics image")

## Attribution

CrackBounce is a fork of LiquidBounce by CCBlueX. **Made by Casefir.**
