# Honor in Law

A Russian-language visual novel built with [Ren'Py](https://www.renpy.org/). It follows police officers through everyday work and unusual adventures in a fictional city. Each chapter parodies a different genre.

The published project contains **three chapters**. This is a personal narrative game: the dialogue and story are in Russian.

## Preview

<img width="1440" alt="Honor in Law gameplay preview" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/dfefa893-5c01-4474-b366-13759fd573a0">

<details>
<summary>More screenshots</summary>

<img width="1440" alt="Honor in Law screenshot 2" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/f3213dca-f6f3-45ca-a806-95134936b916">

<img width="1440" alt="Honor in Law screenshot 3" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/391f0d6f-f492-4568-9ba5-0f7413341b6d">

<img width="1440" alt="Honor in Law screenshot 4" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/720e65a7-d038-49b0-b9ae-efec6db3dc40">

<img width="1440" alt="Honor in Law screenshot 5" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/4ba4f224-145e-4d0d-b1cc-56ae0a70f2d9">

<img width="1440" alt="Honor in Law screenshot 6" src="https://github.com/andreystashev/VisualNovelTemplate/assets/70208784/ac3855d7-12c3-4a08-b291-2e87c64dd41b">

</details>

## Run from source

1. Install the [Ren'Py SDK](https://www.renpy.org/).
2. Clone this repository:

   ```sh
   git clone https://github.com/andreystashev/honor-in-law.git
   cd honor-in-law
   ```

3. Open the Ren'Py launcher. In **Preferences**, set **Projects Directory** to the parent directory of this checkout.
4. Select **Honor in Law** and choose **Launch Project**.

The SDK provides the Python runtime; a separate `pip install` step is not needed. See the official [Ren'Py quickstart](https://www.renpy.org/doc/html/quickstart.html) for launcher setup and packaging.

The committed runtime log records **Ren'Py 8.3.7**. Compatibility with newer engine versions has not been verified.

## Project structure

| Path | Purpose |
| --- | --- |
| `game/script.rpy` | Story and dialogue |
| `game/screens.rpy` | Interface screens |
| `game/gui.rpy` | GUI configuration |
| `game/options.rpy` | Game name, version and build settings |
| `game/images/` | Visual assets |
| `game/audio/` | Audio assets |
| `game/tl/` | Translation-related files |

## Development status

The repository also contains legacy runtime logs, compiled scripts, cache and save files. These are development artifacts; the editable game sources are the `.rpy` files.

The screenshots show the game interface. This README update does not establish a tested packaged release or a fresh engine compatibility check.
