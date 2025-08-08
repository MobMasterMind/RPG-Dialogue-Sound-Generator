# RPG Dialogue Sound Generator

A web tool that transforms any audio sample into RPG-style dialogue talking sounds.  
Perfect for game developers and audio creators who want to generate seamless looping dialogue clips or varied pitch-shifted speech effects for RPGs and other games.

## Features

- Import audio samples in formats like WAV, FLAC, OGG, MP3, and others supported by your browser.
- Trim audio by specifying start and end times.
- Create smooth looping dialogue sounds with adjustable loop length and loop delay.
- Generate multiple pitch-shifted variations for diverse dialogue effects.
- Live preview with pitch randomization options.
- Download single audio loops or a ZIP archive of multiple pitch variations.
- User-friendly interface with helpful tooltips.

## How to Use

1. Click **Import Audio File** to upload your dialogue sample.
2. Set the **Cut Start Time** and **Cut End Time** to isolate the portion of the audio you want to use.
3. Choose a mode:
   - **Loop Export:** Generate a single looping audio clip with optional loop length and delay.
   - **Generate Variations (ZIP):** Create multiple pitch-shifted variations bundled in a ZIP file.
4. Adjust the **Loop Delay**, **Pitch Variation**, and **Randomize Pitch Each Loop** settings as desired.
5. Use **Preview** and **Stop Preview** buttons to listen to your selection.
6. Click **Generate & Download** to export your audio.

## Technologies Used

- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API) for audio processing and playback.
- [Lame.js](https://github.com/zhuker/lamejs) for encoding audio to WAV.
- [JSZip](https://stuk.github.io/jszip/) for generating ZIP archives.
- HTML5, CSS3, and vanilla JavaScript.

## Author

Created with care by [MobMasterMind](https://github.com/MobMasterMind).
