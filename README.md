# AI Colors Engine

The AI Colors Engine is a simple tool that generates color palettes in HEX format based on text descriptions. It uses  penAI's text-davinci-003 model.
The AI model can generate palettes with 2 to 8 colors that fit the theme, mood, or instructions provided in the prompt.

## Requirements

- Python ^3.11
- Poetry ^1.4.0

## Installation

1. Clone the repository and navigate to the project directory.

```
git clone git@github.com:sdevgill/ai-colors-engine.git
cd ai-colors-engine
```

2. Install the requirements.

```
poetry install
```

3. Activate the virtual environment.

```
poetry shell
```

4. Run the application.

```
cd server
flask run --debug
```

## Features

- Generate color palettes from simple text descriptions.
- Output palettes with 2 to 8 colors in HEX format.
- AI model trained on diverse sources for accurate and creative color generation.
- Easy-to-use interface for quick palette generation.

## Usage

1. Provide a text description of the color palette you want to generate.
2. The AI model will generate a color palette based on the provided description.
3. The generated color palette will be displayed in HEX format.

## Examples

Input:
```

Generate a color palette for a calm and relaxing beach scene.

```

Output:
```

# D9E4F5 #3A7CA5 #7EBDC2 #F2D1B3 #F0EFEA

```

## Tips

- If you have a specific starting color in mind, include it in your description.
- Describe the mood or theme you want the palette to convey.
- Experiment with different descriptions to generate a variety of palettes.

## License

The AI Colors Engine is released under the MIT License.
