# Hello, Plant!

## Situation

I want to help my family with gardening by building an automated farm. As a robotics hobbyist, I'm excited to connect a pump to a microcontroller and water the plant whenever my plant's soil lacks moisture. But I need to first make sure that my sensors work fine.

I bought a soil moisture sensor to monitor when the plant needs water. It's easy to use, but I worry that it may not be reliable.

I read a [question from `Matthew Berman`](https://electronics.stackexchange.com/questions/90725/arduino-moisture-sensor-value-decreasing-for-no-reason) asking about his moisture sensor. His sensor was the same model as mine. When the sensor is in soil, the readings say that the soil gets wetter even if he did not water the soil.

`Connor Wolf` responded by saying that the FR4 material of the sensor is not reliable because of its structure. This made me worried that my sensor will not work properly. This project tries to confirm if Connor Wolf is right about his claims.

## Ask

This data analytics project was made to check if I can rely on the moisure sensor. This goal implies that I have assumptions about the output of the sensor. Below are some of the assumptions I had when building this project.

1. The detected soil moisture should gradually decrease.
2. The detected soil moisture should be [inversely related with temperature of the plant's environment](https://www.mdpi.com/2073-4433/11/5/503).

Given all the knowledge about my situation, I would like to ask the question below.

**Does my moisture sensor follow the assumptions I have about it?**