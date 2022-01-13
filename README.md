# Sparkd-Tennis

Given a tennis match video, our product is able to detect and track across time:
* the tennis court
* the players
* the balls

## Input
* Video of a tennis match

## Output
1. json file with all frame-by-frame collected data
2. video showing the results of our algorithm
3. map of the history of the match seen from above

### Output json - example
For each frame you the position of the ball and of the playes. Like in the example bleow:
```json
{
   "1164":{
      "ball":{
         "x":1069,
         "y":2671
      },
      "plyr1":{
         "x":660.1242478833117,
         "y":3119.943489975537
      },
      "plyr2":{
         "x":1105.7799367205557,
         "y":366.90136620082444
      }
   },
   "1165":{
      "ball":{
         "x":1069,
         "y":2672
      },
      "plyr1":{
         "x":661.384172464346,
         "y":3118.0565622605427
      },
      "plyr2":{
         "x":1107.0065524522108,
         "y":364.9214125701079
      }
   },
   "1166":{
      "ball":{
         "x":1069,
         "y":2672
      },
      "plyr1":{
         "x":663.208716381775,
         "y":3118.2110872774438
      },
      "plyr2":{
         "x":1108.4624330148888,
         "y":359.9408179625466
      }
   }
}
```
