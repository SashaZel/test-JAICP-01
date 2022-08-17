# My test chatbot sandbox

Great integration with GitHub! I like it.

Strange test running. 
If I make test deploy - all are OK. But for the channels deploy there is an Error (with states /Greeting and /Hello - I made it with conscions intent)
Not pure behaiveor of test enviroment... Or I don't understand something.

Oh, I see it. I can check fired intents in 'Train intents and entities mode':
On 'Пока' input fires only one Intents '/пока'.
But for 'Здравствуйте' or 'Привет' inputs fires two intents: '/привет' and '/здравствуйте'
It seems like a JavaScript works in loose non-strict mode (I'll prefer ES6 syntax...)