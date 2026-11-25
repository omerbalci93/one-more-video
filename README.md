# One More Video? Measuring Topic Persistence on YouTube

DSA210 course project

## Research question

After two consecutive videos on the same topic, how many more videos do I watch before switching topics or ending the session? Which topics persist longest, and where do I go when I switch?

## Planned analysis

- Group my YouTube Takeout watch events into viewing sessions and assign topics from video titles with a local text model.
- Estimate the probability of staying on a topic, switching to another topic, or ending the session using a Markov model.
- Compare the model's predictions with observed topic runs in later weeks. Estimate the topic half-life as the number of additional videos at which half of the runs have ended.
- Present the results with a topic survival curve and a transition heatmap.

## Data

The project uses my own YouTube watch history. The raw export stays local. The analysis describes recorded viewing choices and does not establish what YouTube recommended or what caused a click.
