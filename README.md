# Minimal design system by Alex Woo

Design guidance, tokens, references, and working examples for coding assistants.
Built for the workflow shared at [ajwoo.com](https://www.ajwoo.com/).
Star this repository to bookmark it and follow its development.

## Use it

Open your project in your coding tool. Ask it to read this repository’s SKILL.md
and relevant reference, token, and example files, then apply the system to your
requested scope. Start with shared components and work in reviewable batches.
You do not need an AJWOO account or Figma access.

Clone or download the entire repository to preserve relative file paths.
For persistent reuse, optionally install the complete folder into your coding
tool’s skills directory. Installation is optional and does not guarantee automatic
invocation. Do not overwrite an existing installation without reviewing changes.

## Compatibility and recovery

The runnable examples are HTML/CSS; the Tailwind preset targets version 3.4.
Native iOS, React Native, and Flutter require platform-specific adaptation;
this repository does not contain tested native component implementations.
Preserve Dynamic Type, screen-reader support, native navigation, and reduced motion.

Save a recoverable checkpoint first. Review and test changes before publishing.
Ask your coding tool to explain how to undo only its changes. Do not reset or
remove unrelated work. If network access is unavailable, attach the complete
folder or use the self-contained download on ajwoo.com.

## Files

- `SKILL.md`: workflow and design rules
- `reference/`: component, motion, accessibility, and setup guidance
- `tokens/`: CSS variables, JSON tokens, Tailwind 3.4 preset
- `examples/`: runnable HTML/CSS component example
- `LICENSE-AND-ASSETS.md`: existing asset and usage notes

Font binaries and Figma component libraries are not included.
