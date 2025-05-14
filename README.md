# Voltage-Phase-Module-beta-
Amplitude to Phase modulator. Legacied VST2 .dll plugin for Windows or Linux via Yabridge (https://github.com/robbert-vdh/yabridge)

Voltage Phase Module (beta3 6 July 2014)

Press:
https://bedroomproducersblog.com/2014/06/18/voltage-phase-module/

©AMATEUR TOOLS DSP
concept: Josh Gura

Contact information: amateurtools@gmail.com

This is a PUBLIC BETA testing release, not a final version. 

There has been a resurgence of interest in this plugin and plans are underway to emit it in vst3, possibly cross platform.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

# 'What's it do? How's it work?'-

"Voltage Phase Module" (beta3) is a 32 bit VST plugin (VST is a trademark of Steinberg GMBH)

Voltage Phase Module is an amateur quality sound manipulation tool for use in a Digital Audio Workstation such as Reaper, Cubase, Ableton, FL Studio, Renoise, and any other Windows based software that utilizes VST technology.

It has one function and purpose, to phase modulate one audio stream with another.

This means the amplitude of one signal changes the other audio signal's speed.

VPM (we'll use an acronym from now on) has four inputs.

VPM can either modulate channel 1 with channel 2 "mono mode", or in stereo mode, channels 3 and 4 modulate channels 1 and 2 respectively, and 4 channels of incoming audio are processed.

As of Beta3, there is a third algorithm that sums channels 1 and 2, as well as 3 and 4, to mono, reduces the input values by half, and allows for modulating them in 'mono mode.' There are also clear illustrations of the signal routing in each algorithm on the GUI.

There is a switch that Inverts (flips) the inputs labeled 'CAR/MOD INVERT.'

Some DAW hosts allow multichannel routing, so to get full use of the plugin, it's good to know your way around your DAW's internal routing.

The Range knob controls the range of the delay algorithm.  This knob is not designed for automation because it is noisy.  

The Amount knob allows for musical phase modulation fade-ins and fadeouts, and timbre changes, and is more suitable for automation. 

This plugin is meant for experimentation, try it on a single stereo or even mono source.
A perfect example of how to use this plugin is with 2 tracks of sine waves that change in pitch, give it a try.

-----------------------------------------------------------------------------------

changelog

13 May 2025 - Revised NFO
6 July 2014 - Mod Input Clip Indicator added, Preset/Automation names fixed.
27 June 2014 - "beta3" GUI overhaul, Third Algorithm added, more responsive 'Amount' Knob.
15 June 2014 - "beta2" reduce plugin latency artifacts, reduce cpu usage, change gui
