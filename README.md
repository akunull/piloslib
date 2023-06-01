# Pilos Lib
![PilosLib logo](https://akunull.com/pilosliblogo.jpeg)

## Description
Multi-platform open-source library of audio and modulation tools that focus on synthesis, live electronic music, interconnection, probability, unique sounds, and intuitive interfacing built by Akunull in Pure Data starting in 2014.

## Required
[Pure Data](https://puredata.info)

## Recommended skills
Basic Pure Data

Basic electronic music concepts

## Getting Started
See intro.pd in root folder or watch the [intro video](https://www.youtube.com/watch?v=Mv9c8uUxwkk). You must have the objects in plate.pd to use the library.

## What is in the library
Vanilla only patches without expr(~) editable in pd

Syntactic sugar to make Pure Data programming more efficient

Several ways to make complex rhythms and a global clock to guide it

A save and load system with preset management

A way to handle per voice modulation for synthesizers

Unique modulators for control

Tools for generative design

Model-(View)-Controller programming architecture

An assortment of synths and audio effects capable of some classic sounds and many strange ones

## Ideas behind the library
Readable, encapsulated code with intuitive interfacing and ease of use in mind

Simple code, commenting, and intro tutorial instead of help files

Portability through naming conventions and no externals


## Synths
**rhine**-2 osc synth with 2 filters and mhx modulation system 

**sentinel**-2 osc synth with variable pole lp/bp filter and mhx modulation system 

**imp**-2 osc synth with a lot of linkage to exponential envelopes and mqu modulation system. Built around synthesizing drums 

**ajah**-3 osc synth with fm interconnection between them and mhx modulation system 

**osciano**-Simplest synth, one oscillator

**nbd**-Simple bass drum synth 

**rhibd**-Simple bass drum synth with complex per voice modulation (mhx) 

**rewbd**-Bass drum synth with more saturation options

**ncym**-Simple cymbal synth

**nhh**-Simple hi-hat synth

**nsn**-Simple snare synth

## Audio Effects
**asym_tanh**-Asymmetry and tanh(x) for non-linear compression, distortion, tape-like saturation

**bellmid_3band**-3 band eq with tanh(x) (non-linear compressor) with the middle channel also including the low and high

**eq_3band**-3 band eq

**eq_3band_tanh**-3 band eq with tanh(x) (non-linear compressor) on each band

**bit_red**-Bit reduction

**bp_mix**-bandpass filter with dry/wet mixing controls

**lop_mix**-lowpass filter with dry/wet mixing controls

**hip_mix**-hipass filter with dry/wet mixing controls


**vcf_mix**-bandpass filter with dry/wet mixing controls

**vcf_np**-vcf (bandpass filter) with variable amount of poles

**vcf_npnp**-vcf~ (“voltage controlled” filter) with variable amount of poles and variable “low-pass” or band-pass

**vcf_npnp_mix**-vcf~ (“voltage controlled” filter) with variable amount of poles and variable “low-pass” or band-pass with dry/wet mixing controls

**multi_vcf**-vcf_npnp~ or bob~

**multi_vcf_mix**-vcf_npnp~ or bob~ with dry/wet mixing controls

**formant_filter**-Formant (vowel) filter with 5 formants

**formant_filter_3v**-Formant (vowel) filter with 3 formants

**delay_extfb**-Delay with external feedback so you can customize the delay line

**delay_ms**-Simple delay

**delay_ms_pitch**-Simple delay with pitch shifting in the feedback loo

**pitch_shift**-Pitch shift via phase vocoding

**downsample**-Down-sample

**retrig**-Retrigger/stutter/buffer/beat repeat

**retrig_ij**-Retrigger with multiple rates inspired by Instajungle

**tanhx**-Tanh(x), a non-linear compressor capable of emulating a lot of saturation and distortion

**vverb**-Reverb via freeverb algorithm

Latest version: [Github.com/akunull](https://github.com/akunull)

[Akunull.com](https://Akunull.com)
![Logo](https://akunull.com/akunulllogo.jpeg)