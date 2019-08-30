# TrumBela
PureData Fx pedal for Bela

The Trum bela is ourfirst hardware/.software project using the Bela and Pure Data. It is a single use device with no display other than 8 led.

![Layout](http://wiki.emc23.com/images/thumb/7/77/TrumBela.gif/450px-TrumBela.gif "layout")


Tr-umBela an FX box for the Roland TR 8 based on ther Fx above. The assignable A and B outputs are used as sends and the mix in is used as returns. Specifically built for the toms, rimshot and Clap but any of the voices can be assigned to Mix out, A or B as usual.
TrumBela.gif

![TrumBela](http://wiki.emc23.com/images/5/55/Tr-8-back.jpeg "TrumBela")

    https://guitarextended.wordpress.com/2011/12/12/creating-a-simple-effect-with-pd/ Creating a simple delay effect
    https://guitarextended.wordpress.com/2011/12/28/simple-fuzz-effect-with-pure-data/ Simple Fuzz effect
    https://guitarextended.wordpress.com/2011/12/28/phaserchorus-effect-with-pure-data/ Phaser/Chorus effect
    https://guitarextended.wordpress.com/2012/01/03/tremolo-effect-with-pure-data/ Tremolo effect
    https://guitarextended.wordpress.com/2012/01/06/simple-monophonic-fm-synthesizer-with-pure-data/ Simple monophonic FM synthesizer
    https://guitarextended.wordpress.com/2012/01/07/vibrato-with-pure-data/ Vibrato
    https://guitarextended.wordpress.com/2012/01/07/wha-wha-auto-with-pure-data/ Wha-wha (auto)
    https://guitarextended.wordpress.com/2012/01/18/step-vibrato-effect-for-guitar-with-pure-data/ Step-vibrato effect for guitar
    https://guitarextended.wordpress.com/2012/01/24/reverb-effect-in-pure-data/ Reverb Effect
    https://guitarextended.wordpress.com/2012/02/06/ring-modulator-effect-using-pure-data/ Ring modulator effect
    https://guitarextended.wordpress.com/2012/02/07/spectral-delay-effect-for-guitar-with-pure-data/ Spectral Delay effect for guitar
    https://guitarextended.wordpress.com/2012/03/05/guitar-effects-chain-with-pure-data/ Guitar effects chain
    https://guitarextended.wordpress.com/2012/04/04/polyphonic-synth-using-phase-vocoder-in-pure-data/ Polyphonic synth using phase vocoder
    https://guitarextended.wordpress.com/2012/04/10/reversed-tape-violin-effect-for-guitar-with-pure-data/ Reversed tape / Violin effect for guitar
    https://guitarextended.wordpress.com/2012/07/08/detuning-delay/ Detuning delay
    https://guitarextended.wordpress.com/2012/07/10/thehexxciter-detuning-reverb-better/ TheHexxciter
    https://guitarextended.wordpress.com/2013/08/05/making-a-looper-with-pure-data/ Looper
    
    
I hve removed the dac~ and adc~ from each of the tutorial fx units and replaced them with inlets and outlets. This allows me to use them as modules in the master pedal board.

I can now add  8 faders and 8 switches. In order to have some control we are limited to 3 fx by two inputs equals siz volume knobs, six on/of buttons and 6 leds.

That leaves us with two knows and two buttons that can act as toggles to access more functinality. Press Button 1 to access fx, button two to access fx 2 and both buttons to access fx three.

The main six volumes could ne default if no button is pressed and act as futher contrls for the fx too.


