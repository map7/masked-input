Masked Input Plugin for jQuery
==============================

Overview
--------
This is a masked input plugin for the jQuery javascript library. It allows a user to more easily enter fixed width input where you would like them to enter the data in a certain format (dates,phone numbers, etc). It has been tested on Internet Explorer 6/7, Firefox 1.5/2/3, Safari, Opera, and Chrome.  A mask is defined by a format made up of mask literals and mask definitions. Any character not in the definitions list below is considered a mask literal. Mask literals will be automatically entered for the user as they type and will not be able to be removed by the user.The following mask definitions are predefined:
* a - Represents an alpha character (A-Z,a-z)
* 9 - Represents a numeric character (0-9)
* * - Represents an alphanumeric character (A-Z,a-z,0-9)

Options
-------

watermark: Enter a default option or show the user what you want entered there
  $('#release_date').mask("99/99/9999", {watermark: "mm/dd/yyyy" })

disable_esc: If you use keybindings on esc through another plugin then you may want to disable ESC in masked_input, here is how:
  $('#release_date').mask("99/99/9999", {disable_esc: true })		