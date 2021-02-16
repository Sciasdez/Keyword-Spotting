# Keyword-Spotting
Using Knowledge Distillation to train a compact keyword spotting model


Keyword Spotting usually in the context of an intelligent agent, is the detection of a predefined set of utterances. The full process of the speech recognition typically
happens in the cloud, which other than privacy issues, requires resources that often slow down the command execution.
Therefore, it is desirable to have the recognition happen using models with smaller footprints that can be deployed on low power and performance-limited devices. One method to reduce the size of a model is Knowledge Distillation, which entails training a compact model (’student’) to replicate the behavior of an already trained full model (i.e. ’teacher’). In this study, based on previous work done by Raphael Tang and Jimmy Lin, 2017 (available at https://github.com/castorini/Honk) a series of experiments were conducted to investigate the possibility of performing Knowledge distillation of keyword spotting models.

