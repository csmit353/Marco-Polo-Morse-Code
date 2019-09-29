# Marco-Polo-Morse-Code
## Marco Polo: radio.onReceivedString(function (receivedString) {
    basic.showString(receivedString)
})
input.onButtonPressed(Button.A, function () {
    radio.sendString("Marco")
})
input.onButtonPressed(Button.B, function () {
    radio.sendString("Polo")
})
radio.setGroup(1)
basic.showLeds(`
    # . # # #
    # # # # #
    # . # # #
    # . # # .
    # . # # .
    `)
