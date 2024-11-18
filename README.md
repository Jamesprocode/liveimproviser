# 🎸 Interactive Improv Companion 🎹
Welcome to the *Interactive Improv Companion*! This software is your virtual jam partner, perfect for solo musicians who want to up their improv game. Built in MAX/MSP, it’s here to create genre-savvy backing tracks, generate melodies, and jam along with you in style. 

## 🎶 What does it do?
You give it the vibe (genre, tempo, chords), and it brings the band. The software auto-generates a rhythm section with drums, keyboard, and bass, and makes sure these instruments play with the style and feel you choose. Plus, it doesn't just stop there—two melody generation options help keep things fresh and give you a variety of improvisational flavors.

### Melody Generators
1. **Probability Model** 🎲 – Ever wish you had a bandmate that was predictable... but in a good way? This model uses a fixed probability system to create melodies that align with the chord changes in the backing track. It sticks to notes that fit, so you get some harmonic guidance on what works with the current chords. Great for practicing how to follow the harmony!
   
2. **Markov Chain Magic** 🧙 – A step up in complexity, this one gets personal! Play along using your MIDI keyboard, and let the software learn your unique playing style. Over time, it’ll pick up on the way you transition between notes and the rhythms you prefer. Then, once trained, it can generate melodies that *sound like you*—a personalized improv partner, right at your fingertips!

## 🎛️ Customize Your Sound
Melody playback is powered by a custom synthesizer with loads of tweakable parameters:
- **Overtone Control**: Adjust individual volumes for a rich harmonic feel.
- **ADSR Envelope**: Control Attack, Decay, Sustain, and Release to shape your sound.
- **Filter Settings**: Customize the filter for a unique vibe, from warm to edgy.

## 🥁 Drum Samples and Chord Files
- **Drums**: A drum sample is provided, but you’ll need to manually select it in MAX/MSP. This lets you choose your ideal drum sound to match the vibe you’re going for.
- **Chords and Bass**: The chords and bass parts connect to the Ableton file provided. Just load in the TXT files with all the chords and chord qualities, and you’re ready to roll!

## 🚀 Getting Started
1. **Download & Install**: Clone this repo, open the project in MAX/MSP, and hit play.
2. **Input Your Track Details**: Choose genre, set tempo, and add your chord progressions.
3. **Jam On**: Grab your MIDI controller or let the melody generators take the lead. You can switch between Probability and Markov Chain modes on the fly.

## 🥁 FAQ

**Q: Is this for beginners or advanced musicians?**  
A: It’s for everyone! Beginners can learn by example, and advanced players can explore unique sounds and styles. 

**Q: Can I save the generated melodies?**  
A: Yep, just hit “Save” in MAX/MSP, and you can save the MIDI for your next gig or practice session.

## 🌈 Contribute
Got an idea to make this even better? Fork it, add your magic, and submit a PR! 

Get creative, experiment, and have fun! This software is here to help you dive into the art of improv with a little help from a virtual band that always has your back.
