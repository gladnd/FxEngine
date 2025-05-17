FxEngine Framework Copyright (C) 2005-2012 Sylvain Machel, SMProcess.

FxEngine Framework Contents:
============================

Doc/ ....Contains the FxEngine Framework documentation in PDF format.
Bin/ ....Contains the FxEngine Framework Library files, samples and the FxEngine Editor application.
	VcX/ ....Where X is the Win32 Runtime version (e.g. 8, 9, ...) 
Include/ ...Contains FxEngine Framework include files for FxEngine core and FX's components.
Lib/ ....Contains FxEngine Framework library files for FxEngine core and FX's components.
	VcX/ ....Where X is the Win32 Runtime version (e.g. 8, 9, ...) 
Samples/ ....Contains all samples code. Sample binaries are copied in bin directory.
	FxPcmEcho/ ....(Win32 only) The Fx Echo mixes a delayed copy of the original PCM waveform back
                into the PCM waveform.
	FxBmpSrc/ ....(Win32 only) The Fx Bmp source loads a bmp file and creates a 24 bits RGB array 
   				on its output pin. 
	FxRGBrlSplitter/ ....(Win32 only) The Fx RGB RL splitter allows to cut a 24 bits RGB array to Right and Left images. 
	FxRGBRnd/ ....(Win32 only) The Fx RGB renderer allows to show in window a 24 bits RGB array on its input pin. 
	FxNullRnd/ ....The Fx Null renderer illustrates the simplest renderer Fx.
	FxHelloWorldSrc/ ....The Fx HelloWorld source sends "Hello World" text on its output pin. 
	FxSndFileSrc/ ....(Linux only) The Fx Sound File source reads sound data from file and sends PCM data on its output pin.
				  this Fx uses the libsndfile library from Erik de Castro Lopo. See http://www.mega-nerd.com/libsndfile
	FxPcmGain/ ....(Linux only) The Fx Pcm Gain applies a gain on sound data from its input pin. 
	FxLADSPA/ ....(Linux only) This Fx is a LDSPA wrapper. It allows to load most of popular LADSPA plugins. 
	FxWavFileRnd/ ....vThe Fx wave File renderer get pcm data on its input pin and creates a wav file.
				This Fx uses the libsndfile library from Erik de Castro Lopo. See http://www.mega-nerd.com/libsndfile
	FxAlsaRnd/ ....(Linux only) This Fx is an audio renderer. It allows to play audio stream using Alsa sound driver. 
	FxMToS/ ....(Linux only) This Fx transforms its input audio stream (Mono or Stereo) to a stereo audio stream. 
	FxSToM/ ....(Linux only) This Fx transforms its input audio stream (Mono or Stereo) to a mono audio stream. 	
	FxSToMSplitter/ ....(Linux only) This Fx transforms its input audio stream (Mono or Stereo) to two mono audio streams.
	FxMToSMerger/ ....(Linux only) This Fx transforms its both input audio streams (Mono or Stereo) to one stereo audio streams.		
    	FxMsgSrc/ ....(Win32 only) The Fx Message source shows how to use the Microsoft Winform to create Fx dialog. This Fx get user 
				message and send it to its output pin.
	PlaySound/ ....(Win32 only) The PlaySound sample shows how to load, modify and play a wave
  				file using 3 FXs (source Fx, process Fx and renderer Fx).
