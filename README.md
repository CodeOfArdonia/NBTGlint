# NBT Glint

This is a client side, nbt powered mod for colorful item glint

## Usage

There are 2 keys to control glint rendering.

- `glint`: Control the color. Available colors:
[GlintManager.java](https://github.com/CodeOfArdonia/NBTGlint/blob/master/common/src/main/java/com/iafenvoy/glint/render/GlintManager.java)

- `glint_always`: Whether it should always render glint

### Example

A diamond sword with red glint: `/give @s diamond_sword{"glint":"red","glint_always":true}`

<div align=center><img src="https://raw.githubusercontent.com/CodeOfArdonia/NBTGlint/refs/heads/master/img/1.webp" style="width:400px;text-align:center;" alt=""></img></div>