# geekbot-rasa
A chatbot for www.geekedoutsolutions.com backed by Rasa Core - https://rasa.com/

# Train NLU Model
`python -m rasa_nlu.train -c nlu_config.yml --data data/nlu_data.md -o models --fixed_model_name nlu --project geekbot --verbose`

# Train Dialogue Model
`python -m rasa_core.train -d domain.yml -s data/stories.md -o models/geekbot/dialogue --epochs 200
`
