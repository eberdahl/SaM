Synth-A-Modeler v0.4
--------------------
July 10, 2013


It's not a synthesizer---it's a Synth-A-Modeler!



The Synth-A-Modeler compiler, enables musicians to synthesize binary DSP modules according to mechanical analog model specications. This open-source tool promotes modular design
and ease of use. By leveraging the Faust DSP programming environment, an output Pd, Max/MSP, SuperCollider, VST, LADSPA, or other external module is created, allowing the musician to hear the sound of the physical model in real time using an audio host application.




To download:
git clone https://github.com/eberdahl/SaM.git

Documentation:
http://lac.linuxaudio.org/2012/papers/34.pdf
(more soon)

To use SaM with the FireFader, see:
https://ccrma.stanford.edu/wiki/SynthAModelerFireFaderLab





After you install git, you can just run

    git clone https://github.com/eberdahl/SaM.git

to download Synth-A-Modeler into a new directory.  Then go into that directory by typing
cd SaM
Then try to use the Make command as if you were using Faust to build the Synth-A-Modeler modules.  Currently the following targets are supported:

    make puredata

    make map

    make jackqt


otherwise you will have to create your own Makefiles from the Faust examples (see Makefile.HOWTO.txt).
