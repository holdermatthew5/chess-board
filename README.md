**Author:** Matthew Holder
**Version:** 0.1.0

[PR]()

Problem Domain:

    I would like a 1980's style pixel art chess board with a red queen and a blue queen. I would like to be able to change the position of my queens and know when one is under attack. I should be able to render the readied board.

Description:

    Board - Class for creating 8x8 chess boards.
      - add_red - adds a red queen to the designated (x, y) coordinates of the chess board.
      - add_blue - adds a blue queen to the designated (x, y) coordinates of the chess board.
      - render - renders prepaired board onscreen.
      - is_under_attack - Returns true if the blue queen is on the same horizontal, vertical or 45 degree line as the red queen and false if not.