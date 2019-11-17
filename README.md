# POWERLINE SLOTMACHINE

A toy [Powerline](https://powerline.readthedocs.io/en/master/) segment. This segment shows a slotmachine.

By [Miguel de Dios Matias](https://github.com/mdtrooper).

## Installation

### Using pip

```
pip install powerline-slotmachine
```

## Configuration

You can activate the Powerline Slotmachine segment by adding it to your segment configuration,
for example in `.config/powerline/themes/shell/default.json`:

```json
{
    "function": "powerline_slotmachine.slotmachine",
    "priority": 90
}
```

But the Powerline Slotmachine store the last combination and money amount in `<home>/.config/powerline_slotmachine.json`.


## Usage

Only execute something in the prompt and the slotmachine will bet.

The bet is 1 coin. The user starts with 10 coins.

![screenshot](https://raw.githubusercontent.com/mdtrooper/powerline_slotmachine/master/powerline_slotmachine.jpg "Screenshot")

### Combinations

Slot   | Prize
------ | ----
🍇🍇🍇 | 1
🍋🍋🍋 | 2
🍉🍉🍉 | 4
🍒🍒🍒 | 15
⭐⭐⭐ | 100
XX🍒 | 5
X🍒🍒| 10

## License

Licensed under [the GPL3 License](https://github.com/mdtrooper/powerline_slotmachine/blob/master/LICENSE).


