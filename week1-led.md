

# My First LED Strip Experiment

## Step 1: Download Tools 
Before you start on your first experiment, let's download some tools.
Go to the Advanced drawer and press ``||Advanced:Extentions||``. Search and click on the 'neopixel' extention.



```blocks
let strip = neopixel.create(DigitalPin.P0, 30, NeoPixelMode.RGB)
basic.forever(function () {
    strip.showColor(neopixel.colors(NeoPixelColors.Red))
    basic.pause(1000)
    strip.showColor(neopixel.colors(NeoPixelColors.Blue))
    basic.pause(2000)
})
```

