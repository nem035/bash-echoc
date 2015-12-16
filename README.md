# echoc
Bash function allowing echo-ing strings in different colors and formats

## Usage

The first argument to the function describes the format of the text and the second argument is the actual text.

##### Color shortcodes:

- Black   - `black`, `bk`
- Red     - `red`, `r`
- Green   - `green`, `g`
- Yellow  - `yellow`, `y`
- Blue    - `blue`, `b`
- Purple  - `purple`, `p`
- Cyan    - `cyan`, `c`
- Gray    - `gray`, `gy`

##### Effect shortcodes (prepend to color code)

- Bold               - `bold`, `b`
- Underline          - `under`, `u`
- Background         - `bg`
- Intense            - `intense`, `i`
- Bold Intense       - `bintense`, `bi`
- Background Intense - `bgintense`, `bgi`

Sample:

![Hello World](https://raw.githubusercontent.com/nem035/bash-echoc/master/hello_world.png)

If you want to use echoc in your scripts, add echoc.sh to the same directory as your scripts.

Then you can just add the following line to the begining of the script to include echoc:

`source $(dirname $0)/echoc.sh`

## All Effects

![All Effectss](https://raw.githubusercontent.com/nem035/bash-echoc/master/all_effects.png)
