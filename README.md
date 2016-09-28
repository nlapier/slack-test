# slack-test
Setting up a simple web-to-slack-channel app.  Testing for our final project.  


bootcampspot2 #general webhook: https://hooks.slack.com/services/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

curl -X POST --data-urlencode 'payload={"channel": "#general", "username": "webhookbot", "text": "This is posted to #general and comes from a bot named webhookbot.", "icon_emoji": ":ghost:"}' https://hooks.slack.com/services/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
