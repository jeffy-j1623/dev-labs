# 🎨 CSS Background Properties

## 🎯 Purpose
CSS background properties are used to control the background color, image, positioning, and behavior of an element’s background. They play a crucial role in enhancing the design and layout of a webpage.

---

## 📌 Core Elements

| **Property**              | **Description**                            |
|---------------------------|--------------------------------------------|
| `background-color`      | Sets background color.                     |
| `background-image`      | Adds background image.                     |
| `background-repeat`     | Repeats or stops image repetition.         |
| `background-position`   | Sets image start position.                 |
| `background-size`       | Defines image size (e.g., cover, contain). |
| `background-attachment` | Scrolls or fixes background image.         |
| `background-origin`     | Sets positioning area.                     |
| `background-clip`       | Controls how far background extends.       |
| `background`            | Shorthand for all background properties.   |


- ### `background-color`

| **Value**       | **Description**                                      |
|-----------------|------------------------------------------------------|
| color name      | Named colors like `red`, `blue`, `lightgreen`        |
| #hex            | Hexadecimal color codes (e.g., `#ffffff`, `#000000`) |
| rgb()           | RGB color format (e.g., `rgb(255, 0, 0)`)          |
| rgba()          | RGB with alpha transparency                          |
| hsl()           | Hue, Saturation, Lightness format                    |
| hsla()          | HSL with alpha transparency                          |
| transparent     | Fully transparent background                         |
| inherit         | Inherits from parent                                 |
| initial         | Sets to default value                                |
| unset           | Removes applied value (acts as inherit/initial)      |


- ### `background-image`
| **Value**                     | **Description**                                     |
|------------------------------|-----------------------------------------------------|
| none                         | No background image (default)                       |
| url("image.jpg")             | Loads background image from given path              |
| linear-gradient(...)         | Creates a linear gradient background                |
| radial-gradient(...)         | Creates a circular/elliptical gradient              |
| repeating-linear-gradient()  | Repeats linear gradient pattern                     |
| repeating-radial-gradient()  | Repeats radial gradient pattern                     |
| multiple urls                | Layer multiple images: `url(a.jpg), url(b.jpg)`     |

- ### `background-repeat`
| **Value**    | **Description**                                      |
|--------------|------------------------------------------------------|
| repeat       | Repeats horizontally and vertically (default)        |
| no-repeat    | Shows the image only once                            |
| repeat-x     | Repeats image horizontally only                      |
| repeat-y     | Repeats image vertically only                        |
| space        | Distributes image with space between repeats         |
| round        | Resizes image to fit perfectly without cropping      |

- ### `background-position`

| **Value**         | **Description**                                   |
|------------------|---------------------------------------------------|
| left / center / right | Horizontal alignment keywords               |
| top / center / bottom | Vertical alignment keywords                 |
| x y values        | Specific offsets like `20px 30px`, `50% 50%`      |
| combinations      | Any valid combo like `right bottom`, `center top`|

- ###  `background-size`

| **Value**  | **Description**                                          |
|------------|----------------------------------------------------------|
| auto       | Default image size                                       |
| cover      | Fills entire element (may crop)                          |
| contain    | Scales image to fit without cropping                     |
| length     | Fixed size (e.g., `100px 200px`)                         |
| percentage | Relative to element (e.g., `50% 50%`)                    |

- ### `background-attachment`

| **Value** | **Description**                                          |
|-----------|----------------------------------------------------------|
| scroll    | Scrolls with page (default)                              |
| fixed     | Background stays fixed when page scrolls                 |
| local     | Scrolls with the content of the element                  |

- ### `background-origin`

| **Value**     | **Description**                                      |
|---------------|------------------------------------------------------|
| padding-box   | Background starts from padding edge (default)        |
| border-box    | Starts from border edge                              |
| content-box   | Starts from content edge                             |

---

- ### `background-clip`

| **Value**     | **Description**                                      |
|---------------|------------------------------------------------------|
| border-box    | Extends background to border edge                    |
| padding-box   | Clips background at padding edge                     |
| content-box   | Clips background at content edge                     |
| text          | Clips background to text (requires `-webkit-clip`)   |

---
## 🔑 Summary
- Use `background` shorthand for cleaner code.
- Set a `background-color` as fallback.
- Use `background-size: cover;` for full image coverage.
- Set `background-repeat: no-repeat;` to avoid tiling.
- Use `background-position: center;` for alignment.
- Apply `background-attachment: fixed;` for parallax effect.

---

⏭️ **Next:** Lets Explore about CSS Dimensions.