+++
title = "NeurIPS Workshop on Bayesian Decision-making and Uncertainty"
+++

# Abstract

In recent years, the growth of decision-making applications, where principled handling of uncertainty is of key concern, has led to increased interest in Bayesian techniques.
By offering the capacity to assess and propagate uncertainty in a principled manner, Gaussian processes have become a key technique in areas such as Bayesian optimization, active learning, and probabilistic modeling of dynamical systems.
In parallel, the need for uncertainty-aware modeling of quantities that vary over space and time has led to large-scale deployment of Gaussian processes, particularly in application areas such as epidemiology.
In this workshop, we bring together researchers from different communities to share ideas and success stories.
By showcasing key applied challenges, along with recent theoretical advances, we hope to foster connections and prompt fruitful discussion.
We invite researchers to submit extended abstracts for contributed talks and posters.



{{ new_block() }}



# Speakers

{{ grid(
    text = [
        ["Marta Blangiardo","Imperial College London"], 
        ["Viacheslav Borovitskiy","ETH Zürich"],
        ["Willie Neiswanger","Stanford University"],
        ["Paula Moraga","KAUST"],
        ["Jasper Snoek","Google Research"],
        ["Carolina Osorio","HEC Montréal and Google Research"],
    ],
    urls = [
        "https://www.imperial.ac.uk/people/m.blangiardo",
        "http://vab.im/",
        "https://willieneis.github.io/",
        "https://www.paulamoraga.com/",
        "https://research.google/people/JasperSnoek/",
        "https://www.carolinaosorio.net/",
    ],
    image_dir = "speakers",
    narrow = true) }}



{{ new_block() }}



# Schedule

| Time (USA)    | Event                                                   |
|---------------|---------------------------------------------------------|
| 09:00 - 09:30 | **Introduction and Opening Remarks: Zoubin Ghahramani** |
| 09:30 - 10:00 | Invited Talk: Willie Neiswanger                         |
| 10:00 - 10:30 | Invited Talk: Marta Blangiardo                          |
| 10:30 - 11:00 | **Coffee and Discussion**                               |
| 11:00 - 11:30 | Invited Talk: Viacheslav Borovitskiy                    |
| 11:30 - 11:45 | Contributed Talk: Pierre Thodoroff                      |
| 11:45 - 12:00 | Contributed Talk: Renato Berlinghieri                   |
| 12:00 - 13:00 | **Lunch**                                               |
| 13:00 - 13:30 | Lightning Talks                                         |
| 13:30 - 14:00 | Invited Talk: Jasper Snoek                              |
| 14:00 - 14:15 | Contributed Talk: Renzhi Chen                           |
| 14:15 - 14:45 | **Coffee and Discussion**                               |
| 14:45 - 15:15 | Invited Talk: Paula Moraga                              |
| 15:15 - 15:30 | Contributed Talk: Sulin Liu                             |
| 15:30 - 15:45 | Contributed Talk: Andreas Besginow                      |
| 15:45 - 16:45 | **Poster Session**                                      |
| 16:45 - 17:15 | Invited Talk: Carolina Osorio                           |
| 17:15 - 17:55 | **Panel Discussion**                                    | 
| 17:55 - 18:00 | **Closing Remarks**                                     |



{{ new_block() }}



# Organizers

{{ grid(
    text = [
        ["Alexander Terenin","University of Cambridge"],
        ["Geoff Pleiss","Columbia University"],
        ["Elizaveta Semenova","University of Oxford"],
        ["Zi Wang","Google DeepMind"],
    ],
    urls = [
        "https://avt.im/",
        "https://geoffpleiss.com",
        "https://elizaveta-semenova.com",
        "https://ziw.mit.edu/",
    ],
    image_dir = "organizers") }}



{{ new_block() }}



# Advisory Committee

{{ grid(
    text = [
        ["Tamara Broderick","MIT"],
        ["Carl Henrik Ek","University of Cambridge"],
        ["Seth Flaxman","University of Oxford"],
        ["Zoubin Ghahramani","Google Research"],
        ["Emtiyaz Khan","RIKEN"],
        ["Andreas Krause","ETH Zürich"],
    ],
    urls = [
        "https://tamarabroderick.com/",
        "http://carlhenrik.com/",
        "https://sethrf.com/",
        "http://mlg.eng.cam.ac.uk/zoubin/",
        "https://emtiyaz.github.io/",
        "https://las.inf.ethz.ch/krausea",
    ],
    image_dir = "advisors") }}



{{ new_block() }}



# Sponsors

{{ grid(
    text = [
        ["Google Research"],
    ],
    urls = [
        "https://research.google/",
    ],
    images = [
        "sponsors/google-research.svg"
    ]) }}



{{ new_block() }}



# Accepted Workshop Papers

{{ table(
    data = "papers.csv", 
    button_names = ["paper","poster"], 
    button_data_columns = [2,3], 
    button_output_columns = [1,1]) }}