# Euroscope Setup

Contains instructions for custom actions after full HvACC sector file update for LGGG / LCCC.

## Aliases

Add the `alias.txt` file contents on top of the `alias.txt` file that came with the full package.

## Display Settings

<img width="356" height="296" alt="image" src="https://github.com/user-attachments/assets/2c03c870-b691-42d7-9776-f4b88ab0a2ab" />

**Change to 350 only for APP/CTR ASRs**

## Symbology Settings

Symbology text file is included in the repo.

Below settings are saved in the General settings file. Change the settings manually from their default values.

<img width="548" height="174" alt="image" src="https://github.com/user-attachments/assets/011f374c-feb4-4c44-87ca-67f7417d6c5e" />


## Profile file

### Add this to the .prf file for LGGG/LCCC

Be sure to replace the existing lines

```
ASRFastKeys	1	LGGG\ASR\Radar Service ASR\LGAV_GND_NEW.asr
ASRFastKeys	3	LGGG\ASR\Radar Service ASR\LGAV_APP.asr
ASRFastKeys	4	LGGG\ASR\Radar Service ASR\LGGG_GND.asr
ASRFastKeys	5	LGGG\ASR\Radar Service ASR\LGGG_APP.asr
ASRFastKeys	6	LGGG\ASR\Radar Service ASR\LGGG_CTR.asr
```
The fast keys should appear like this , in the settings:
<img width="746" height="317" alt="image" src="https://github.com/user-attachments/assets/233cbedf-1d22-4720-b2af-257741bc23aa" />


```
LastSession	connecttype	0
LastSession	facility	5
LastSession	rating	4
LastSession	tovatsim	1
LastSession	range	150
LastSession	proxyserver	localhost
LastSession	simdatapublish	0
LastSession	callsign	LGAV_W_APP
LastSession	realname	Elias Stassinos
LastSession	certificate	xxxxxx
LastSession	password	xxxxxx
LastSession	server	AUTOMATIC
LastSession	atis2	Athinai Arrival
LastSession	atis3	ATIS on 136.125 - Charts on briefing.hvacc.org - Coverage at vats.im/gr/sectormap
LastSession	atis4	Feedback on vats.im/gr/atcfb
```

## Hoppie

Add HOPPIE code to `TopSkyCPDLChoppiecode.txt` file
