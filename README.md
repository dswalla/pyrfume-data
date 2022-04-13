# The Pyrfume Public Data Archive
## Wrangled, pre-processed, and curated olfactory psychophysics data.

![pyrfume-logo](https://avatars.githubusercontent.com/u/34174393)

Intended for use with the `pyrfume` Python library:
```console
pip install pyrfume
```

Examples:
```python
import pyrfume
```
followed by e.g.:

```python
# Load all the data from Bushdid et al, 2014 ("Humans Can Discriminate More than 1 Trillion Olfactory Stimuli")
molecules = pyrfume.load_data('bushdid_2014/molecules.csv')
mixtures = pyrfume.load_data('bushdid_2014/mixtures.csv')
behavior = pyrfume.load_data('bushdid_2014/behavior.csv')
```
or e.g.:

```python
# Load all the data from Snitz et al, 2013 ("Predicting Odor Perceptual Similarity from Odor Structure")
molecules = pyrfume.load_data('snitz_2013/molecules.csv')
behavior = pyrfume.load_data('snitz_2013/behavior.csv')
```

Analogous examples can be found [here](code_examples.py) for other datasets.

## Current inventory:
[![abraham_2012](https://img.shields.io/static/v1?label=&nbsp;&message=abraham_2012&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<threshold>](https://img.shields.io/static/v1?label=data&message=threshold&color=ff0000)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![arctander_1960](https://img.shields.io/static/v1?label=&nbsp;&message=arctander_1960&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![aromadb](https://img.shields.io/static/v1?label=&nbsp;&message=aromadb&color=eeeeee)](#) <br>[![arshamian_2022](https://img.shields.io/static/v1?label=&nbsp;&message=arshamian_2022&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=ffa256)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![bushdid_2014](https://img.shields.io/static/v1?label=&nbsp;&message=bushdid_2014&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![davison_2007](https://img.shields.io/static/v1?label=&nbsp;&message=davison_2007&color=eeeeee)](#) <br>[![dravnieks_1985](https://img.shields.io/static/v1?label=&nbsp;&message=dravnieks_1985&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![goodscents](https://img.shields.io/static/v1?label=&nbsp;&message=goodscents&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![haddad_2008](https://img.shields.io/static/v1?label=&nbsp;&message=haddad_2008&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![ifra_2019](https://img.shields.io/static/v1?label=&nbsp;&message=ifra_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![keller_2012](https://img.shields.io/static/v1?label=&nbsp;&message=keller_2012&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=9cfaa3)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=ffa256)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<threshold>](https://img.shields.io/static/v1?label=data&message=threshold&color=ff0000)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![keller_2016](https://img.shields.io/static/v1?label=&nbsp;&message=keller_2016&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=9cfaa3)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=ffa256)](#) [![<familiarity>](https://img.shields.io/static/v1?label=&nbsp;&message=familiarity&color=4756fb)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![leffingwell](https://img.shields.io/static/v1?label=&nbsp;&message=leffingwell&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![ma_2021](https://img.shields.io/static/v1?label=&nbsp;&message=ma_2021&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=9cfaa3)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=ffa256)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=0fa2ef)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![mainland_2015](https://img.shields.io/static/v1?label=&nbsp;&message=mainland_2015&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=62fac3)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![manoel_2021](https://img.shields.io/static/v1?label=&nbsp;&message=manoel_2021&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![mayhew_2022](https://img.shields.io/static/v1?label=&nbsp;&message=mayhew_2022&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![nat_geo_1986](https://img.shields.io/static/v1?label=&nbsp;&message=nat_geo_1986&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![optical_rotation](https://img.shields.io/static/v1?label=&nbsp;&message=optical_rotation&color=eeeeee)](#) <br>[![ravia_2020](https://img.shields.io/static/v1?label=&nbsp;&message=ravia_2020&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=0fa2ef)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![scott_2014](https://img.shields.io/static/v1?label=&nbsp;&message=scott_2014&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![sigma_2014](https://img.shields.io/static/v1?label=&nbsp;&message=sigma_2014&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) <br>[![snitz_2013](https://img.shields.io/static/v1?label=&nbsp;&message=snitz_2013&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=0fa2ef)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![snitz_2019](https://img.shields.io/static/v1?label=&nbsp;&message=snitz_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=9cfaa3)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=2adcdc)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=ff562b)](#) <br>[![wakayama_2019](https://img.shields.io/static/v1?label=&nbsp;&message=wakayama_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=d4dc7f)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=9cfaa3)](#) <br>
