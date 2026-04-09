# AoE2DE UI Layout Editor

A visual editor for **Age of Empires II: Definitive Edition** UI layout files.

Latest version:  
https://jonasbl3.github.io/AoE2DE-UI-editor/

## About

This project was made to make editing AoE2DE UI elements easier than working directly in raw `.json` files.

The game UI is built from layout files in the `widgetui` folder, but the way the game reads and behaves with these files is not always obvious. Because of that, this editor helps a lot, but some trial and error is still part of the process.

## Current state

This is still an unfinished project.

It is already useful, but some behavior is still rough, some parts are experimental, and not everything is fully explained inside this repository. You may need to figure some things out as you go.

I may continue development, or I may leave it as-is.

## Purpose

The goal of this editor is to make AoE2DE UI modding and layout editing:

- more visual
- faster to iterate on
- easier to understand
- less frustrating than editing JSON by hand

## Notes

Some UI behavior is controlled by the game itself, so the editor cannot always preview everything perfectly.

In practice, this means:

- some elements behave in odd or engine-specific ways
- some layouts still need in-game testing
- graphics and layout do not always update the same way

## Graphics

Besides editing layout files, you may also want to edit the UI graphics.

The game reads many graphics on startup, so image changes usually require restarting the game before they appear correctly.

## Example content

An example mod may also be included here as a reference.

It is not guaranteed to stay updated, but it can still be useful for learning how the app and the game files work.

## Project background

This tool was built with heavy help from ChatGPT during development.

## Final note

This project exists to make AoE2DE UI editing more accessible and practical.

It is not perfect, but it can save a lot of time if you are willing to experiment a bit.
