# Plant-in-the-Loop

The long-term engineering goal is a closed-loop system in which measured plant responses contribute directly to control decisions.

## Experimental watering loop

The project already contains an automated watering experiment workflow:

1. pause continuous acquisition;
2. collect baseline frames;
3. trigger a controlled watering action;
4. collect response frames;
5. evaluate predefined hypotheses;
6. store the experiment result;
7. resume continuous monitoring.

This architecture is valuable even before a biological acoustic marker has been validated because it creates reproducible stimulus-response experiments.

## Future control path

A true Plant-in-the-Loop controller would require a validated relationship between measured acoustic features and a plant state or stress response. Only then should the signal influence irrigation or another actuator automatically.

Until that validation exists, the system is an experimental closed-loop research platform rather than an autonomous plant-health controller.
