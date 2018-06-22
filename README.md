# geekbot-rasa
A chatbot for www.geekedoutsolutions.com backed by Rasa Core - https://rasa.com/

# Rasa Core Install Instructions
Please refer to the [Rasa Core Simple Bot Tutorial](https://core.rasa.com/tutorial_basics.html#tutorial-basics) for more information on how to use these dialog files with [Rasa Core](https://core.rasa.com/index.html)

# Train NLU Model
`python -m rasa_nlu.train -c nlu_config.yml --data data/nlu_data.md -o models --fixed_model_name nlu --project geekbot --verbose`

# Train Dialogue Model
`python -m rasa_core.train -d domain.yml -s data/stories.md -o models/geekbot/dialogue --epochs 200
`

# Slack Screenshot
In this example I clicked the Pi button

![](https://github.com/Geeked-Out-Solutions/geekbot-rasa/blob/master/slack_ss.jpg)
